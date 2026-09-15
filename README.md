🚦 Análisis de Movilidad Urbana y Desarrollo Económico
📊 Resumen del proyecto

Este proyecto analiza la relación entre la movilidad urbana y la productividad económica, utilizando indicadores de congestión y tiempos de viaje junto con el PIB per cápita de diferentes ciudades.

La pregunta central del análisis es:

¿Qué relación existe entre la congestión y los tiempos de viaje en una ciudad y su nivel de productividad económica, medido mediante el PIB per cápita?

El objetivo es identificar patrones que permitan determinar si existen ciudades donde altos niveles de congestión y tiempos de desplazamiento se presentan junto con bajos niveles de PIB per cápita, lo que podría señalar oportunidades para priorizar inversiones en infraestructura y movilidad.

🎯 Objetivos
Objetivo principal

Analizar la relación entre los indicadores de movilidad urbana y el PIB per cápita, identificando ciudades que presenten patrones relevantes de congestión y productividad económica.

Objetivos específicos
Analizar los niveles de congestión vehicular entre ciudades.
Comparar los tiempos de viaje y desplazamiento.
Analizar las diferencias de PIB per cápita entre ciudades.
Integrar los datos de movilidad y economía mediante una unidad común de análisis.
Identificar correlaciones entre congestión, tiempos de viaje y PIB per cápita.
Detectar valores atípicos y comportamientos que requieran investigación adicional.
Identificar ciudades potencialmente prioritarias para inversión en infraestructura de transporte.
❓ Pregunta de análisis

La investigación busca responder principalmente:

¿Qué ciudad presenta la mayor correlación significativa entre altos niveles de congestión vehicular y bajos indicadores de productividad económica, sugiriendo que podría ser priorizada para inversión en infraestructura de transporte?

Se prestará especial atención a ciudades como:

🇨🇴 Bogotá
🇵🇪 Lima
🇦🇷 Buenos Aires
🌎 Otras ciudades incluidas en el conjunto de datos

La comparación no se limitará a estas ciudades, ya que se utilizará el conjunto completo de datos para identificar si existen otras ciudades con un patrón más significativo.

🗃️ Datos utilizados

El análisis integra información de dos dimensiones principales:

🚗 Movilidad urbana

Variables relacionadas con:

Índice de congestión.
Tiempo de viaje.
Tiempo perdido en tráfico.
Indicadores de movilidad urbana.
Ciudad.
Año.
💰 Desarrollo económico

Variables relacionadas con:

PIB.
PIB per cápita.
País.
Ciudad.
Año.

La unidad principal de análisis será ciudad–año, permitiendo comparar las condiciones de movilidad y económicas correspondientes al mismo periodo.

Fuente de los datos: [Agregar fuente]

🧹 Preparación y limpieza de datos

Antes del análisis se realiza un proceso de preparación de los datasets que incluye:

Revisión de tipos de datos.
Estandarización de nombres de columnas.
Normalización de formatos.
Tratamiento de valores ausentes.
Identificación de valores duplicados.
Revisión de valores inconsistentes.
Identificación de posibles valores atípicos.
Estandarización de nombres de ciudades y países.

Posteriormente, los datos de movilidad son agregados a nivel de ciudad–año para obtener una estructura compatible con los indicadores económicos.

🔗 Integración de los datos

Para combinar la información de movilidad y desarrollo económico se utiliza una unión INNER.

La integración se realiza utilizando las claves correspondientes a:

Ciudad + Año

Esto permite trabajar únicamente con observaciones que cuentan con información disponible en ambas fuentes.

La estructura final permite analizar conjuntamente:

Ciudad
   │
   ├── Año
   │
   ├── Indicadores de tráfico
   │
   ├── Tiempos de viaje
   │
   └── PIB per cápita
🔎 Metodología

El análisis se desarrolla en las siguientes etapas:

1. Exploración inicial

Se revisan:

Dimensiones de los datasets.
Tipos de variables.
Valores faltantes.
Distribuciones.
Estadísticas descriptivas.
2. Limpieza y estandarización

Se preparan los datos para garantizar consistencia entre las fuentes.

3. Agregación

Los indicadores de movilidad se consolidan por:

Ciudad – Año

4. Integración

Se realiza una unión INNER entre los datos de movilidad y economía.

5. Análisis exploratorio

Se estudian las distribuciones, tendencias y diferencias entre ciudades.

6. Análisis de correlación

Se analiza la relación entre:

Congestión ↔ PIB per cápita
Tiempo de viaje ↔ PIB per cápita
Congestión ↔ Tiempo de viaje

La correlación se utilizará para identificar relaciones estadísticas, no para afirmar causalidad.

7. Identificación de outliers

Se investigan ciudades o periodos que presenten comportamientos significativamente diferentes al patrón general.

8. Priorización

Finalmente, se identifican ciudades que combinen:

Alta congestión.
Elevados tiempos de viaje.
Bajo PIB per cápita relativo.
Una relación estadística relevante.

Estas ciudades serán consideradas como posibles candidatas para análisis adicional y priorización de inversión en transporte.

📈 Validación visual

Para validar los resultados se utilizarán diferentes visualizaciones:

Histogramas para analizar distribuciones.
Boxplots para identificar valores atípicos.
Gráficos de dispersión para analizar relaciones entre variables.
Líneas de tendencia para observar patrones.
Gráficos temporales para analizar evolución.
Matrices de correlación para identificar relaciones entre indicadores.

En particular, los gráficos de dispersión permitirán evaluar visualmente si existe una relación entre congestión y PIB per cápita.

📋 Cobertura del análisis
Característica	Valor
Periodo analizado	[AÑO INICIAL – AÑO FINAL]
Número de ciudades	[N]
Número de países	[N]
Unidad de análisis	Ciudad – Año
Indicador económico principal	PIB per cápita
Indicadores de movilidad	Congestión / tiempos de viaje

Estos valores se actualizarán una vez finalizada la preparación de los datos.

💡 Hallazgos
Patrones principales

Esta sección se completará después de ejecutar el análisis.

Se documentarán los principales patrones encontrados entre los indicadores de movilidad y el PIB per cápita.

Outliers

Se identificarán ciudades o periodos que presenten comportamientos inusuales, por ejemplo:

Alta congestión con PIB per cápita elevado.
Alta congestión con PIB per cápita bajo.
Baja congestión con PIB per cápita elevado.
Valores extremos en tiempos de viaje.

Estos casos podrán requerir una revisión adicional de las fuentes o un análisis más profundo de factores como población, infraestructura, densidad urbana y transporte público.

🏙️ Priorización de ciudades

Uno de los resultados principales del proyecto será determinar qué ciudad presenta el patrón más relevante de:

Alta congestión + bajo PIB per cápita

La ciudad seleccionada será determinada a partir de la evidencia disponible en los datos y no únicamente por comparación visual.

La recomendación final tendrá en cuenta:

Magnitud de la congestión.
Nivel de PIB per cápita.
Relación estadística entre ambas variables.
Consistencia del patrón.
Presencia de posibles valores atípicos.
Calidad y disponibilidad de los datos.
⚠️ Importante

Una correlación negativa entre congestión y PIB per cápita no demuestra que la congestión cause menor productividad económica. El resultado debe interpretarse como una asociación que puede justificar investigaciones posteriores.

🚀 Recomendaciones

A partir de los resultados se plantearán recomendaciones orientadas a:

Identificar ciudades que deberían estudiarse con mayor profundidad.
Priorizar posibles inversiones en infraestructura de transporte.
Validar las fuentes de datos cuando existan anomalías.
Incorporar variables adicionales que puedan explicar las diferencias observadas.
Realizar análisis temporales para determinar si las relaciones se mantienen a lo largo del tiempo.

Entre las posibles variables adicionales para futuras investigaciones se encuentran:

Población.
Densidad urbana.
Ingreso promedio.
Transporte público.
Longitud de la red vial.
Tasa de motorización.
Desempleo.
Inversión pública en infraestructura.
🛠️ Tecnologías utilizadas
Python
Pandas — limpieza, transformación y análisis de datos.
NumPy — operaciones numéricas.
Matplotlib — visualización.
Seaborn — visualización estadística.
Jupyter Notebook — desarrollo y documentación del análisis.

📌 Habilidades demostradas

Este proyecto demuestra habilidades en:

Análisis exploratorio de datos (EDA).
Limpieza y transformación de datos.
Integración de datasets.
Agregación de datos por ciudad–año.
Análisis estadístico descriptivo.
Análisis de correlaciones.
Identificación de outliers.
Visualización de datos.
Análisis de indicadores económicos.
Interpretación de resultados.
Comunicación de insights.
Python para análisis de datos.
Pandas.
Matplotlib.
Seaborn.

👤 Autor
Jair Alejandro

Data Analyst | Python | SQL | Data Visualization
Este proyecto forma parte de mi portafolio de análisis de datos y busca demostrar cómo utilizar datos para analizar problemas urbanos y económicos y convertir los resultados en información útil para la toma de decisiones.
