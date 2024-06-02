# Sesgo y varianza

## ¿Como determinamos esta funcionando bien?
Lo bueno de un modelo depende de su prediccion y que tan bien generaliza en un conjutno de datos de prueba 
independientes. Basandonos en diferentes modelos elegimos el que tenga mejor rendimiento

Es importante considrar el tamaño de la muestra, pues puede ser muy pequeña y no representar a la poblacion,
lo puede causar una insuficiente variacion en los datos

## ¿cual es el objetivo de un algorimo de ml?

## Vias and variance for regression
Fpr,miañ deñ errpr redictobñe e orredictobñe
Err(x)
Err x
2
Bias
Varianza
— Bias + Varianza + Errorlrreductibl
Error Reductible
Error
Irreductible
necesito que coloques la formula y expliques las partes

## Error irreductiblñe
Es el error que no se puede reducir, es el error que se obtiene al predecir un valor, es el error que se obtiene

## Bias (Sesgo)
Capacidad de un modelo a ajustarse a los datos de entrenamiento, es la diferencia entre la prediccion y el valor real
* Un modelo de alto sesgo, no es lo sugicientemente complejo para caputar la complejidad de los daots ¿Que significa esto?, y subestima la relacion entre las variables de entrada y salida ¿Que signifca eso?

Esto conlleba a una alta tasa de error en los datos de entrenamiento y en una posibible alta tasa de error en nuevos datos

* ¿Que significa que un modelo no es lo suficientemente complejo para capturar la complejidad de los datos?
* ¿Que significa que un modelo subestime la relacion entre las variables de entrada y salida?
* ¿Que significa que un modelo tenga una alta tasa de error en los datos de entrenamiento?
* ¿Que significa que un modelo tenga una alta tasa de error en nuevos datos?
* ¿Que significa que un modelo tenga un alto sesgo?
* ¿Que significa que un modelo tenga un bajo sesgo?
* ¿Que significa que un modelo tenga un sesgo de 0?

## Varianza
Es la variabilidad de un modelo al ajustarse a diferentes conjuntos de datos de entrenamiento, es la sensibilidad del modelo a los datos de entrenamiento, un modelo de alta varianza es muy sensible a los datos de entrenamiento y no generaliza bien en nuevos datos

esto conlleva a una baja tasa de error en los datos de entrenamiento y una alta tasa de error en nuevos datos

* ¿Que significa que un modelo sea muy sensible a los datos de entrenamiento?
* ¿Que significa que un modelo no generalice bien en nuevos datos?
* ¿Que significa que un modelo tenga una alta tasa de error en nuevos datos?
* ¿Que significa que un modelo tenga una baja tasa de error en los datos de entrenamiento?
* ¿Que significa que un modelo tenga una alta varianza?
* 

## Dilema sesgo-varianza
El objetivo es encontrar un equilibrio entre el sesgo y la varianza, para minimizar el error de prediccion
Porque sino se puede caer en un sobreajuste o un subajuste
* ¿Que es el sobreajuste?
* ¿Que es el subajuste?
* ¿Como se puede encontrar el equilibrio entre sesgo y varianza?

## Underfitting and Overfitting
### Underfitting
Un modelo de alto sesgo y baja varianza, no es lo suficientemente complejo para capturar la complejidad de los datos, subestima la relacion entre las variables de entrada y salida, tiene una alta tasa de error en los datos de entrenamiento y en nuevos datos
¿Cuando ocurre?
* Muy pocos datos de entrenamiento
* Construir un modelo lineal con datos no lineales
Este tipo de modelos son muy simples para capturar patrones complejos en datos como la regresion lineal y logistica

### Overfitting
Un modelo de baja sesgo y alta varianza, es muy sensible a los datos de entrenamiento y no generaliza bien en nuevos datos, tiene una baja tasa de error en los datos de entrenamiento y una alta tasa de error en nuevos datos
¿Cuando ocurre?
* Demasiados datos de entrenamiento
* Conjunto de datos ruidoso
* Son modelos muy complejos que capturan el ruido en los datos

Las predicciones "correctas_" no estan desviadas por un alto sesgo (low bias low variamce) (low bias high variance)
Predicciones "Incorrectas" fuera de lo esperado ( high bias low variance) (high bias high vbariance)
Las predicciones estan en la misma vecindad ya sea para valiores obtenidos correctos eincorrectos (low bias low variance) (high bias high variance) ¿Que significa que esten en la misma vecindad?
Las predicciones poco consistentes, las predicciones son variadas (low bias high variance) (high bias low variance) 

### Equilibrio entre sesgo y varianza
El objetivo es encontrar un equilibrio entre el sesgo y la varianza, para minimizar el error de prediccion

## Maldicion de la dimensionalidad
consiste en que a medida que aumenta la dimensionalidad de los datos, la cantidad de datos necesarios para cubrir el espacio de busqueda crece exponencialmente, lo que puede llevar a un sobreajuste

### Fenomeno hughes phenomenon
Indica que a medida que aumenta el numero de caracteristicas, el rendimiento del clasificador tambien aumenta, hasta que alcanzamos un numero optimo de caracteristicas, despues de ese punto, agregar mas funciones basadas en el mismo tamaño que el conjunto de datos de entrenamiento, degrada el rendimiento del clasificador
Esto se debe a que el clasificador se ajusta al ruido en los datos de entrenamiento
Que significa funciones basadas en el mismo tamaño que el conjunto de datos de entrenamiento
como determinar el numero optimo de caracteristicas

### Solucion a la maldicion de la dimensionalidad
Reducir la dimensionalidad de los datos, mediante tecnicas de seleccion de caracteristicas, extraccion de caracteristicas y reduccion de dimensionalidad
Implica identificar las caracteristicas mas relevantes y eliminar las menos relevantes
* Analisis de componentes principales (PCA)
* Singular Value Decomposition (SVD)
* Representacion de caracteristicas con redes preentrenadas

### Analisis de los datos
Consiste en recopilar organizar e interpretar los datos para descubrir patrones y tendencias
* Comprender el comportamiento del cliente
* Mejorar la eficiencia operativa
* Toma de decision mas inteligente

### Tipos de analisis de datos
#### Analitica descriptiva
Consiste en describir los datos, mediante tecnicas estadisticas y graficas, para resumir las caracteristicas de los datos
* Calcular la media, mediana, moda, desviacion estandar, varianza, percentiles, etc

#### Analitica Exploratorio
Se utiuliza para explorar las relaciones entre las variables.
Incluye tecnica como graficos de dispersion, diagramas de caja, tablas de contingencia y correlacion

#### Analitica predictiva
Se utiliza pronosticar resultados futuros en funcion de datos pasados. 
Identifica riesgos y oportunidades potenciales

#### Analitica prescriptiva
Sugerir soluciones optimas a un problema dado, se usa para identificar el merjor curso de accion y tomar decisiones basdas en las predicciones

#### Analisis causal
Identificar causas fundamentales de un problema

### Modelo de analitica ascende de gardener

1.- Descriptiva: ¿Que ocurrio?
2.- Diagnostica: ¿Por que ocurrio?
3.- Predictiva: ¿Que ocurrira?
4.- Prescriptiva: ¿Como puedo hacer que ocurra?
