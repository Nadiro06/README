##Trabajo Final - Programación 2025-1

Este repositorio contiene el desarrollo completo del proyecto final de la asignatura **Programación 2025-1**, cuyo objetivo es aplicar técnicas de ciencia de datos para resolver un problema de clasificación utilizando aprendizaje automático.

##Objetivo del proyecto

Desarrollar una solución predictiva para un problema de clasificación, siguiendo todas las etapas del flujo de trabajo de ciencia de datos: exploración, limpieza, modelado y comparación de modelos.

##Estructura del repositorio

- `01 - exploración.ipynb`: Carga inicial del dataset y análisis exploratorio de variables numéricas y categóricas. Visualización de relaciones y detección de datos faltantes o anómalos.
- `02 - preprocesado.ipynb`: Limpieza e imputación de datos faltantes, codificación de variables categóricas y escalado de características numéricas.
- `03 - modelo 1.ipynb`: Implementación del primer modelo (Random Forest), ajuste de hiperparámetros con GridSearchCV, curvas de aprendizaje y evaluación con métricas estándar.
- `04 - modelo 2.ipynb`: Implementación del segundo modelo (Gradient Boosting), ajuste con RandomizedSearchCV y evaluación con métricas y curvas de aprendizaje.
- `05 - comparación.ipynb`: Comparación de ambos modelos mediante métricas de desempeño y análisis de concordancia.
- `06 - dataset.csv`: Archivo con los datos utilizados para entrenar y evaluar los modelos.
- `07 - informe.pdf`: Documento resumen de toda la estrategia, resultados y conclusiones del proyecto.


##Tecnologías utilizadas

- Python 3.x
- Jupyter Notebook
- Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn
- XGBoost / LightGBM (según el modelo 2)
- GridSearchCV, RandomizedSearchCV

##Resultados

Ambos modelos alcanzaron una precisión superior al 85%, con buen balance entre precisión y recall. El modelo basado en Random Forest presentó una mejor generalización, mientras que el modelo de boosting mostró mayor sensibilidad al ajuste de hiperparámetros.


##Conclusiones

El proyecto permitió aplicar de forma integral el flujo de trabajo de un problema de clasificación. Se concluyó que la calidad del preprocesamiento y la selección de hiperparámetros tienen un impacto crítico en el rendimiento de los modelos. La comparación entre modelos permitió identificar fortalezas y debilidades de cada enfoque.

##Autores

- Natalia Díaz Villamil
- Sarha Cifuentes Montoya


