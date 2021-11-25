---
title: "Detección de COVID-19 en imágenes de rayos X mediante el uso de Redes Neuronales de Convolución"
date: 2021-11-25T20:46:39+01:00
draft: false
---

## Autores:

* __Sherlyn Ballestero Cruz__

* __Rolando Sánchez Ramos__

## Resumen
El objetivo principal de este trabajo es investigar y comparar varias técnicas de Deep Learning aplicadas a imágenes de rayos X de tórax sobre tres clases (pacientes infectados con COVID-19, pacientes con neumonı́a y pacientes sanos) para la clasificación de las mismas de acuerdo al tipo que representen. En este proceso se utilizaron Redes Neuronales de Convolución, las cuales posibilitan la creación de manera eficiente de modelos de aprendizaje automático supervisado orientados a tareas de clasificación a partir de una serie de imágenes previamente etiquetadas. Especı́ficamente se utilizaron los modelos de redes preentrenadas DenseNet201, EfficientNetB7 y MobileNet, como parte de la técnica de Transfer Learning, las cuales fueron ejecutadas a partir de las implementaciones que ofrece la API de Keras para el lenguaje Python. Finalmente, se mezclaron los tres modelos mencionados mediante el uso de Ensemble Learning como método para mejorar la precisión final. 