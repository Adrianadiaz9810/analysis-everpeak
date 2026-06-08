# EverPeak Retail Analysis – Sprint 7

Este repositorio contiene el análisis realizado durante el Sprint 7 del caso EverPeak–SilverBasket.

El dataset /datasets/plans.csv /datasets/users_latam.csv /datasets/usage.csv incluye 4,000 datos de usuarios con valores faltantes, sentinels, outliers y problemas de calidad diseñados para simular datos reales del retail. 

## 📂 Contenido del repositorio

 → Notebook principal con limpieza, EDA, distribuciones, outliers y conclusiones.

## ▶ Cómo abrir el notebook en github

Haz clic en el siguiente botón:

[![Open In Colab][(https://github.com/Adrianadiaz9810/analysis-everpeak/blob/main/sprint7-final-project.ipynb)

O:

1. Abre el archivo `.ipynb` en GitHub
2. Haz clic en **Open in Colab**

## 📘 Cómo reproducir el análisis

1. Abre `notebooks/everpeak_analysis.ipynb`
2. Ejecuta las celdas en orden
3. El notebook carga automáticamente el dataset desde `/data/` o desde un enlace público (según corresponda)

## 🧠 Objetivo del análisis

- Identificar problemas de calidad de datos
- Construir un pipeline de limpieza reproducible
- Analizar comportamientos, distribuciones y outliers
- Generar insights para el equipo de Estrategia e Integración de EverPeak
  
#feat: add missingness analysis to notebook.#
 missingness = pd.DataFrame({
    'valores_nulos':   df.isnull().sum(),
