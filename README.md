# Predicción de abandono de clientes (Churn)

## 📊 Descripción
Se utiliza el dataset público de Kaggle: "bank-customer-churn", el cual contiene información de clientes bancarios.

## 🎯 Objetivo
Predecir qué clientes tienen mayor probabilidad de abandonar el banco.

## 🤖 Modelos utilizados
- Regresión Logística
- Random Forest

## 📈 Resultados

- Random Forest mejora significativamente el **recall**
- Reduce considerablemente los falsos negativos
- Permite identificar más clientes en riesgo

## 🧠 Conclusiones

El modelo Random Forest mejora la detección de clientes que abandonan, lo cual es crítico en problemas de churn.  
Aunque aumenta el número de falsos positivos, este trade-off es aceptable desde una perspectiva de negocio.

## 🛠️ Tecnologías
- Python
- Scikit-learn
- Pandas
- Numpy