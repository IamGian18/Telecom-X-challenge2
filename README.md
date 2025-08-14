# Predicción de Cancelación de Clientes

Este proyecto tiene como objetivo predecir la cancelación (churn) de clientes utilizando modelos de **Machine Learning** en Python, comparando el rendimiento entre **KNN** y **Árbol de Decisión**.

#📌 Descripción
Se realizó un análisis de datos para identificar los factores que influyen en la cancelación de clientes.  
Los modelos entrenados permiten detectar patrones y ayudar a implementar estrategias de retención.

Modelos evaluados:
- **KNN (K-Nearest Neighbors)**
- **Árbol de Decisión (Decision Tree)**

#📊 Conclusiones Principales
- El **Árbol de Decisión** presentó mejor rendimiento que KNN.
- Variables más relevantes:
  1. Tenure (duración de la relación con el cliente)
  2. Tipo de plan contratado
  3. Cargos mensuales
  4. Uso de servicios adicionales
- Factores que incrementan el riesgo de cancelación:
  1. Alta sensibilidad al precio.
  2. Baja fidelización en clientes nuevos.
  3. Poca adopción de servicios adicionales.

#🚀 Estrategias de Retención Recomendadas
1. Ofrecer promociones a clientes nuevos.
2. Crear programas de fidelización.
3. Detectar clientes insatisfechos con encuestas tempranas.
4. Ajustar precios en clientes con cargos mensuales altos.
