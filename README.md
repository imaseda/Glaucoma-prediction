# Glaucoma-prediction

## Descripción

Clasificador neuronal para la detección de Glaucoma. Encontramos diferentes modelos basados en EfficientNet B0, preentrenado con los pesos de ImageNet, ofreciendo distintas opciones al sustituir su capa de clasificación, con el conjunto de imágenes original y añadiendo imagenes basadas en las originales (aumentando, rotando, descentrando...) mediante la función ImageDataGenerator().
También podemos encontrar un modelo sin Transfer Learning, con una red neuronal propia.
Disponemos de 10 particiones de datos sobre las que se aplicará una técnica de cross validation intentando reducir los sesgos y variaciones estadísticas en función de cómo se ha realizado la partición. 
  
En el archivo **pdf/PRAC_1_Ivan_Maseda_Zurdo.pdf** encontramos una explicación más detallada del proceso y los distintos modelos.
  
Se emplea la librería keras con Tensorflow para la implementación de los distintos modelos.

Esta práctica se ha realizado bajo el contexto de la asignatura _Deep learning_, perteneciente al Máster en Ciencia de Datos de la Universitat Oberta de Catalunya.

## Autor

La actividad ha sido realizada por **Iván Maseda Zurdo**.

## Ficheros del código fuente

En la carpeta **src/** encontramos los distintos modelos creados.
  
## Nota

Los resultados de los modelos entrenados no han sido añadidos al repositorío por limitación de almacenamiento.
  
En el archivo **pdf/PRAC_1_Ivan_Maseda_Zurdo.pdf** encontramos una explicación más detallada del proceso en los diferentes modelos.
