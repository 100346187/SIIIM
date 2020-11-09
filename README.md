# SIIM-ISIC Melanoma Classification

Este proyecto, que parte de la competición de Kaggle que le da nombre, no tiene otro objetivo que el de ilustrar y demostrar distintos conceptos claves sobre la visión artificial. 

A pesar de no ser su objetivo obtener un buen resultado, se ha logrado sobre los datos de validación un porcentaje de acierto del 94.3% haciendo uso de una EfficientNet preentrenada y un data augmentation moderadamente agresivo.
El resultado habría sido probablemente mejorado con un hardware superior pero todo el trabajo ha sido realizado en Google Colab y haciendo uso de Google Drive como soporte, lo que ha limitado mucho el avance por distintos motivos.
Se puede acceder al mejor modelo obtenido en el archivo model_1_256_2.

En este proyecto se han demostrado las siguientes competencias en lo que a Deep Learning y Computer Vision se refiere:
- Uso de librerías tales como Pandas, Numpy o Pytorch.
- Uso de data augmentation.
- Capacidad para codificar una versión especial de una Resnet (concretamente una XResnet18) desde cero.
- Uso de inicializaciones para la red como la inicialización propuesta por Kaiming et al.
- Uso de políticas de entrenamiento como la política OneCycle.
- Capacidad para elegir correctamente una función de activación para la última capa y una función de error acordes al problema.
- Uso de varios tamaños de imágenes y, por lo tanto, tamaños de lote, para mejorar todo lo posible el desempeño durante el entrenamiento.
- Uso de transfer learning mediante una EfficientNet-b1 preentrenada con ImageNet.
- Combinación de una red convolucional con un percetrón multicapa de forma paralela para poder combinar el análisis de imágenes con el análisis de metadatos.

El desarrollo del proyecto se ha realizado en distintos cuadernos al subido en este repositorio, por lo que las salidas que se muestran en las celdas no tienen por qué corresponder con las obtenidas anteriormente.
