# Predicción de Precios de Airbnb con Deep Learning

## Descripción del Proyecto

Este proyecto tiene como objetivo predecir el precio de habitaciones de Airbnb utilizando un enfoque de Deep Learning. Se hará uso de un conjunto de datos que incluye características variadas como datos numéricos, texto e imágenes. El propósito es combinar estos diferentes tipos de datos mediante el uso de modelos de redes neuronales, incluyendo redes neuronales convolucionales (CNN) para imágenes y modelos para datos 1D, culminando en un modelo híbrido que integre ambas fuentes de información.

## Objetivos

- Desarrollar un modelo basado en imágenes para predecir precios de habitaciones.
- Crear un modelo que maneje datos 1D (numéricos y de texto) para la misma tarea de predicción.
- Implementar un modelo híbrido que combine ambas fuentes de datos para mejorar la precisión de las predicciones.

## Dataset

El dataset utilizado ha sido extraído de Airbnb mediante técnicas de scraping y ha sido preseleccionado para contener 14780 registros, optimizando así el tiempo de ejecución y evitando problemas de memoria.

## Herramientas y Tecnologías

- Python
- TensorFlow/Keras
- Redes Neuronales Convolucionales (CNN)
- Procesamiento y aumento de imágenes

## Estructura del Proyecto

- `data/`: Directorio que contiene el dataset utilizado.
- `notebooks/`: Jupyter Notebooks con el análisis exploratorio, la preparación de los datos, y los experimentos de modelado.
- `src/`: Código fuente con funciones de ayuda, entrenamiento de modelos, y evaluación.
- `models/`: Modelos entrenados y sus pesos para futuras evaluaciones o mejoras.
- `README.md`: Documentación sobre el proyecto, incluyendo cómo ejecutar los scripts, una descripción de los archivos, y cómo contribuir.

## Cómo Empezar

Instrucciones sobre cómo configurar el entorno, instalar dependencias, y correr los scripts de entrenamiento.