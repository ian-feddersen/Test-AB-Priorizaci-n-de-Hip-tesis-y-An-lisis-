# Test-AB-Priorizaci-n-de-Hip-tesis-y-An-lisis-
Test A/B Priorización de Hipótesis y Análisis tienda online

# 📊Priorización de Hipótesis y Análisis de Test A/B para una Tienda Online
# A/B Testing


## 📌Descripción del Proyecto
Este proyecto se centra en la priorización de hipótesis y el análisis de un test A/B para una gran tienda online. El objetivo es identificar las hipótesis más prometedoras para aumentar los ingresos y evaluar los resultados de un test A/B para determinar si una nueva estrategia (grupo B) es más efectiva que la actual (grupo A).

### Parte 1: Priorización de Hipótesis
Se utilizaron dos frameworks para priorizar las hipótesis:

ICE (Impact, Confidence, Effort): Evalúa el impacto, la confianza y el esfuerzo requerido para implementar cada hipótesis.

RICE (Reach, Impact, Confidence, Effort): Similar a ICE, pero incluye el alcance (Reach) como un factor adicional.

### Parte 2: Análisis del Test A/B
Se analizaron los resultados de un test A/B para evaluar:

Ingresos acumulados por grupo.

Tamaño promedio de pedido acumulado.

Tasa de conversión.

Significancia estadística de las diferencias entre los grupos.

## 🛠Tecnologías Utilizadas
Lenguajes de programación: Python

Librerías principales: Pandas, Matplotlib, Seaborn, Scipy

Herramientas: Jupyter Notebook

Métricas clave: ICE, RICE, Tasa de Conversión, Tamaño Promedio de Pedido, Significancia Estadística

## 📊Estructura del Proyecto
### 1. Priorización de Hipótesis
Carga de datos: Se cargaron las hipótesis desde el archivo hypotheses_us.csv.

Cálculo de scores ICE y RICE: Se calcularon los scores para cada hipótesis y se ordenaron en orden descendente.

Comparación de resultados: Se compararon los resultados de ICE y RICE para identificar cambios en la priorización.

### 2. Análisis del Test A/B
Carga de datos: Se cargaron los datos de pedidos (orders_us.csv) y visitas (visits_us.csv).

Ingresos acumulados: Se representó gráficamente el ingreso acumulado por grupo.

Tamaño promedio de pedido: Se calculó y representó gráficamente el tamaño promedio de pedido acumulado por grupo.

Tasa de conversión: Se calculó la tasa de conversión diaria por grupo y se representó gráficamente.

Significancia estadística: Se evaluó la significancia estadística de las diferencias en la conversión y el tamaño promedio de pedido entre los grupos.

# 📈Resultados Clave
## Priorización de Hipótesis
## Hipótesis más prometedoras:

Add a subscription form to all the main pages (ICE: 112.0, RICE: 112.0).

Add product recommendation blocks to the store (ICE: 56.0, RICE: 56.0).

Add two new channels for attracting traffic (ICE: 40.0, RICE: 40.0).

Comparación ICE vs RICE: En este caso, ambos frameworks produjeron los mismos resultados, lo que sugiere que las hipótesis seleccionadas están bien alineadas con los objetivos de negocio.

## Análisis del Test A/B
#### Ingresos acumulados: El grupo B mostró un ingreso acumulado ligeramente superior al grupo A, pero la diferencia no fue significativa.

#### Tamaño promedio de pedido: No se observaron diferencias significativas en el tamaño promedio de pedido entre los grupos.

#### Tasa de conversión: La tasa de conversión fue similar en ambos grupos, sin diferencias estadísticamente significativas.

#### Significancia estadística:

#### Conversión: p-value = 0.0923 (no significativo).

#### Tamaño promedio de pedido: p-value = 0.3745 (no significativo).

# 📈Conclusiones y Recomendaciones
## Priorización de Hipótesis
Implementar las hipótesis más prometedoras: Las hipótesis con los scores más altos (ICE y RICE) deben ser priorizadas para su implementación, ya que tienen el mayor potencial para aumentar los ingresos.

## Análisis del Test A/B
No hay diferencias significativas: No se encontraron diferencias estadísticamente significativas entre los grupos A y B en términos de ingresos, tamaño promedio de pedido y tasa de conversión.

#### Decisión final: Dado que no hay evidencia suficiente para afirmar que el grupo B es más efectivo que el grupo A, se recomienda continuar la prueba para recopilar más datos o considerar otras estrategias para mejorar los resultados.

