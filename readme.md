 Proyecto de Análisis de Siniestros Viales en CABA

## Introducción

Este proyecto se enfoca en el análisis de datos de siniestros viales en la Ciudad Autónoma de Buenos Aires (CABA) durante el periodo 2016-2021. El objetivo principal es proporcionar insights para la toma de decisiones orientadas a mejorar la seguridad vial y reducir el número de víctimas fatales.

## Estructura del Proyecto

El proyecto se estructura en tres fases principales: ETL (Extract, Transform, Load), EDA (Exploratory Data Analysis) y el desarrollo y análisis de KPIs (Key Performance Indicators).

### ETL

El proceso de ETL involucró la extracción de datos archivos excel ed la Ciudad Autónoma de Buenos Aires, seguido de una serie de transformaciones para limpiar y estructurar los datos. Las principales tareas de limpieza y transformación incluyeron:

- Identificación y manejo de valores faltantes.
- Conversión de tipos de datos.
- Normalización de datos.
- Creación de nuevas columnas para facilitar análisis posteriores.

### EDA

El Análisis Exploratorio de Datos se centró en identificar tendencias, patrones y anomalías en los datos. Se dividieron las variables en numéricas y categóricas y a partir de esa distinción se realizó un análisis en busca de tendencias y patrones.Adicionalmente se normalizaron datos y se realizó un tratamiento de nulos y duplicados.

Finalmente, en esta etapa se desarrollaron y analizaron tres KPIs:

1. **Reducción de la Tasa de Homicidios en Siniestros Viales:** Enfocado en disminuir la tasa de homicidios en siniestros viales en CABA.
2. **Reducción de Accidentes Mortales de Motociclistas:** Orientado a reducir la cantidad de accidentes mortales de motociclistas en CABA.
3. **Reducción de accidentes de tránsito fatales entre jóvenes de 18 a 30 años en un 5% respecto al año anterior en CABA.
:** Propuesto para enfocarse en la seguridad de este rango etario.

Cada KPI fue analizado en detalle, considerando la evolución anual de los incidentes, el impacto de la pandemia y otros factores externos. 

## Herramientas Utilizadas

- requests: Permite enviar solicitudes HTTP/1.1 con facilidad en Python, utilizada para realizar solicitudes a la web y obtener datos.
- BeautifulSoup (bs4): Una biblioteca para analizar documentos HTML y XML, facilita la extracción de datos de páginas web.
- pandas: Proporciona estructuras de datos y herramientas de análisis de datos de alto rendimiento y fáciles de usar, como los DataFrame.
- warnings: Utilizado para controlar la emisión de advertencias en Python, permitiendo suprimirlas o mostrarlas según sea necesario.
- numpy (np): Ofrece soporte para arrays y matrices grandes y multidimensionales, junto con una colección de funciones matemáticas para operar en estos arrays.
- seaborn (sns): Una biblioteca de visualización de datos basada en matplotlib que proporciona una interfaz de alto nivel para dibujar gráficos estadísticos atractivos e informativos.
- matplotlib.pyplot (plt): Una colección de funciones estilo comando que hacen que matplotlib funcione como MATLAB, utilizada para crear gráficos y visualizaciones de datos en 2D.

## Conclusiones y Recomendaciones

La mayoría de los incidentes involucran a 1 víctima, esta suele ser de sexo masculino peatón o conductor de una moto. La probabilidad más alta de que el accidente sea fatal es en las avenidas.
La mayoría de las víctimas están en el rango de 20 a 60 años; la presencia de individuos muy jóvenes y muy mayores es mucho menos frecuente. 

La cantidad total de víctimas fatales fue relativamente estable entre 2016 y 2018, con una ligera disminución en 2019. Se observa, además, una reducción notable en 2020, que podría ser atribuible a eventos específicos de ese año, como la pandemia de COVID-19 y las consecuentes restricciones de movilidad o cambios en el comportamiento social.
En 2021, la cantidad de víctimas permanece por debajo de los niveles de 2018, aunque muestra una ligera recuperación respecto a 2020.

Por otro lado, podemos apreciar un aumento en los accidentes fatales en los meses finales del año (noviembre y diciembre), probablemente relacionado con factores estacionales como las vacaciones o las condiciones climáticas.
La frecuencia de incidentes aumenta desde la madrugada hasta alcanzar un primer pico en las horas de la mañana. Luego hay una disminución durante el mediodía seguida de un incremento nuevamente en la tarde. Finalmente, la frecuencia disminuye después de las horas pico de la tarde, con los incidentes menos frecuentes durante la noche.

Recomendaciones:

1. Campañas de concientización dirigidas a jóvenes: Dado que la mayoría de las víctimas están en el rango de edad de 18 a 30 años, sería conveniente desarrollar campañas de concienciación y educación vial específicamente dirigidas a este grupo etario.
2. Programas de educación vial para conductores de motocicletas: Implementar programas de capacitación y educación vial obligatorios para los conductores de motos, enfocándose en técnicas de conducción segura, uso adecuado del casco y otras medidas de protección.
3. Mejoras en la infraestructura de avenidas: Realizar mejoras en la infraestructura en los puntos críticos, como la instalación de semáforos, señalización adecuada, pasos peatonales seguros y carriles exclusivos para motocicletas.