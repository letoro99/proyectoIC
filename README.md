# Proyect de segmentación del miocardio en resonancias magnéticas.

## Integrantes
- Samuel Clavel
- Álvaro Toro

## Librerias y achivos necesarias
Es necesario tener instalados los siguientes software:
- TensorFlow
- Matplotlib
- Numpy
- Pandas
- Datos : https://drive.google.com/drive/folders/1bxyZUNWbmqKhJPV37dP4M-2V-IgQGvJF?usp=sharing (descargar toda la carpeta llamada MIOCARDIO)

## ¿Cómo correr el proyecto?
Se puede correr el modelo con el entrenamiento, testing y validación con el archivo proyecto.ipynb. El arhivo .py contienen el mismo codigo que el arhivo .ipynb. Para cargar los archivos de la base de datos de entrenamiento, testing y validación tienen dos opciones:

### Opcion 1: Google Drive
Es necesario subir la carpeta MIOCARDIO a la carpeta raiz de su drive para poder cargar los archivos sin tener que editar el código. Si sube los archivos en otra dirección es necesario cambiar el string dado en las funciones de np.load() a la dirección donde ubico los archivos .npy

### Opción 2: Colab
Si usa esta opción, debe cambiar el valor de option a uno distinto de 1. Además debe subir la carpeta MIOCARDIO a al directorio temporal otorgado por Colab.

Con cualquiera de las dos opciones, se debe correr todas las celdas en el orden dado.
