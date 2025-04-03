# **Machine Learning para la prevención de desenlaces críticos en violencia de género: Un estudio aplicado a datos colombianos (2018–2023)**

## **Contextualización de los datos**

El conjunto de datos utilizado en este proyecto proviene del Sistema Nacional de Vigilancia en Salud Pública (Sivigila) de Colombia, una plataforma que recopila y sistematiza información sobre eventos de interés en salud pública, incluidos los casos de violencia de género. Los datos abarcan el período comprendido entre 2018 y 2023 y contienen variables demográficas, clínicas y contextuales relacionadas con las víctimas, los agresores y los eventos de violencia. Entre las variables clave se encuentran la edad, el género, la etnia, el nivel educativo, el tipo de violencia reportada, la relación entre la víctima y el agresor, y el desenlace del caso (hospitalización, muerte, entre otros).

La violencia de género es un fenómeno multidimensional que afecta desproporcionadamente a las mujeres en Colombia. Según un informe de ONU Mujeres (2020), el 35% de las mujeres en el país ha sufrido algún tipo de violencia física o sexual por parte de su pareja, y el 70% ha experimentado violencia psicológica en algún momento de su vida {cite:ps}`onumujeres2020`. Estos datos resaltan la necesidad de abordar este problema desde una perspectiva integral, utilizando herramientas de análisis de datos para identificar factores de riesgo y diseñar intervenciones efectivas.

El uso de datos de Sivigila para este proyecto es particularmente relevante, ya que este sistema es una de las principales fuentes de información sobre violencia de género en Colombia. Sin embargo, es importante reconocer las limitaciones inherentes a los datos, como la posible subnotificación de casos debido a barreras culturales, sociales o institucionales. Según un estudio de García-Moreno et al. (2015), la subnotificación de la violencia de género es un problema global, con tasas que pueden superar el 50% en algunos contextos {cite:ps}`garcia-moreno2015`. Estas consideraciones deben tenerse en cuenta durante el análisis para evitar conclusiones sesgadas o erróneas.

:::{note}
**Descripción del proyecto:**  
Este proyecto aplica técnicas de Machine Learning para predecir desenlaces graves en casos de violencia de género registrados en Colombia entre 2018 y 2023. Se comparan múltiples algoritmos (árboles, ensambles, SVM, Naive Bayes, etc.) utilizando métricas relevantes como F1-score macro, AUC macro y tiempo de entrenamiento, con el fin de proponer soluciones eficientes para contextos sensibles y de alta prioridad social.
:::


```{bibliography} references.bib
:style: plain
:filter: docname in docnames
```
