# ☕ Starbucks (SBUX) - Predicción Estocástica y Análisis Cuantitativo con SARIMAX

![Python](https://img.shields.io/badge/Python-3.10+-blue.svg) ![Statsmodels](https://img.shields.io/badge/Statsmodels-Econometrics-orange.svg) ![Plotly](https://img.shields.io/badge/Plotly-Interactive_Charts-purple.svg)

---

## 📌 1. Introducción y Objetivos

El presente repositorio documenta un estudio estadístico temporal (econométrico) exhaustivo sobre la serie de precios y retornos de **Starbucks Corporation (Ticker: SBUX)**. En el ámbito de la Ingeniería, la comprensión de la dinámica de los activos financieros exige ir más allá del análisis técnico tradicional; requiere la integración de la salud financiera de la empresa y el impacto psicológico de los shocks externos.

Para lograr esto, se emplea la metodología **SARIMAX** (Seasonal AutoRegressive Integrated Moving Average with eXogenous variables). Este enfoque estocástico permite descomponer la serie en sus componentes de tendencia y estacionalidad, mientras simultáneamente mide el impacto paramétrico de variables explicativas cuantitativas (Estados Financieros) y cualitativas (Variables Dummy de Intervención).

## 🏢 2. Marco Institucional: El “Choque Estructural”

El análisis matemático se fundamenta en la realidad corporativa de Starbucks. Durante el periodo de estudio (2021-2026), la empresa atravesó turbulencias directivas significativas. El modelo cuantifica matemáticamente el **“Choque Estructural”** provocado por la inestabilidad de liderazgo (salida de Kevin Johnson, retorno de Howard Schultz, breve mandato de Laxman Narasimhan y la reciente era de Brian Niccol).

## 📈 3. Metodología y Descubrimientos Empíricos

### A. La Microestructura y el Ciclo de 21 Días

Mediante el análisis de anomalías de volumen (43 detectadas) y la Descomposición Clásica, se identificó una fuerte autocorrelación cíclica en el rezago **m=21**.

> **Hallazgo:** Un mes de calendario típico contiene en promedio 21 días hábiles de negociación. Esta estacionalidad refleja el comportamiento institucional masivo: cierres contables, ejecución de opciones (Options Expiration) y rebalanceos sistemáticos de portafolio.

### B. Transformación Dual y Estacionariedad

Se contrastaron dos enfoques mediante la Prueba de Dickey-Fuller Aumentada (ADF):

1.  **Precio Absoluto:** Comportamiento de Caminata Aleatoria (d=1).
2.  **Retornos Logarítmicos:** Estacionarios en nivel (d=0), alineados a los axiomas de la econometría financiera para estabilizar la varianza.

### C. Inferencia Exógena (Feature Selection)

Al evaluar el p-valor de la matriz de variables exógenas (Xt), el modelo dictaminó:

-   **Variables Significativas (p < 0.05):** `choque_estructural`, `shock_extremo`, `earnings` y `shock_costos`. Estas detonan euforia o liquidaciones masivas inmediatas.
-   **Variables Descartadas (p > 0.05):** `riesgo_pais`, `Margen_Operativo_%` y `Revenue`. El mercado asimila estas variables a largo plazo, perdiendo su poder predictivo diario.

### D. Colapso del Multi-Step vs. Éxito del Walk-Forward

Se demostró empíricamente que el **Pronóstico Tradicional (Multi-Step)** fracasa en series financieras. La proyección converge a la media, generando una línea plana (“Flatlining”) que arrojó un **MSE crítico de 6390.7592** sobre la serie en niveles, suprimiendo la varianza estocástica.

> Idea final: Para solucionar esta limitación estructural, se propuso una simulación **Walk-Forward Validation**. El algoritmo predice t+1, observa el dato empírico, actualiza su memoria, re-optimiza pesos y avanza a t+2, logrando mapear los quiebres de volatilidad reales.

---

## 📂 4. Arquitectura del Repositorio

El proyecto está diseñado para ser 100% reproducible. Se proponen 7 *notebooks*, incluyendo el forecast avanzado con Walk-Forward

```bash
sbux-time-series-analysis/
├── data/
│   ├── external/               
│   ├── processed/         
│   ├── raw/         
│   └── transformed/        
├── notebooks/
│   ├── 00_sbux_history_timelines.ipynb                     # Contexto y Radar Exógeno
│   ├── 01_data_acquisition_cleaning.ipynb                  # API y Forward-Fill Imputation
│   ├── 02_eda_and_news_analysis.ipynb                      # Detección de anomalías de volumen
│   ├── 03_stationarity_and_prep.ipynb                      # Análisis ADF de Precios (Niveles)
│   ├── 03.1_stationarity_and_prep.ipynb                    # Análisis ADF de Retornos Logarítmicos
│   ├── 04_adjustment_forecasting_and_validation.ipynb      # Análisis SARIMAX de Precios
│   ├── 04.1_adjustment_forecasting_and_validation.ipynb    # Análisis SARIMAX de Retornos Logarítmicos
│   └── 05_seasonal_patterns.ipynb                          # Análisis de Patrones Estacionales   
├── results/
│   └── figures/                                            # Gráficos exportados
├── reports/
│   ├── forecasting-analysis-sbux-presentation.pdf          # Presentación Previa al Informe          
│   └── forecasting-analysis-sbux-final-report.md           # Informe técnico completo
└── README.md                                               # Este documento
```