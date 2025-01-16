---
date: 2024-08-01
---
# Análisis de Sentimientos para Reseñas de Películas en IMDB 

## Aprendizaje Automático para Textos

## Descripción del Proyecto

En este sprint se trabajó en la implementación y evaluación de modelos avanzados de clasificación de textos, específicamente para clasificar reseñas de películas en IMDB. Se utilizaron técnicas de procesamiento de texto y modelos como LightGBM, Random Forest, Logistic Regression, y un Voting Classifier. El enfoque estuvo en optimizar la precisión y la generalización del modelo, utilizando herramientas como spaCy, TF-IDF y BERT para la generación de embeddings.

## Objetivo
El objetivo de este proyecto fue desarrollar y evaluar modelos avanzados de clasificación de texto, buscando mejorar la capacidad de clasificación de reseñas con un enfoque en la precisión y capacidad de generalización. Se apuntó a alcanzar un F1 Score superior a 0.85 en el conjunto de prueba.

## Etapas del Proyecto
- **Preprocesamiento de Datos**: Normalización y limpieza de las reseñas utilizando spaCy y TF-IDF para la preparación del texto.
- **Entrenamiento de Modelos**: Se entrenaron modelos individuales como LightGBM, Random Forest y Logistic Regression.
- **Ensamblaje de Modelos**: Implementación de un Voting Classifier para combinar las predicciones de los modelos individuales y mejorar la precisión general.
- **Uso de Embeddings de BERT**: Generación de embeddings para los textos utilizando BERT, seguido del entrenamiento de un modelo de regresión logística sobre estos embeddings.
- **Evaluación**: Los modelos se evaluaron utilizando métricas como Exactitud, F1 Score, APS y ROC AUC para determinar su rendimiento.

## Herramientas Tecnológicas Implementadas
- **LightGBM**: Utilizado para capturar relaciones complejas y no lineales en los datos.
- **Random Forest Classifier**: Elegido por su robustez frente al sobreajuste y su eficacia en datos con muchas características.
- **Logistic Regression**: Aplicado por su simplicidad y efectividad en capturar relaciones lineales.
- **Voting Classifier**: Combinación de modelos para optimizar el rendimiento general.
- **spaCy**: Empleado para el procesamiento y normalización de texto.
- **TF-IDF**: Utilizado para la vectorización del texto.
- **BERT**: Implementado para generar embeddings de texto que mejoran la representación de los datos.


![Análisis de Sentimientos](/Proyectos/assets/cover_S4_analisis_sentimientos.png)

## Habilidades en Ciencia de Datos Desarrolladas
- **Implementación de Modelos Avanzados**: Experiencia en la aplicación de técnicas avanzadas como Voting Classifier y BERT en problemas de clasificación de textos.
- **Evaluación de Modelos**: Competencia en el uso de métricas avanzadas para evaluar y mejorar el rendimiento de los modelos.
- **Optimización de Modelos**: Habilidad en el ajuste y combinación de diferentes modelos para maximizar el rendimiento.

