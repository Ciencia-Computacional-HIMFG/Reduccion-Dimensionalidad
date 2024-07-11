# **Análisis de Componentes Principales (PCA)**

Un Análisis de Componentes Principales, es una **técnica de reducción de dimensionalidad líneal**. Toma datos de un espacio de alta dimensionalidad y los representa en un espacio de menor dimensionalidad. Busca preservar las partes importantes de la información, aquellas con mayor variación y elimina aquellas con poca variación (no esenciales). Un PCA, es una técnica no supervisada, es decir, los agrupamientos son por la naturaleza de los datos y no por la categoria de una etiqueta dada por nostros. 

Un PCA permite explorar grandes cantidades de datos y mostrarnos cuales son las carácteristicas más importantes de ellos. La representación se hace a través de los componentes principales. Un componente es la forma en que se retiene la mayor información posible de una dimensión. Los componentes principales tiene dirección y magnitud:

+ Dirección: representa el eje sobre el cual se distribuyen los datos preferentemente con base en su mayor variación.
+ Magnitud: cantidad de variación capturada de los datos por el componente principal durante su proyección por el eje. 

Los componentes principales son un vector y siempre el primer componente abarca la mayor cantidad de variación de los datos. Cada componenete representa un conjunto de características correlacionadas que aportan un porcetantaje de la variación total de los datos. Así, se reduce el número de dimensiones para un conjunto de datos dado.

---
**Nota**: aquí puedes visualizar correctamente el ejemplo de [PCA en lenguaje R](http://htmlpreview.github.io/?https://github.com/Ciencia-Computacional-HIMFG/Reduccion-Dimensionalidad/blob/main/pca/r_pca.nb.html).

