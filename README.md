# Glaucoma-prediction

## Descripción

Clasificador neuronal para la detección de Glaucoma. encontramos diferentes modelos basados en EfficientNet B0, preentrenado con los pesos de ImageNet, ofreciendo distintas opciones al sustituir su capa de clasificación.
También podemos encontrar un modelo sin Transfer Learning, con una red neuronal propia.
Disponemos de 10 particiones de datos sobre las que se aplicará una técnica de cross validation intentando reducir los sesgos y variaciones estadísticas en función de cómo se ha realizado la partición.
En el archivo **pdf/PRAC_1_Ivan_Maseda_Zurdo.pdf** encontramos una explicación más detallada del proceso y los distintos modelos.

Esta práctica se ha realizado bajo el contexto de la asignatura _Visualización de datos_, perteneciente al Máster en Ciencia de Datos de la Universitat Oberta de Catalunya.

## Autor

La actividad ha sido realizada por **Iván Maseda Zurdo**.

## Fichero del código fuente

**src/PEC3_Ivan_Maseda.Rmd**: este fichero contiene el código en lenguaje R para la carga de los datasets original, la carga de librerías, genera los graficos requeridos.
