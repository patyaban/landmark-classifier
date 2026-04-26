# Clasificación de Landmarks Mediante Redes Neuronales Convolucionales

Este proyecto presenta una solución de aprendizaje profundo (*Deep Learning*) desarrollada en PyTorch para la identificación de puntos de referencia icónicos. El sistema ha sido entrenado para reconocer monumentos globales y categorías locales.

## 🎥 Presentación del Proyecto
* [**▶️ Ver video explicativo en YouTube**][https://youtu.be/ExH1R0zIldQ]

## 🚀 Resultados Principales
El análisis contrasta el rendimiento entre una arquitectura propia y modelos de *Transfer Learning*.

| Modelo | Arquitectura | Épocas | Precisión en Test |
| :--- | :--- | :---: | :---: |
| **Modelo Base** | CNN Propia (3 Capas) | 40 | ~42% |
| **Transfer Learning** | ResNet50 | 15 | **80%** |
| **Transfer Learning** | VGG16 | 10 | 74% |

## 🛠️ Instrucciones de Ejecución
1. Clonar este repositorio.
2. Descargar los archivos pesados (modelos y fotos) desde el enlace de Google Drive proporcionado abajo.
3. Colocar los archivos `.pt` y las imágenes de prueba en la raíz del proyecto o actualizar las rutas en el cuaderno.
4. Asegurarse de tener instaladas las librerías: `torch`, `torchvision`, `matplotlib` y `livelossplot`.
5. Ejecutar el cuaderno principal **`Solucion_P1.ipynb`**.

## 📂 Contenido del Proyecto

### En este Repositorio (GitHub):
* **`Solucion_P1.ipynb`**: Cuaderno maestro con todo el flujo de trabajo, desde el preprocesamiento hasta la evaluación final.
* **`README.md`**: Documentación actual.

### En la Nube (Google Drive):
Debido al tamaño de los archivos, los siguientes recursos se encuentran alojados en una carpeta externa:
* [**📁 Acceder a Modelos y Fotografías de Prueba**](https://drive.google.com/drive/folders/1IOaTDk3uDCXozpbB2suvR2ZIdylh9Rom?usp=sharing)
    * **Archivos `.pt`**: Pesos de los modelos entrenados y parámetros de normalización (`mean_and_std.pt`, `modelo_3capas.pt`, `model_transfer_resnet50.pt`,`helpers.py`, etc.).
    * **Imágenes de Prueba**: Fotografías reales (Uyuni, Santa Cruz, etc.) utilizadas para la validación final.
