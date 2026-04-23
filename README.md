## Identificación de Imagenes Globales y Locales

Este proyecto es una solución de Deep Learning desarrollada en PyTorch para clasificar imagenes icónicos del mundo, incluyendo la integración de la Catedral de Santa Cruz de la Sierra como categoría local.

## 🚀 Resultados Principales
El proyecto se dividió en dos enfoques arquitectónicos:
* **Modelo desde cero (CNN From Scratch):** Arquitectura propia de 3 capas convolucionales que logró superar el umbral con un **~44% de Test Accuracy**.
* **Transfer Learning (ResNet50):** Utilizando extracción de características con pesos preentrenados, el modelo alcanzó un **80% de Test Accuracy**, superando ampliamente la meta del 70%.

## 🛠️ Instrucciones de Ejecución
1. Clonar este repositorio o descargar el archivo .zip.
2. Asegurarse de tener instalado `torch`, `torchvision`, `matplotlib` y `livelossplot` (`pip install -r requirements.txt`).
3. Descargar el dataset original y colocar las carpetas `train` y `test` en la ruta principal. (El dataset no está incluido en este repositorio por cuestiones de peso).
4. Abrir y ejecutar el cuaderno `.ipynb` en Visual Studio Code o Jupyter Notebook.

## 📂 Estructura del Proyecto
* `/models`: Contiene los archivos `.pt` exportados con Torch Script listos para inferencia.
* `proyecto_final.ipynb`: Cuaderno con la Fase 1 a la Fase 4 ejecutadas.
* `README.md`: Este archivo.

### 📍 Enlace a Modelos Exportados:
Puedes encontrar los archivos `.pt` en el siguiente directorio:
👉 [**Descargar modelos (.pt) desde Google Drive**](https://drive.google.com/drive/folders/1IOaTDk3uDCXozpbB2suvR2ZIdylh9Rom?usp=sharing)
