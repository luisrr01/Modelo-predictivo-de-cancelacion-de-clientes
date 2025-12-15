# 📡 Predicción de Cancelación de Clientes (Churn) en Telecomunicaciones

## 📌 Contexto
Este proyecto desarrolla un modelo predictivo para identificar clientes con alta probabilidad de cancelar los servicios de la empresa de telecomunicaciones **Interconnect**. La cancelación de clientes representa un impacto directo en los ingresos, por lo que anticipar este comportamiento permite diseñar estrategias de retención más efectivas.

El análisis se realizó integrando múltiples fuentes de datos relacionadas con contratos, información personal y servicios de internet y telefonía.

---

## 🧠 Enfoque Analítico
Se construyó un pipeline de análisis de datos que incluyó limpieza, integración de múltiples fuentes y modelado predictivo. El objetivo fue identificar patrones de comportamiento asociados al churn y evaluar distintos modelos de clasificación para seleccionar el más adecuado según métricas de desempeño.

---

## 🛠️ Herramientas y Técnicas
- Lenguaje: Python  
- Manipulación de datos: Pandas, NumPy  
- Visualización: Matplotlib, Seaborn  
- Preprocesamiento:
  - Limpieza y unificación de múltiples datasets  
  - Codificación de variables categóricas  
  - Escalado de variables  
- Modelos evaluados:
  - Logistic Regression  
  - Random Forest  
  - Gradient Boosting  
- Optimización:
  - Ajuste de hiperparámetros  
- Métricas de evaluación:
  - AUC-ROC  
  - Accuracy  

---

## 📊 Resultados
- El modelo final seleccionado fue **Gradient Boosting**, optimizado mediante ajuste de hiperparámetros.  
- Desempeño del modelo:
  - **AUC-ROC: 0.8695**  
  - **Accuracy: 82.11%**  
- Se identificó que los clientes con contratos mensuales, pagos manuales y sin servicios adicionales presentan mayor probabilidad de cancelar.

---

## 🚀 Aplicación al Negocio
El modelo permite:
- Identificar de forma anticipada a clientes con alto riesgo de cancelación.  
- Apoyar estrategias de retención mediante ofertas personalizadas, descuentos o mejoras de servicio.  
- Priorizar acciones comerciales basadas en datos para reducir el churn.  

---

## 📚 Aprendizajes Clave
- Integración de múltiples fuentes de datos en un proyecto de Data Science.  
- Importancia de la selección de métricas adecuadas para problemas de clasificación.  
- Evaluación comparativa de modelos de Machine Learning.  
- Interpretación de resultados para generar recomendaciones de negocio accionables.
