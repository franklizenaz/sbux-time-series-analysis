# ANEXO C: Diccionario de Shocks Externos

 **Proyecto:** _Análisis Predictivo y Caracterización de Serie de Tiempo mediante Modelo SARIMA aplicado a Starbucks Corporation (SBUX)_\
 **Investigador:** Frankli Zeña Zeña\

---

 ## 1\. Listado de Dummies para SARIMAX

 Las variables exógenas se organizan según la naturaleza del shock o evento que puede afectar el comportamiento de la serie temporal de **Starbucks Corporation (SBUX)**.

 ### 1.1. Variables estructurales — Intervención permanente

 | Variable | Descripción |
| --- | --- |
| `choque_estructural` | Cambios de CEO |
| `restructuracion` | Cambios estratégicos corporativos |
| `plan_estrategico` | Implementación de planes estratégicos |

### 1.2. Mercado financiero

 | Variable | Descripción |
| --- | --- |
| `earnings` | Eventos asociados a la publicación de resultados financieros |
| `revision_analistas` | Revisiones o cambios en las expectativas de los analistas |
| `riesgo_credito` | Cambios asociados al riesgo crediticio de la empresa |
| `politica_capital` | Modificaciones en la política de capital |
| `politica_accionista` | Cambios relacionados con la política hacia los accionistas |
| `activismo` | Activismo de accionistas e intervenciones de inversores |

### 1.3. Competencia

 | Variable | Descripción |
| --- | --- |
| `competencia_global` | Intensificación de la competencia a escala global |
| `competencia_qsr` | Presión competitiva del segmento _Quick Service Restaurants_ (QSR) |
| `competencia_precio` | Presión competitiva relacionada con precios |
| `competencia_retail` | Competencia en el segmento _retail_ |
| `competencia_b2b` | Competencia en el segmento _Business-to-Business_ (B2B) |
| `guerra_precios` | Episodios de competencia agresiva mediante reducción de precios |

### 1.4. Macroeconómicos y costos

 | Variable | Descripción |
| --- | --- |
| `shock_costos` | Incrementos o perturbaciones significativas en costos |
| `riesgo_pais` | Cambios en las condiciones de riesgo país |
| `shock_operativo` | Perturbaciones que afectan las operaciones de la empresa |

### 1.5. Demanda y reputación

 | Variable | Descripción |
| --- | --- |
| `shock_laboral` | Conflictos, huelgas u otros eventos relacionados con la fuerza laboral |
| `shock_reputacional` | Eventos que afectan la reputación o percepción pública de la empresa |
| `confianza_institucional` | Variaciones en la confianza hacia la empresa o sus instituciones |

### 1.6. Estacionalidad

 | Variable | Descripción |
| --- | --- |
| `estacionalidad_verano` | Efectos asociados a la temporada de verano |
| `estacionalidad_navidad` | Efectos asociados al periodo navideño |

### 1.7. Innovación

 | Variable | Descripción |
| --- | --- |
| `innovacion_operativa` | Implementación de innovaciones que modifican o mejoran las operaciones |

### 1.8. Eventos extremos

 | Variable | Descripción |
| --- | --- |
| `shock_extremo` | Eventos extraordinarios o de elevada magnitud que generan una perturbación significativa en la serie |

---

 ## 2\. Análisis de Uso

 A partir del conjunto total de variables identificadas, se seleccionan **5 variables exógenas como especificación óptima desde el punto de vista empírico** para su incorporación al modelo **SARIMAX**:

 | N.º | Variable exógena | Categoría |
| --- | --- | --- |
| 1 | `choque_estructural` | Estructural |
| 2 | `shock_extremo` | Eventos extremos |
| 3 | `earnings` | Mercado financiero |
| 4 | `riesgo_pais` | Macroeconómico |
| 5 | `shock_costos` | Macroeconómico / costos |

### Especificación exógena seleccionada

```
X_t = [
    choque_estructural,
    shock_extremo,
    earnings,
    riesgo_pais,
    shock_costos
]
```

 Estas cinco variables constituyen el **conjunto de variables exógenas seleccionado para la especificación SARIMAX**, preservando la información relevante del diccionario completo de shocks externos.

---

 ## 3\. Resumen de la Selección

 > **Variables exógenas óptimas empíricamente:**
>
>  **`choque_estructural` · `shock_extremo` · `earnings` · `riesgo_pais` · `shock_costos`**

 El conjunto seleccionado busca representar, de manera parsimoniosa, **cambios estructurales, eventos extraordinarios, información financiera y condiciones macroeconómicas y de costos**, evitando incorporar simultáneamente todas las dummies disponibles en la especificación final del modelo.