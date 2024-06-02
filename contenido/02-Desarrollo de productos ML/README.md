# Desarrollo de productos ML

## Creacion de productos de ml
### Perfiles de desarrolladores:
* Desarrolladores de modelos
* Desarrolladores de implementacion de modelos
* ingenieria de datos
  *  Obtener datos ¿Como?
  *  Curar datos ¿Que es?
  *  Transformar los datos para utilizarlols en entrenamiento de modelos
* Diseño de productos
* Analisis de seguridad
* Etica de IA

## Ciclo de vida de desarrollo de modelos
### Business and data understanding (planning)
* Definir objetivos de negocio
* traductir objetivos de negocio en objetivos de ML ¿ Como puedo hacer esto?
* Recopilar datos
* evaluar viaibilidad del proyecto

#### Se debe analizar
* Dispobilidad de datos: ¿Hay suficientes datos?, ¿Como verifico que hayan suficientes datos?
* Aplicabilidad; ¿La solciuon soluciona el problema o mejora el proceso actual?, ¿Se puede utilizar el ml para resolver el problema?
* Restricciones legales: Seguir la recolccion de datos de forma etica, cual es el impacto de la app en la sociedad
* Robustez y escalabilidad: ¿La solucion es escalable?, ¿La solucion es robusta?
* Disponibilidad de recursos: ¿Se cuenta con los recursos necesarios para el desarrollo del proyecto?, red, humanos profesionales calificados
### Data engineering (data preparation)
#### Data collection and labeling
* Como recopilamos los datos?, ¿que datos usaremos?, internos, de codigo abierto, comprandolos sinteticos?
* Etiquetado de datos
#### data cleaning
* Limpieza de los datos imputando valores faltantes
* Analis de datos mal etiquetados
* Eliminacion de valores atipicos y reduccion de ruido
* Creacion de una canalizacion (pipeline) de datos para automatizar el proceso ¿Que esto y en que consiste?
* REalizar verificaciones de calidad de los datos
#### data processing
* Implica la seleccion de las caracteristicas
* Tratamiento de clases desequilibradas
* Ingenieria de caracteristicas
* Aumento de datos
* Normalizacion y escalado de los datos
#### data management
* Solucion de almacenamiento de datos
* Control de versiones de datos para reproducibilidad
* Almacenamiento de metadatos y creaacion de canalizaciones ETL
### Machine learning model engineering
* Construccion de arquitecturas de modelo mediante una amplia investigacion
* Definicion de metricas del modelo
* entrenamiento y validacion del modelo en el conjunto de datos de entrenamiento y validacion
* Seguimiento de experimentos, cambios de codigo y canalizaciones de aprendizaje automatico
* Interpretar los resultados mediuante la incorporacion de experotos en conocimiento del dominio

#### Versionado y repproducibilidad (explicar en que consisten)
* Hiperparametros
* Experimentos de ml
* arquitectura del modelo
* entorno de desarrollo y metadatos se almacenan
### Evaluating machine learning models
* Pruebas de metricas ¿Cuales metricas sirven?
* Prueba del modelo en un conjunto de datos de prueba
* pruebas con datos aleatorios y mundo real
* pruebas de rendimiento hardware
* toma de deciones de implementacion
### Model eployment
* Integracion del modelo ml en el sistema de sofgtware existente
* Modo de mantencion y prediuccion
* Exponer su funcionalidad preductiuva como tableros interactivo, preduicciones precalculadas
* Envolcer el modlo ml como un componente en una arquitectura de software
### Monitoring and maintence
* Supervision del rendimiento del moodelo y mantenemiento
* Mitiggar el efecto de degradacion del modelo o obsolescencia del modelo
* supervision de los reacursos computacionales

### Machine learnign model deployment
preguntarse si las predicciones se hagan de inmediato o si pueden esperar una hora o un dia
* Por lotes o fuera de linea: En caso de que podamos esperar un poco
Base de datos -> hace un pull del dia anterior y realiza una predccion de trrabajo ->
Los resultados de la prediccion se actualizan en la base de datos y luego se muestran
* Implementacion en linea: En caso que necesitemos lkas predciiones delk molodel lo antes posinle el modelo estara funcionando todo el tiiempo
* Servicio web: En este caso implementamos nuestro modelo como un servicio web y podemos envuiar solicitudes https y obtener predcciuones de eso
En una app pasa por intermediraio de un backend para solicitar la prediccion
* streaming: en el caso que hya un flujo de eventos el modelo escucha los eventos y reacciona ante ellos
la app y un bakcnedn se comunica con todos los consumidores

 
