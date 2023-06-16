# PRA2-TCVD-JosemiGT

## Introducción

Muy buenas, soy José Miguel Gamarro Tornay, estudiante del máster de Ciencia de datos y voy a presentar la practica 2 de la asignatura de tipología y ciclo de vida de los datos.

Para realizar esta práctica, la cual consiste en un proceso de limpieza de datos y otro proceso de análisis de un data set, he elegido como herramientas para su realización en tipo informe un jupyterlab en el cual se puede ejecutar Python y redactar el documento con markdown, de forma que mientras se van detallando los puntos de limpieza o análisis de datos que se necesitan se muestra simultáneamente el código que lo realiza.

Como data set, he continuado con el propuesto para la práctica, en el que se analiza variables médicas junto a la probabilidad de sufrir un infarto.

## Documento de Jupyterlab

A continuación, presentamos el fichero de jupyerlab, ejecutandose en visual studio code, para elaborar el documento y el código del trabajo.

Se permiten escribir cajas en markdown o cajas de código en python que es ejecutable desde el mismo lugar y muestra en el documento las salidas de la ejecución.

Una vez se finaliza, jupyterlab permite exportar a HTML o PDF.

## Documento en HTML o PDF

Continuamos con el fichero de PDF para mostrar los pasos realizados.

### Descripción del dataset

Inicialmente tenemos una descripción del data set. Donde se comenta el número de variables y qué análisis se prentende hacer.

En nuestro caso, estudiar las diferentes variables médicas y si tienen correlación con una mayor o menor probabilidad de infarto por cada uno de ellas. 

Así, empezamos importando el dataset  con la librería de pandas.

### Integración y selección

En el segundo apartado detallamos las variables que hemos seleccionado como subconjunto de datos respecto al original y de qué tipo son cada una de ellas.

Para mayor comprensión en el código de python, cada nombre de la columna la asigno a una variable con un nombre más descriptivo. Tras ello filtramos el data set por los elementos que nos interesan.