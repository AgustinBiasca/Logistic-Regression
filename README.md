# Clasificación, Riesgo y Predicción de Mercados (Machine Learning) 

Este repositorio contiene varios estudios de caso enfocados en modelos de **clasificación** y **Análisis Discriminante**, herramientas fundamentales para la predicción de riesgo y variables binarias. Los proyectos demuestran la aplicación de diversos algoritmos y la **evaluación crítica** de los resultados.

## Proyectos Destacados y Conclusiones Clave

- **Análisis de Riesgo Crediticio (Regresión Logística - Teórico):**
    - **Objetivo:** Simulación de 10,000 datos para predecir el *default* de clientes (basado en ingreso, balance, estudiante (si o no)).
    - **Análisis Crítico:** Aunque el modelo arrojó una precisión del **90%**, el proyecto concluye que este resultado es **falso e inpráctico**, argumentando las limitaciones del *dataset* simulado, el potencial de *overfitting* y problemas a la hora de evaluar un modelo como el *Data Leaked*.
    - **Archivos:** [`Riesgo_crediticio.ipynb`](./Riesgo_crediticio.ipynb)

- **Predicción de la Dirección del Mercado (Análisis Comparativo):**
    - **Objetivo:** Predecir la dirección del mercado (Up/Down) usando datos históricos (2001 - 2005), comparando la eficacia de varios clasificadores.
    - **Resultados Clave (Accuracy):**
        - **QDA (Análisis Discriminante Cuadrático):** El clasificador más efectivo, alcanzando una **tasa de acierto del 60%**.
        - **Naive Bayes (NB):** Muy efectivo y rápido, con un acierto del **59%**.
        - **Regresión Logística (GLM Binomial) / LDA:** Ambos resultaron en una precisión del **56%**.
        - **K-Nearest Neighbors (KNN):** El menos efectivo, con una tasa máxima de **53%** (Con K=3).
    - **Archivos:** [`The_Stock_Market_Binomial_.ipynb`](./The_Stock_Market_Binomial_.ipynb), [`LDA_SMARKET.ipynb`](./LDA_SMARKET.ipynb), [`QDA_SMARKETipynb.ipynb`](./QDA_SMARKETipynb.ipynb), [`NB_SMARKET.ipynb`](./NB_SMARKET.ipynb), [`K_Nearste_Neighbors_SMARKET.ipynb`](./K_Nearste_Neighbors_SMARKET.ipynb)

***

## Conclusión sobre Habilidades

Estos modelos buscan mostrar las distintas aplicación y resultados que arrojan los distintos clasificadores (`Regresion Logística`, `QDA`, `LDA`, `NB`, `KNN`). Además, el proyecto de riesgo crediticio resalta la importancia del **análisis crítico**, de los supuestos del modelo, fundamental en el análisis de riesgos. No caer en posibles errores de perdida de datos.
