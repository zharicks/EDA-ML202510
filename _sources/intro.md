# **Introducción**

El Análisis Exploratorio de Datos (EDA, por sus siglas en inglés) es una fase fundamental en cualquier proyecto de ciencia de datos, ya que permite comprender la estructura, distribución y calidad de los datos antes de aplicar técnicas de modelado predictivo. En el contexto de la violencia de género, el EDA adquiere una relevancia particular, dado que los datos no solo reflejan patrones estadísticos, sino también realidades sociales complejas y sensibles. Según Tukey, el EDA es "el proceso de descubrir patrones, anomalías y relaciones en los datos que pueden guiar hipótesis y decisiones posteriores" {cite:ps}`tukey1977`. En este proyecto, el EDA se aplica a un conjunto de datos proporcionado por el Sistema Nacional de Vigilancia en Salud Pública (Sivigila) de Colombia, que recopila información sobre casos de violencia de género reportados entre los años 2012 y 2022. El objetivo principal es identificar tendencias, patrones y posibles sesgos en los datos que puedan influir en la construcción de modelos de clasificación y regresión para predecir desenlaces graves, como hospitalizaciones o muertes.

La violencia de género es un problema crítico en Colombia, donde, según el Instituto Nacional de Medicina Legal y Ciencias Forenses, se reportaron más de 40,000 casos de violencia contra la mujer en 2020, con un aumento del 10% en comparación con el año anterior {cite:ps}`inmlcf2021`. Este contexto subraya la importancia de utilizar herramientas analíticas para comprender y abordar este fenómeno de manera efectiva. A través del EDA, se busca no solo preparar los datos para el modelado, sino también generar insights que puedan informar políticas públicas y estrategias de prevención.

# **Contextualización de los datos**

El conjunto de datos utilizado en este proyecto proviene del Sistema Nacional de Vigilancia en Salud Pública (Sivigila) de Colombia, una plataforma que recopila y sistematiza información sobre eventos de interés en salud pública, incluidos los casos de violencia de género. Los datos abarcan el período comprendido entre 2012 y 2022 y contienen variables demográficas, clínicas y contextuales relacionadas con las víctimas, los agresores y los eventos de violencia. Entre las variables clave se encuentran la edad, el género, la etnia, el nivel educativo, el tipo de violencia reportada, la relación entre la víctima y el agresor, y el desenlace del caso (hospitalización, muerte, entre otros).

La violencia de género es un fenómeno multidimensional que afecta desproporcionadamente a las mujeres en Colombia. Según un informe de ONU Mujeres (2020), el 35% de las mujeres en el país ha sufrido algún tipo de violencia física o sexual por parte de su pareja, y el 70% ha experimentado violencia psicológica en algún momento de su vida {cite:ps}`onumujeres2020`. Estos datos resaltan la necesidad de abordar este problema desde una perspectiva integral, utilizando herramientas de análisis de datos para identificar factores de riesgo y diseñar intervenciones efectivas.

El uso de datos de Sivigila para este proyecto es particularmente relevante, ya que este sistema es una de las principales fuentes de información sobre violencia de género en Colombia. Sin embargo, es importante reconocer las limitaciones inherentes a los datos, como la posible subnotificación de casos debido a barreras culturales, sociales o institucionales. Según un estudio de García-Moreno et al. (2015), la subnotificación de la violencia de género es un problema global, con tasas que pueden superar el 50% en algunos contextos {cite:ps}`garcia-moreno2015`. Estas consideraciones deben tenerse en cuenta durante el análisis para evitar conclusiones sesgadas o erróneas.


## **Bibliografía**
## **Referencias**
```{bibliography} references.bib
:style: plain
:filter: docname in docnames
```
