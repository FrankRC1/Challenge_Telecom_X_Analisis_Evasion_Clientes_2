# Telecom X – Predicción de Cancelación de Clientes (Churn)

## 📌 Descripción del Proyecto

Este proyecto forma parte del **Challenge Telecom X – Parte 2** del programa de formación en Data Science.

El objetivo es construir modelos de **Machine Learning** capaces de predecir qué clientes tienen mayor probabilidad de cancelar sus servicios (Churn).

A partir de estos modelos, se busca identificar los factores que más influyen en la cancelación de clientes y proponer estrategias que ayuden a mejorar la retención.

---

# 🎯 Objetivos

* Preparar los datos para el modelado predictivo.
* Transformar variables categóricas mediante técnicas de encoding.
* Analizar la correlación entre variables.
* Entrenar modelos de clasificación para predecir cancelación de clientes.
* Evaluar el rendimiento de los modelos utilizando métricas de Machine Learning.
* Interpretar los resultados para identificar los factores que influyen en el churn.

---

# 🧰 Tecnologías Utilizadas

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-Learn
* Google Colab
* Git & GitHub

---

# 📊 Modelos Utilizados

Se implementaron dos modelos de clasificación:

### Regresión Logística

Modelo lineal utilizado para problemas de clasificación binaria.
Requiere normalización de los datos para mejorar su rendimiento.

### Random Forest

Modelo basado en árboles de decisión que combina múltiples árboles para mejorar la capacidad de predicción.

---

# 📈 Métricas de Evaluación

Para evaluar el rendimiento de los modelos se utilizaron las siguientes métricas:

* Accuracy
* Precision
* Recall
* F1 Score
* Matriz de Confusión

Estas métricas permiten analizar el desempeño del modelo y su capacidad para identificar correctamente clientes que cancelarán el servicio.

---

# 🔎 Principales Factores Asociados al Churn

A partir del análisis del modelo Random Forest se identificaron variables importantes en la predicción de cancelación:

* Tipo de contrato
* Tiempo de permanencia del cliente (tenure)
* Cargos mensuales
* Servicio de internet
* Método de pago

Los clientes con contratos mensuales, menor tiempo de permanencia y cargos mensuales más altos presentan mayor probabilidad de cancelar el servicio.

---

# 💡 Estrategias de Retención

Basado en los resultados del modelo, se sugieren las siguientes estrategias:

* Incentivar contratos de largo plazo mediante descuentos.
* Implementar programas de fidelización para clientes nuevos.
* Revisar los planes con cargos mensuales elevados.
* Promover métodos de pago automáticos para mejorar la permanencia del cliente.

---

# 📂 Estructura del Proyecto

```
Challenge_Telecom_X_Analisis_Evasion_Clientes_2

│
├── Challenge_Telecom_X_Analisis_Evasion_Clientes_2.ipynb
├── TelecomX_df_final.csv
└── README.md
```

---

# 👨‍💻 Autor

**Frank J. Rua Castro**
