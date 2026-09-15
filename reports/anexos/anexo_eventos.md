# ANEXO B: Bitácora de Eventos y Shocks Externos (Ticker: SBUX)
**Proyecto:** Análisis Predictivo y Caracterización de Serie de Tiempo mediante Modelo SARIMA aplicado a Starbucks Corporation (SBUX)
**Investigador:** Frankli Zeña Zeña

---

![Presentación](https://dynamic-media-cdn.tripadvisor.com/media/photo-o/29/f8/c9/8c/starbucks-coffee-honduras.jpg?w=1200&h=500&s=1)

---

 <div style="page-break-after: always;"></div>

## 1. Introducción al Anexo
Este documento contiene la recopilación cronológica de eventos cualitativos que impactaron la cotización de **Starbucks Corporation (SBUX)** y sus principales competidores (Luckin Coffee, Dunkin', McCafé y Costa Coffee). El objetivo es proporcionar una base de datos de "variables dummy" o eventos de intervención para refinar el ajuste del modelo estadístico SARIMA, permitiendo distinguir entre ruido blanco estocástico y movimientos direccionales inducidos por noticias de mercado, guerras de precios o cambios estructurales.

---

![Imagen Polémica](https://elceo.com/wp-content/uploads/2024/10/starbucks_promociones_ceo_brian_niccol.jpg)

---

 <div style="page-break-after: always;"></div>

## 2. Registro de Eventos por Periodo

### 2.1. Primer Trimestre 2021 (Q1 - Recuperación Post-Pandemia)
Durante este periodo, la serie de tiempo de SBUX muestra una estabilización tras la volatilidad del 2020. Los eventos clave se centran en la competencia global y la reestructuración de la industria del café.

| Fecha | Marca Relacionada | Evento / Noticia Clave | Impacto Potencial en Serie SBUX | Fuente (URL) |
| :--- | :--- | :--- | :--- | :--- |
| **16/03/2021** | **Luckin Coffee** | Firma de acuerdo de reestructuración de deuda (RSA) para salir de la quiebra. | **Competencia:** Fortalecimiento del principal rival en China. | [Luckin IR](https://investor.luckincoffee.com/news-releases/news-release-details/luckin-coffee-enters-restructuring-support-agreement-holders/) |
| **17/03/2021** | **Starbucks** | Reunión Anual de Accionistas y lanzamiento del *50th Anniversary Blend*. | **Fundamental:** Impulso de marca y proyecciones de crecimiento. | [Global Coffee Report](https://www.gcrmag.com/starbucks-celebrates-its-50th-anniversary-and-looks-at-the-year-ahead/) |
| **18/03/2021** | **Dunkin'** | Expansión de fondos contra el hambre y consolidación del modelo *Pick-up*. | **Sustitución:** Presión en el segmento de conveniencia rápida en EE.UU. | [Dunkin' News](https://news.dunkindonuts.com/news/dunkin-joy-in-childhood-foundation-announces-another-1-million-in-funding-to-fight-hunger) |
| **19/03/2021** | **Costa Coffee** | Despliegue masivo de estaciones *Costa Express* inteligentes con Coca-Cola. | **Innovación:** Amenaza al segmento de café "on-the-go" de Starbucks. | [Caternews](https://caternewsdigital.com/internacional/costa-coffee-adios-a-las-perdidas-y-nueva-linea-de-cafeteras/) |
| **20/03/2021** | **McCafé** | Integración total en la App de McDonald's y promociones de lealtad. | **Volumen:** Competencia agresiva en precios bajos afectando tráfico matutino. | [InfoFranquicias](https://www.infofranquicias.com/fd-1348/franquicias/noticias/McDonalds.aspx) |

### 2.2. Segundo y Tercer Trimestre 2021 (Q2 - Q3)
Periodo de fuerte recuperación global post-cuarentenas, pero fuertemente marcado por la primera crisis en la cadena de suministros que afectó a toda la industria del "Quick Service Restaurant" (QSR).

| Fecha | Marca Relacionada | Evento / Noticia Clave | Impacto Potencial en Serie SBUX | Fuente (URL) |
| :--- | :--- | :--- | :--- | :--- |
| **28/04/2021** | **Starbucks** | Publicación de resultados Q2 FY21. Fuerte recuperación de ventas pre-pandemia. | **Alcista:** Confirmación de la resiliencia del negocio principal en EE. UU. | [SBUX Investor Relations](https://investor.starbucks.com/news/financial-releases/news-details/2021/Starbucks-Reports-Q2-Fiscal-2021-Results/default.aspx) |
| **25/06/2021** | **Starbucks / Dunkin'** | Escasez crítica de insumos (jarabes y vasos) a nivel nacional en EE. UU. afecta las operaciones. | **Negativo / Ruido:** Incapacidad de satisfacer demanda, generando pérdida de ventas marginales. | [Business Insider](https://www.businessinsider.com/starbucks-shortage-list-drinks-ingredients-missing-2021-6) |
| **15/09/2021** | **Starbucks** | Anuncio de incremento del 9% en el dividendo trimestral ($0.49). | **Atractivo:** Señal de solidez de caja para retener accionistas de largo plazo. | [Nasdaq](https://www.nasdaq.com/articles/starbucks-sbux-rewards-shareholders-with-nearly-9-dividend-hike-2021-09-3) |

### 2.3. Cuarto Trimestre 2021 y Primer Trimestre 2022 (Q4 2021 - Q1 2022)
Surgimiento de presiones inflacionarias agresivas, tensiones laborales (sindicalización) y transición crítica en la directiva de la empresa.

| Fecha | Marca Relacionada | Evento / Noticia Clave | Impacto Potencial en Serie SBUX | Fuente (URL) |
| :--- | :--- | :--- | :--- | :--- |
| **29/10/2021** | **Starbucks** | Compromiso de inversión salarial masiva de $1,000M para empleados (Partners) frente al riesgo sindical. | **Bajista a corto plazo:** Incremento en costos fijos y reducción de márgenes proyectados. | [CNBC News](https://www.cnbc.com/2021/10/27/starbucks-to-raise-pay-for-us-baristas-at-least-twice-next-year.html) |
| **01/11/2021** | **Costa Coffee** | Coca-Cola completa la adquisición de BodyArmor, optimizando su canal logístico masivo, beneficiando la distribución de Costa RTD. | **Competencia indirecta:** Mayor presión en los supermercados donde SBUX vende café embotellado. | [Coca-Cola Co. Press](https://www.coca-colacompany.com/news/coca-cola-to-acquire-full-ownership-of-bodyarmor) |
| **20/01/2022** | **Luckin Coffee** | Se reporta que Luckin explora re-listar sus acciones en el mercado estadounidense tras salir de su liquidación. | **Competencia directa:** El principal rival chino vuelve a capitalizarse formalmente. | [Financial Times](https://www.ft.com/content/36294e0f-217f-4447-9878-00a454d45543) |
| **16/03/2022** | **Starbucks** | El CEO Kevin Johnson anuncia su retiro; **Howard Schultz regresa** como CEO interino por tercera vez. | **Volatilidad:** El mercado celebra el regreso del fundador, pero duda sobre la falta de sucesión. | [CNN Edition](https://edition.cnn.com/2022/03/16/business/starbucks-ceo-howard-schultz) |
| **18/03/2022** | **Starbucks** | Howard Schultz suspende abruptamente el programa de recompra de acciones (*Buybacks*) para reinvertir en tiendas. | **Bajista (Fuerte):** Se retira un pilar de soporte financiero para el precio de la acción. | [Forbes](https://www.forbes.com/sites/siladityaray/2022/04/04/starbucks-shares-slide-as-howard-schultz-suspends-share-buyback-program/) |

### 2.4. Resto del Año 2022 (Q2 - Q4)
Periodo de reestructuración tecnológica ("Reinvention Plan") y crisis operativa en Asia por el entorno macroeconómico.

| Fecha | Marca Relacionada | Evento / Noticia Clave | Impacto Potencial en Serie SBUX | Fuente (URL) |
| :--- | :--- | :--- | :--- | :--- |
| **04/05/2022** | **Starbucks / Luckin** | Reporte Q2 FY22: Caída alarmante del 23% en ventas en China por la política Cero-COVID, mientras Luckin capta terreno. | **Riesgo país:** Fuerte lastre en la acción al perder rentabilidad en su 2do mercado más grande. | [CNBC SBUX Earnings](https://www.cnbc.com/2022/05/03/starbucks-sbux-q2-2022-earnings.html) |
| **03/08/2022** | **Starbucks** | Resultados Q3 superan expectativas apoyados por el consumo récord de bebidas frías ("Iced Coffee"). | **Estacionalidad positiva:** Las bebidas frías aíslan a SBUX temporalmente de la inflación en comida. | [Reuters](https://www.reuters.com/business/retail-consumer/starbucks-beats-sales-estimates-us-cold-coffee-demand-offsets-china-slump-2022-08-02/) |
| **09/08/2022** | **Luckin Coffee** | Luckin Coffee anuncia plan agresivo de expansión de tiendas en China | **Impulso de marca:** Marca Competencia se consolida dentro de territorio de alta demanda de bebidas frías. | [Reuters](https://www.reuters.com/business/retail-consumer/chinas-luckin-plans-store-expansion-remains-committed-us-market-2022-08-09/#:~:text=He%20said%20Luckin%20would%20add,such%20as%20Beijing%20and%20Shanghai) |
| **13/09/2022** | **Starbucks** | "Día del Inversor 2022": Presentación del Plan de Reinvención. Proyectan crecimiento de EPS del 15-20%. | **Estructural:** Nuevo plan técnico (Siren System) para acelerar tiempos de servicio en tienda. | [SBUX Investor Day](https://stories.starbucks.com/press/2022/starbucks-unveils-reinvention-plan-at-investor-day/) |
| **14/09/2022** | **Mercado** | Reacción de analistas de Wall Street al plan estratégico de Schultz. Se publican *upgrades* masivos de la acción. | **Impulso de tendencia:** Reversión de la tendencia bajista; aumento agresivo en el volumen de compra. | [Yahoo Finance](https://finance.yahoo.com/news/starbucks-bullish-investor-day-targets-145610815.html) |
| **24/10/2022** | **McCafé** | McDonald's invierte masivamente en su aplicación de recompensas y sistema *drive-thru* digital. | **Sustitución:** McCafé captura a los consumidores de clase media que rechazan los aumentos de precio de SBUX. | [McDonald's Corp IR](https://corporate.mcdonalds.com/corpmcd/investors.html) |
| **04/11/2022** | **Starbucks** | Reporte Q4 FY22: Ingresos globales récord a pesar de los vientos cambiarios en contra (dólar fuerte). | **Fundamental:** Confirma el estatus de la marca como inelástica. | [Reuters](https://www.reuters.com/business/retail-consumer/starbucks-beats-quarterly-sales-estimate-pricey-drinks-robust-demand-2022-11-03/#:~:text=New%20product%20launches%20and%20a,help%20it%20survive%2C%20he%20said) |

### 2.5. Año 2023 (Expansión, Recuperación y Guerra en China)
Consolidación del liderazgo de Laxman Narasimhan y un giro drástico en la hegemonía del café en China.

| Fecha | Marca Relacionada | Evento / Noticia Clave | Impacto Potencial en Serie SBUX | Fuente (URL) |
| :--- | :--- | :--- | :--- | :--- |
| **03/02/2023** | **Starbucks** | Resultados Q1 FY23: La empresa falla estimaciones de Wall Street por la persistencia de debilidad en China. | **Bajista:** Demuestra que la recuperación en Asia será más lenta de lo proyectado. (Precios/Costos suben por inflación) | [CNBC SBUX Q1](https://www.cnbc.com/2023/02/02/starbucks-sbux-q1-2023-earnings.html) & [ABC News](https://abcnews.com/GMA/Food/starbucks-expects-price-increases-citing-inflation-covid-pay/story?id=82646673%20%5bweb:20%5d) |
| **03/05/2023** | **Starbucks** | Reporte Q2 FY23. Primer trimestre con Laxman Narasimhan como CEO titular; crecimiento del 12% en ventas en EE.UU. | **Estabilidad:** El mercado aprueba los primeros pasos de la gestión sin Howard Schultz. | [SBUX IR Q2 23](https://investor.starbucks.com/news/financial-releases/news-details/2023/Starbucks-Reports-Q2-Fiscal-2023-Results/default.aspx) |
| **23/06/2023** | **Starbucks / Dunkin'** | Trabajadores sindicalizados de SBUX van a la huelga por políticas internas sobre la decoración del Mes del Orgullo. | **Riesgo Reputacional:** Cierre temporal de tiendas clave, desviando tráfico a competidores como Dunkin'. | [NPR](https://www.gpb.org/news/2023/06/23/us-starbucks-workers-join-in-weeklong-strike-over-stores-not-allowing-pride-decor) & [CNN Edition](https://edition.cnn.com/2023/06/23/business/starbucks-union-pride-strike) |
| **21/07/2023** | **Luckin Coffee** | Luckin alcanza la marca histórica de **10,000 tiendas** en China, superando ampliamente a Starbucks. | **Pérdida de Liderazgo:** SBUX cede oficialmente el trono del volumen en China frente a franquicias de bajo costo. | [Luckin Coffee IR](https://investor.luckincoffee.com/news-releases/news-release-details/luckin-coffee-reaches-10000th-store-milestone/) |
| **21/07/2023** | **Starbucks** | Starbucks contrata al ex ejecutivo de Target Arthur Valdez para dirigir las operaciones de suministro | **Cambio de Liderazgo Precipitado:** Una profunda crisis de marca que se desarrolló a lo largo de 2023 y 2024, culminando en una pérdida del 10% de su tráfico interanual comparable en América del Norte en el cuarto trimestre del año fiscal 2024.  | [Restaurant Dive](https://www.restaurantdive.com/news/starbucks-hires-taco-bell-vets-to-replace-departing-execs/738481/) |
| **02/08/2023** | **Starbucks** | Reporte Q3 FY23: Ventas comparables globales crecen un 10%, compensando la presión de volumen con incrementos de precio en tickets. | **Consolidación:** SBUX defiende sus márgenes apostando por el mercado "Premium". | [SBUX Q3 23 IR](https://investor.starbucks.com/news/financial-releases/news-details/2023/Starbucks-Reports-Q3-Fiscal-2023-Results/default.aspx) |
| **02/08/2023** | **Starbucks** | Starbucks implementa el sistema automatizado *"Siren System"* en aprox. el 10% de sus tiendas para acelerar la preparación de bebidas | **Servicio Eficiente:** La incorporación de herramientas de automatización reduciría los tiempos de espera, impulsando una mayor participación de los consumidores y aumentando las ventas durante el resto del año". | [Reuters](https://www.reuters.com/business/retail-consumer/us-fast-food-chains-add-turn-automation-boost-speed-2023-08-02/#:~:text=Aug%202%20%28Reuters%29%20,and%20potentially%20boost%20profit%20margins) |
| **01/11/2023** | **Starbucks / Dunkin'** | Lanzamiento estratégico del menú de festividades ("Holiday Menu"). | **Pico Estacional:** Punto clave para capturar el *spike* de ventas de fin de año en el modelo. | [SBUX Holiday Press](https://stories.starbucks.com/press/2023/starbucks-holiday-menu-is-back/) |
| **02/11/2023** | **Starbucks** | Reporte Q4 FY23: Superan proyecciones amplias gracias al impulso de bebidas personalizadas y frías. | **Alcista:** Impulso de fin de año en la cotización de mercado. | [Business Wire Q4](https://www.businesswire.com/news/home/20231102558696/en/Starbucks-Reports-Q4-and-Full-Year-Fiscal-2023-Results) |
| **03/11/2023** | **Mercado** | Agencias calificadoras de riesgo elevan el perfil crediticio tras reporte sólido. | **Deuda:** Menor costo de endeudamiento futuro para expansión de la cadena. | [Moody's Investors](https://www.moodys.com/credit-ratings/Starbucks-Corporation-reports-800010912) |
| **04/12/2023** | **McDonald’s** | McDonald’s prueba “CosMc’s”, nuevo concepto de tienda centrada en bebidas premium | **Nueva Competencia:** Se incorpora al rubro de bebidas frías una nueva cadena por parte de McDonal’s | [Reuters](https://www.reuters.com/business/retail-consumer/mcdonalds-tests-cosmcs-stores-burger-chain-boosts-beverages-focus-2023-12-07/#:~:text=Dec%207%20%28Reuters%29%20,out%20an%20ambitious%20growth%20plan) |

### 2.6. Año 2024 (La Caída del Tráfico, Intervención Activista y la Llegada de Brian Niccol)
Este es el periodo de mayor volatilidad estructural para la serie de tiempo. Ideal para la inserción de **variables de intervención** en el modelo SARIMA por la caída extrema de ventas y el cambio revolucionario de CEO.

| Fecha | Marca Relacionada | Evento / Noticia Clave | Impacto Potencial en Serie SBUX | Fuente (URL) |
| :--- | :--- | :--- | :--- | :--- |
| **30/01/2024** | **Starbucks** | Resultados Q1 FY24: Récord de $9.4B en ingresos, pero el crecimiento de ventas comparables de 5% decepciona a analistas. | **Agotamiento de Tendencia:** Se visualiza el límite de subir precios ante un consumidor agotado. | [SBUX Q1 24 Press](https://about.starbucks.com/press/2024/starbucks-reports-q1-fiscal-2024-results/) |
| **31/01/2024** | **Mercado / SBUX** | Analistas asimilan en la acción el impacto adverso de boicots internacionales ligados al conflicto en Medio Oriente. | **Contradicción de Activos:** Acciones suben ~4% tras reportar resultados Q1 FY2024 mejor de lo esperado y recortar pronóstico; Niccol gestiona headwinds. | [Reuters](https://www.reuters.com/business/retail-consumer/starbucks-misses-quarterly-sales-estimates-2024-01-30/#:~:text=Its%20shares%2C%20however%2C%20rose%204,traffic%20in%20November%20and%20December) |
| **15/03/2024** | **Starbucks** | Cierre oficial de "Starbucks Odyssey", su cuestionado programa de lealtad basado en NFTs/Web3. | **Reestructuración:** SBUX elimina gastos ineficientes para enfocarse en Recompensas tradicionales. | [The Spoon / Web3](https://thespoon.tech/not-surprisingly-starbucks-is-shutting-down-its-nft-program/) |
| **01/05/2024** | **Starbucks** | **Reporte Q2 FY24:** Resultados desastrosos. Caída masiva del tráfico global; ventas en EE.UU. y China retroceden. | **Choque Negativo (Outlier):** La acción **se desploma más de un 15%** en un solo día, alterando fuertemente los residuales. | [Kiplinger SBUX Crash](https://www.kiplinger.com/investing/stocks/starbucks-stock-q2-earnings-miss) & [Reuters](https://www.reuters.com/business/retail-consumer/starbucks-shares-tumble-china-us-demand-slowdown-clouds-outlook-2024-05-01/#:~:text=May%201%20%28Reuters%29%20,expected%20economic%20recovery%20in%20China) |
| **21/06/2024** | **Dunkin' / McCafé** | Starbucks lanza promociones agresivas ("Pairings Value Menu") para recuperar tráfico robado por opciones económicas. | **Margen vs. Volumen:** Intento defensivo ante el éxito del "value menu" de la competencia. | [CNN Business Value](https://www.cnn.com/2024/06/21/business/starbucks-value-meal/) |
| **19/07/2024** | **Mercado / SBUX** | Se revela que el fondo activista **Elliott Investment Management** ha tomado una gran participación accionarial exigiendo cambios. | **Punto de inflexión:** El mercado huele un inminente despido directivo, sosteniendo artificialmente el precio. | [Peltz International](https://peltzinternational.com/activist-elliott-building-stake-in-starbucks/) |
| **13/08/2024** | **Starbucks** | SBUX anuncia la sorpresiva destitución de Laxman Narasimhan y nombra como **nuevo CEO a Brian Niccol** (ex-Chipotle). | **Choque Positivo Estructural:** Revalorización inmediata de las expectativas a largo plazo del mercado. | [SBUX Niccol Press](https://about.starbucks.com/press/2024/starbucks-names-brian-niccol-as-chairman-and-chief-executive-officer/) & [Reuters](https://www.reuters.com/business/retail-consumer/starbucks-names-chipotles-brian-niccol-ceo-2024-08-13/#:~:text=Aug%2013%20%28Reuters%29%20,coffee%20chain%27s%20shares%20up%2024) |
| **14/08/2024** | **Mercado** | Efecto inmediato post-anuncio: La acción de Starbucks se dispara un histórico **24% en bolsa** en un día. | **Anomalía Positiva Máxima:** Deberás aislar esta fecha matemática en tu SARIMA para no sesgar el modelo. | [Harvard Law Forum](https://corpgov.law.harvard.edu/2024/10/01/activism-vulnerability-report-3/) |
| **23/10/2024** | **Starbucks** | Adelanto preliminar del Q4 FY24: Niccol suspende previsiones para 2025 ante caída de ventas, pero aumenta dividendo. | **Reset Estratégico:** "Limpieza de balance" (*Kitchen sinking*) para empezar con expectativas bajas. | [Nasdaq SBUX Oct](https://www.nasdaq.com/articles/starbucks-slips-dismal-preliminary-results-and-suspended-guidance) |
| **03/11/2024** | **Luckin Coffee** | Luckin Coffee anuncia plan de expansión en territorio Americano | **Expansión de la Competencia:** Expansión internacional ambiciosa y cargada de simbolismo. Estados Unidos como próximo gran campo de batalla en la competencia global del café. | [La República](https://larepublica.pe/estados-unidos/2024/11/03/luckin-coffee-la-cafeteria-que-derroto-a-starbucks-en-china-busca-conquistar-estados-unidos-lrtmusv-40665) |

### 2.7. Año 2025 (Ejecución de la Estrategia "Back to Starbucks" y Guerras de Precios)
*Nota metodológica: Para efectos del horizonte de tu investigación (Feb 2026), estos datos documentan los cierres fiscales y las respuestas competitivas clave del año previo.*

| Fecha | Marca Relacionada | Evento / Noticia Clave | Impacto Potencial en Serie SBUX | Fuente (URL) |
| :--- | :--- | :--- | :--- | :--- |
| **29/01/2025** | **Starbucks** | Reporte Oficial Q1 FY25: Primer *Earnings Call* completo bajo la gestión táctica de Brian Niccol. | **Fundamental:** Verificación de la efectividad inicial en tiempos de servicio (Siren System). | [Reuters](https://www.reuters.com/business/retail-consumer/starbucks-posts-smaller-than-expected-comparable-sales-decline-turnaround-takes-2025-01-28/#:~:text=Starbucks%27%20global%20same,to%20data%20compiled%20by%20LSEG) |
| **03/04/2025** | **Starbucks** | Reunión Anual de Accionistas. El liderazgo confirma prioridades sobre el ambiente de las tiendas. | **Cultura Corporativa:** Refuerzo de confianza del capital institucional en el cambio cultural de SBUX. | [SBUX Shareholder Events](https://investor.starbucks.com/events-and-presentations/default.aspx) |
| **30/04/2025** | **Starbucks** | Publicación del Reporte Q2 FY25. Evaluación del mercado tras el periodo estacionalmente más plano del año. | **Ajuste de Expectativas:** Demuestra si Niccol logró detener la "fuga de tráfico" reportada justo un año antes; sin embargo, ventas comparables global -1% (NA -1% vs -0.24% esperado), utilidades peor; acción baja ~6% tras reporte | [Reuters](https://www.reuters.com/business/starbucks-posts-bigger-than-expected-drop-global-sales-2025-04-29/#:~:text=North%20American%20same,to%20growth%20in%20the%20quarter) |
| **24/05/2025** | **McDonal's** | McDonald's cierra su cadena CosMc's después de menos de 2 años | **Estrategia:** Conocimientos del Piloto CosMC's será utilizado para ofrecer bebidas durante una próxima prueba de bebidas en los Estados Unidos. | [People](https://people.com/mcdonalds-shutting-down-cosmcs-chain-after-less-than-2-years-11741448) |
| **27/06/2025** | **McCafé** | Intensificación de campañas agresivas de "Value Deals" para atraer consumidores de bajos ingresos durante el verano. | **Sensibilidad de Ingresos:** Diferencia de tráfico entre el consumidor aspiracional de SBUX y el pragmático de McDonald's. | [McDonald's Corp IR](https://corporate.mcdonalds.com/corpmcd/investors.html) |
| **02/07/2025** | **Luckin Coffee** | Luckin Coffee llegó a Nueva York con un modelo que apuesta por precios bajos y tecnología. | **Competencia a menor Precio:** En China Luckin ofrece bebidas desde 8,8 yuanes (aprox. US\$1,23), cifra muy por debajo del promedio de Starbucks. En Nueva York, replicó esa estrategia con una promoción que permite a los nuevos clientes comprar su primera bebida a US$1,99 si utilizan la app oficial. | [La República](https://larepublica.pe/mundo/2025/07/02/la-cadena-china-de-cafe-que-supero-a-starbucks-y-ahora-conquista-estados-unidos-con-precios-ultra-bajos-166022) |
| **29/07/2025** | **Mercado (Commodities)** | Altas fluctuaciones y revisiones contractuales sobre los precios del futuro del **Café Arábica (ICE)**. | **Riesgo de Insumos (Variables Dummy):** Posible presión en el costo de los bienes vendidos (COGS) de la empresa. | [ICE Coffee Arabica Data](https://www.theice.com/products/15/Coffee-C-Futures) |
| **30/07/2025** | **Starbucks** | Reporte Q3 FY25. Medición del impacto del menú de verano (dependiente de bebidas frías como Refreshers). | **Estacionalidad validada:** Validación del modelo de ventas impulsado por el segmento Generación Z. | [SBUX Financial Releases](https://investor.starbucks.com/) |

### 2.8. Año 2026 (Situación Actual del Proyecto)
Eventos y perspectivas de inicio de año coincidiendo con el desarrollo del análisis.

| Fecha | Marca Relacionada | Evento / Noticia Clave | Impacto Potencial en Serie SBUX | Fuente (URL) |
| :--- | :--- | :--- | :--- | :--- |
| **14/01/2026** | **Coca Cola** | Coca-Cola abandona plan de venta de Costa Coffee | **Presión:** Se genera incertidumbre acerca del estado de la competencia | [Retail Detail](https://www.retaildetail.es/news/alimentacion/coca-cola-renuncia-a-la-venta-de-costa-coffee/)
| **28/01/2026** | **Starbucks** | Publicación oficial del Reporte Q1 FY26 (Cierre de fin de año 2025). | **Consolidación del "Turnaround":** Momento cumbre que demuestra cuantitativamente si la visión de Brian Niccol estabilizó las ventas. Se anuncia retorno a márgenes pre-COVID (13.5–15% para FY2028) y plan de renovación de tiendas y café-tech; asimismo, crecimiento en ventas en EE.UU. tras 2 años. | [Reuters](https://www.reuters.com/business/starbucks-seeks-pre-pandemic-profit-margins-ceo-niccols-first-investor-day-2026-01-29/#:~:text=Starbucks%20executives%20said%20that%20by,35%20to%20%244) |
