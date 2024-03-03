# Guía de Uso del Repositorio de Modelado Predictivo con Deep Learning

Este repositorio contiene todos los cuadernos de Jupyter y archivos necesarios para implementar y evaluar modelos predictivos de precios de alojamientos utilizando técnicas de Deep Learning. Todo el trabajo se ha realizado en Google Colab y se ha estructurado para un acceso y una replicación fáciles.

## Estructura del Repositorio

- `cuadernos/`: Contiene todos los Jupyter Notebooks (.ipynb) utilizados para el preprocesamiento de datos, modelado y evaluación.
- `data/`: Incluye los datasets originales y cualquier conjunto de datos derivado, como los filtrados y escalados.
- `train_test_split/`: Subcarpeta que almacena archivos de entrenamiento, validación y prueba separados para etiquetas y características.
- `docs/`: Archivos con aclaraciones y explicaciones.

## Configuración Inicial

1. **Clonar el Repositorio**: Para comenzar, clona este repositorio en tu entorno local o en tu espacio de trabajo de Google Colab.

2. **Google Drive**: Si trabajas desde Google Colab, asegúrate de montar tu Google Drive para acceder a la carpeta `deep_learning` donde se almacenan los datos y los cuadernos.

   ```python
   from google.colab import drive
   drive.mount('/content/drive')
   ```

3. **Instalación de Dependencias**: Instala todas las dependencias necesarias para ejecutar los cuadernos. Generalmente, esto se puede hacer directamente en Colab sin necesidad de pasos adicionales, ya que las librerías de Deep Learning como TensorFlow ya están preinstaladas.

## Uso de los Cuadernos

1. **Preprocesamiento de Datos**: Comienza con el cuaderno `1_preprocesado_datos.ipynb`. Aquí se realiza la descarga del dataset, el preprocesamiento inicial, la exploración de datos y la preparación de los conjuntos de entrenamiento, validación y prueba.

2. **Modelado**: Continúa con el cuaderno `2_modelado.ipynb`. Este archivo contiene el proceso de creación y entrenamiento de los modelos de Machine Learning y Deep Learning para datos tabulares e imágenes.

3. **Evaluación**: Evalúa los modelos utilizando los conjuntos de test que se guardaron previamente en la carpeta `train_test_split/`. Los cuadernos incluyen códigos para calcular métricas y visualizar el rendimiento del modelo.

## Realizar Predicciones

Para hacer nuevas predicciones, sigue los pasos proporcionados en los cuadernos que detallan la carga de modelos entrenados y la aplicación de estos a nuevos datos para generar estimaciones de precios.

## Contribuir al Repositorio

Si deseas contribuir al proyecto, considera seguir las prácticas estándar de GitHub para la contribución, que incluyen la creación de forks, la presentación de pull requests y la utilización de issues para discusiones.