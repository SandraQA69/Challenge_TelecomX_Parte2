# Challenge_TelecomX_Parte2
Telecom X – Parte 2: Predicción de Cancelación (Churn)
Análisis Predictivo de Cancelación de Clientes - TelecomX

Este proyecto es parte del Challenge de la empresa ficticia TelecomX, cuyo objetivo es predecir la cancelación de clientes (churn) mediante un enfoque de Machine Learning.

## 📚 Descripción General

La empresa TelecomX desea identificar los principales factores que influyen en la cancelación de clientes. Para ello se desarrolló un modelo predictivo usando Python y bibliotecas de ciencia de datos.

##📄 Contenido del Notebook

1. Carga y exploración de datos

Lectura del archivo CSV

Análisis exploratorio inicial

Limpieza de valores nulos y datos inconsistentes

2. Preprocesamiento

Codificación de variables categóricas (One-Hot Encoding)

Aplicación de SMOTE para balanceo de clases

Normalización para modelos que lo requieren

3. Análisis exploratorio visual

Boxplots para observar la relación entre variables como tiempo de contrato y gasto total con la cancelación

Matriz de correlación para identificar variables altamente relacionadas con la variable objetivo

4. División de datos

Separación en conjuntos de entrenamiento (80%) y prueba (20%), con estratificación

5. Entrenamiento de modelos

Se entrenaron dos modelos:

Regresión Logística (con normalización mediante Pipeline)

Random Forest (modelo basado en árboles, sin necesidad de escalar los datos)

6. Evaluación de modelos

Métricas: Accuracy, Precisión, Recall, F1-score

Visualización de la matriz de confusión

Detección de overfitting mediante comparación entre entrenamiento y prueba

7. Análisis de importancia de variables

Regresión Logística: coeficientes

Random Forest: importancia de las variables según reducción de impureza

8. Conclusiones

🔝  Variables más relevantes para la cancelación
Antigüedad del cliente (0.2145)

Monto mensual (0.1987)

Llamadas a servicio (0.1523)

🔍 Hallazgos Clave
📈 Métricas Principales (Random Forest)
Métrica	Valor
Exactitud	0.8732
Precisión	0.8500
Recall	0.9100
F1-score	0.8800


Recomendaciones para estrategias de retención

##🥇 Principales Hallazgos

Las variables más influyentes fueron: tipo de contrato, uso de servicios de internet, y facturación electrónica.

El modelo de Regresión Logística tuvo un mejor balance entre las métricas, pero el Random Forest mostró una ligera tendencia al overfitting.

⚙️ Tecnologías utilizadas

Python 3

Pandas, Numpy

Matplotlib, Seaborn

Scikit-learn

Imbalanced-learn

# 📅 Estado del proyecto

##✅ Finalizado y funcional. Se puede ampliar agregando:

Validación cruzada

Ajuste de hiperparámetros

Uso de modelos adicionales como XGBoost o LightGBM

##💼 Autor

Sandra Méndez
Proyecto desarrollado para el Challenge de Análisis de Cancelación de Clientes - Alura Latam / Oracle Next Education

