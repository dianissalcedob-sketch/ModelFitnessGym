# ModelFitnessGym
# 🏋️‍♀️ Predicción de Cancelación de Clientes – Model Fitness

## 📌 Descripción del proyecto

Este proyecto analiza el comportamiento de clientes de una cadena de gimnasios con el objetivo de identificar factores que influyen en la cancelación (churn) y predecir la probabilidad de abandono.

A través del análisis de datos y modelos de machine learning, se busca apoyar la toma de decisiones estratégicas para mejorar la retención de clientes.

---

## 🎯 Objetivos

* Analizar el comportamiento de clientes y detectar patrones asociados a la cancelación.
* Construir un modelo predictivo para estimar la probabilidad de churn.
* Segmentar a los clientes en grupos para entender perfiles de riesgo.
* Proponer recomendaciones para mejorar la retención.

---

## 📂 Datos

El dataset incluye información sobre:

* Datos demográficos (edad, género)
* Comportamiento del cliente (frecuencia de visitas, consumo de servicios)
* Información del contrato (duración, tiempo restante)
* Variables de interacción (visitas grupales, promociones)
* Variable objetivo: **Churn** (cancelación)

---

## ⚙️ Metodología

### 🔍 Análisis exploratorio (EDA)

* Revisión de datos, valores faltantes y estadísticas descriptivas
* Comparación entre clientes que cancelan y los que permanecen
* Visualización de distribuciones y patrones
* Análisis de correlaciones

### 🤖 Modelos de predicción

Se entrenaron dos modelos de clasificación:

* Regresión logística
* Random Forest

Se evaluaron utilizando:

* Accuracy
* Precision
* Recall

### 👥 Segmentación de clientes

* Estandarización de datos
* Clustering con K-means
* Identificación de perfiles de clientes y análisis de tasas de cancelación

---

## 📊 Resultados clave

* Los clientes con menor frecuencia de visitas tienen mayor probabilidad de cancelación.
* Los contratos de mayor duración están asociados con mayor retención.
* Los clientes con mayor gasto en servicios adicionales tienden a ser más leales.
* Se identificaron segmentos de clientes con alto riesgo de churn.
  
---  

💡 Recomendaciones
Implementar estrategias de retención para clientes con baja frecuencia de visitas.
Incentivar contratos de largo plazo.
Promover servicios adicionales para aumentar el engagement.
Diseñar campañas específicas para segmentos con alto riesgo de abandono.

---
🛠️ Tecnologías utilizadas
Python
Pandas
NumPy
Matplotlib
Scikit-learn
🚀 Conclusión

El uso de análisis de datos y modelos predictivos permite identificar clientes en riesgo de cancelación y tomar acciones proactivas para mejorar la retención, generando valor estratégico para el negocio.

