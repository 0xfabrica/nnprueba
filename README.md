# Clasificación de imágenes CIFAR-10 con CNN

Este proyecto implementa dos Redes Neuronales Convolucionales (CNN) para clasificar imágenes del dataset CIFAR-10:

* **TensorFlow/Keras:** Usa `ImageDataGenerator` para el aumento de datos y Dropout para la regularización. Guarda el modelo en formato SavedModel.
* **PyTorch:** Implementa una CNN con capas convolucionales, pooling y capas totalmente conectadas. Guarda el modelo en formato .pth.

## Requisitos

* Python 3.x
* TensorFlow 
* Keras
* PyTorch
* Torchvision
* Matplotlib (opcional)

## Instrucciones

1. Clona este repositorio.
2. Instala las dependencias necesarias usando `pip install -r requirements.txt` (crea un archivo requirements.txt con las bibliotecas necesarias).
3. Ejecuta el notebook de Colab para entrenar y evaluar los modelos.
4. Los modelos entrenados se guardarán en:
    * TensorFlow/Keras: `/content/mymodel.keras`
    * PyTorch: `/content/mymodelavanzedobjetc_pytorch.pth`

## Resultados

* **TensorFlow/Keras:** Precisión en el conjunto de prueba: 57%
* **PyTorch:** Precisión en el conjunto de prueba: 74%

## Comentarios y sugerencias

Este proyecto es un trabajo en progreso y se agradece cualquier comentario o sugerencia para mejorarlo. No dudes en abrir un issue o enviar un pull request si tienes alguna idea o encuentras algún error.

## Próximos pasos

* Explorar diferentes hiperparámetros para mejorar el rendimiento.
* Añadir visualizaciones de las predicciones y las características aprendidas.
* Implementar otras arquitecturas de CNN.
