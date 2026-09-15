# 🚦 Análisis de Tráfico y Desarrollo Económico

## 📊 Descripción

Este proyecto analiza la relación entre la **movilidad urbana** y la **productividad económica**, utilizando indicadores de congestión, tiempos de viaje y **PIB per cápita** de 15 ciudades de América Latina durante 2024.

### 🎯 Pregunta principal

> **¿Qué relación existe entre la congestión y los tiempos de viaje y la productividad económica de una ciudad, medida mediante el PIB per cápita?**

El análisis busca identificar patrones que puedan aportar información para la **planificación urbana y la toma de decisiones sobre infraestructura y transporte**.

## 🔗 Análisis en Google Colab

👉 **[Abrir análisis completo en Google Colab]([https://drive.google.com/file/d/12n1YDX1z2cLfxLnfoVdftz1QF2uq4hTl/view?usp=sharing](https://colab.research.google.com/drive/12n1YDX1z2cLfxLnfoVdftz1QF2uq4hTl#scrollTo=20efc079))**

## 🗃️ Datos

Se integraron dos dimensiones:

* 🚗 **Movilidad urbana:** congestión, tiempos de viaje, longitud y cantidad de atascos y `jams_delay`.
* 💰 **Desarrollo económico:** PIB per cápita.

El análisis comprende **15 ciudades de América Latina** durante 2024, utilizando **ciudad y año** como unidad de integración.

## 🔎 Metodología

1. Limpieza y estandarización de las variables.
2. Conversión de fechas y variables numéricas.
3. Agregación de los datos de tráfico por **ciudad, país y año**.
4. Integración de las fuentes mediante un **INNER JOIN** utilizando `city` y `year`.
5. Análisis exploratorio de distribuciones y valores atípicos.
6. Visualización de la relación entre movilidad y PIB per cápita.
7. Interpretación de patrones y posibles ciudades prioritarias.

Se utilizaron histogramas, gráficos de dispersión y análisis de outliers para validar visualmente los resultados.

## 📈 Principales hallazgos

Los datos **no evidencian una relación clara y consistente** entre el PIB per cápita y los niveles de congestión o tiempos de viaje.

Un ejemplo es **Montevideo**, que presenta uno de los PIB per cápita más altos y, simultáneamente, uno de los menores niveles de congestión. En contraste, **Ciudad de México** presenta un PIB per cápita elevado, pero registra el mayor nivel de congestión entre las ciudades analizadas.

Esto indica que **el nivel de desarrollo económico por sí solo no permite explicar las condiciones de movilidad urbana**.

### 🇧🇷 Patrón destacado en Brasil

Las ciudades brasileñas muestran un comportamiento particularmente interesante. **Curitiba, Fortaleza, Belo Horizonte, Brasilia, Porto Alegre, Recife y Salvador** combinan un desempeño económico relativamente favorable con bajos niveles de `jams_delay`.

Sin embargo, Brasil concentra una gran proporción de las observaciones del conjunto de datos, por lo que este patrón podría estar **sobrerrepresentado**. Se requiere un análisis estadístico adicional para determinar si existe una relación significativa.

### ⚠️ Outliers y casos particulares

Se identificaron ciudades con comportamientos diferentes al patrón general. Estos casos podrían estar relacionados con factores estructurales como:

* Densidad urbana.
* Infraestructura vial.
* Transporte público.
* Población.
* Características territoriales.
* Diferencias en las fuentes y metodologías de medición.

## 🏙️ Priorización para infraestructura

A partir de los indicadores analizados, **Montevideo** aparece como una ciudad con potencial para evaluar inversiones en infraestructura de transporte. Su combinación de **alto PIB per cápita y baja congestión** podría representar una oportunidad para fortalecer su movilidad y aprovechar las condiciones existentes.

Sin embargo, el análisis también demuestra que **el tráfico por sí solo no explica el desarrollo económico**. Por esta razón, una decisión de inversión debería incorporar variables adicionales antes de establecer una prioridad definitiva.

## 💡 Recomendaciones

* Analizar con mayor profundidad las ciudades con niveles elevados de congestión.
* Validar la calidad, cobertura y metodología de las fuentes utilizadas.
* Incorporar variables como población, densidad urbana, transporte público e infraestructura vial.
* Calcular coeficientes de correlación y pruebas de significancia estadística.
* Comparar los resultados entre países para evitar que un país con mayor cantidad de registros domine las conclusiones.

> ⚠️ **Importante:** una correlación no implica causalidad. Los resultados encontrados representan asociaciones observadas en los datos de 2024 y no demuestran que la congestión cause una menor productividad económica.

## 🛠️ Tecnologías

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Google Colab

## 📌 Habilidades demostradas

* Limpieza y transformación de datos.
* Integración de datasets mediante `INNER JOIN`.
* Agregación por ciudad–año.
* Análisis exploratorio de datos (EDA).
* Análisis de correlaciones.
* Identificación de outliers.
* Visualización de datos.
* Interpretación de indicadores económicos.
* Comunicación de insights y recomendaciones.

## 👤 Autor

**Loky**
Data Analyst | Python | SQL | Data Visualization

Proyecto desarrollado como parte de mi portafolio de análisis de datos.
