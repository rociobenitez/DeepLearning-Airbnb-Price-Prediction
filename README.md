# Predicción de Precios de Airbnb con Deep Learning 🏘️

## Descripción del Proyecto

Este proyecto tiene como objetivo predecir el precio de habitaciones de Airbnb utilizando un enfoque de Deep Learning. Se hará uso de un conjunto de datos que incluye características variadas como datos numéricos, texto e imágenes. El propósito es combinar estos diferentes tipos de datos mediante el **uso de modelos de redes neuronales, incluyendo redes neuronales convolucionales (CNN) para imágenes y modelos para datos 1D,** culminando en un modelo híbrido que integre ambas fuentes de información.

## Objetivos

- Desarrollar un modelo basado en imágenes para predecir precios de habitaciones.
- Crear un modelo que maneje datos 1D (numéricos y de texto) para la misma tarea de predicción.
- Implementar un modelo híbrido que combine ambas fuentes de datos para mejorar la precisión de las predicciones.

## Dataset

El [dataset](https://public.opendatasoft.com/explore/dataset/airbnb-listings/table/) utilizado ha sido extraído de Airbnb mediante técnicas de scraping y ha sido preseleccionado para contener 14780 registros, optimizando así el tiempo de ejecución y evitando problemas de memoria.

## Herramientas y Tecnologías

- [Python](https://www.python.org/)
- [TensorFlow](https://www.tensorflow.org/)/[Keras](https://keras.io/)
- [Redes Neuronales Convolucionales (CNN)](https://es.wikipedia.org/wiki/Red_neuronal_convolucional)
- Procesamiento y aumento de imágenes

## Estructura del Proyecto

- `cuadernos/`: Contiene todos los Jupyter Notebooks (.ipynb) utilizados para el preprocesamiento de datos, modelado y evaluación.
- `data/`: Incluye los datasets originales y cualquier conjunto de datos derivado, como los filtrados y escalados. con una subcarpeta `train_test_split/` que almacena archivos de entrenamiento, validación y prueba separados para etiquetas y características.
- `docs/`: Archivos con aclaraciones y explicaciones.

## Cómo Empezar

- [Guía de uso](/docs/guia_de_uso.md)
- [Detalles del proyecto](/docs/detalles_del_proyecto.md)