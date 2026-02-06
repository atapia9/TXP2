# TelecomX – Análisis y Modelado Predictivo de Churn

## Descripción del Proyecto
Este proyecto tiene como objetivo analizar el comportamiento de los clientes de **TelecomX** y desarrollar un **modelo predictivo de churn (cancelación de clientes)** que permita identificar patrones de riesgo y apoyar la toma de decisiones estratégicas orientadas a la retención.

El trabajo integra análisis exploratorio de datos, preparación de variables, entrenamiento de modelos de clasificación y evaluación comparativa de su desempeño, manteniendo un enfoque equilibrado entre **rigor técnico** e **interpretabilidad para negocio**.

---

## Objetivo Principal
Construir y evaluar modelos de machine learning capaces de **predecir la probabilidad de churn**, proporcionando información accionable para:
- Reducir la pérdida de clientes.
- Priorizar acciones de retención.
- Identificar segmentos de mayor riesgo.

---

## Enfoque Analítico
El proyecto sigue una metodología estructurada de análisis de datos:

1. **Comprensión del problema de negocio**
2. **Análisis Exploratorio de Datos (EDA)**
3. **Preparación y transformación de datos**
4. **Modelado predictivo**
5. **Evaluación e interpretación de resultados**
6. **Conclusiones y recomendaciones estratégicas**

Este enfoque asegura trazabilidad entre los datos, los modelos y las decisiones de negocio.

---

## Modelos Implementados
Se entrenaron y compararon modelos de clasificación con énfasis en interpretabilidad y desempeño:

- **Regresión Logística**
- **Modelo de clasificación alternativo (comparativo)**

La selección prioriza modelos comprensibles para stakeholders, adecuados para problemas de churn donde la explicación de variables es clave.

---

## Métricas de Evaluación
Los modelos fueron evaluados utilizando métricas estándar de clasificación:

- Accuracy
- Precision
- Recall
- F1-score
- Classification Report

Estas métricas permiten evaluar no solo la precisión general, sino también el equilibrio entre errores de clasificación relevantes para el negocio.

---

## Principales Hallazgos
- Ambos modelos presentan desempeños comparables en términos de accuracy.
- La Regresión Logística destaca por su **interpretabilidad**, lo que la hace especialmente valiosa para análisis de churn.
- Existen variables con influencia significativa en la probabilidad de cancelación, útiles para diseñar estrategias de retención focalizadas.

---

## Implicaciones para el Negocio
- El modelo permite **identificar clientes con alto riesgo de churn** antes de que abandonen el servicio.
- Facilita la **priorización de campañas de retención** basadas en datos.
- Apoya decisiones estratégicas al balancear desempeño predictivo e interpretabilidad.

---

## Tecnologías Utilizadas
- Python
- Pandas
- NumPy
- Matplotlib / Seaborn
- Scikit-learn
- Jupyter Notebook

---

## Estructura del Proyecto

├── JATG_telecomx_P2.ipynb # Notebook principal del análisis

├── README.md # Documentación del proyecto

└── data/telecomx_clean.csv

---

## Próximos Pasos (Mejoras Potenciales)
- Ajuste de hiperparámetros.
- Evaluación con métricas orientadas a costos de churn.
- Análisis por segmentos de clientes.
- Integración del modelo en un flujo de decisión empresarial.

---

## Autor
Proyecto desarrollado con fines académicos y analíticos, aplicando buenas prácticas de ciencia de datos, análisis de negocio y modelado predictivo.

Por Jesus Armando Tapia Gallegos MTDE

---

## Licencia
Uso académico y educativo.
