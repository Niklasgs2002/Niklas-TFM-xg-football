# Niklas-TFM-xg-football
Construcción y análisis de un modelo de Expected Goals (xG) en el fútbol de élite: La Liga, UEFA Champions League y Copa del Mundo FIFA

Trabajo Fin de Máster — Máster en Big Data, Data Science y Business Analytics (UCM)

## Descripción

Este proyecto construye un modelo de Expected Goals (xG) a partir de datos de eventos de
StatsBomb (La Liga, UEFA Champions League y Copa del Mundo FIFA). Además, cruza los resultados
con datos de valoración de mercado de Transfermarkt.

## Estructura del repositorio

- notebooks/ — Notebooks del proyecto en formato .ipynb:
  - 01_EDA.ipynb — Análisis exploratorio de datos
  - 02_preparacion_datos.ipynb — Preparación y transformación de datos
  - 03_modelizacion.ipynb — Modelización (regresión logística, Random Forest, XGBoost)
  - 04_Interpretabilidad.ipynb — Interpretabilidad (SHAP) y cruce con Transfermarkt
  - 05_productivización.ipynb — Función de productivización del modelo
- models/ — Modelo final entrenado (regresión logística), serializado con pickle

## Fuentes de datos

- StatsBomb Open Data — https://github.com/statsbomb/open-data
- Transfermarkt Datasets (Kaggle) — https://www.kaggle.com/datasets/davidcariboo/player-scores

Niklas Garcia Schulz
