# 📉 Análisis y Predicción de Abandono de Clientes (Churn)

## 🎯 Objetivo del Proyecto
Identificar los factores principales que causan la pérdida de clientes en una empresa de telecomunicaciones y construir un modelo predictivo capaz de anticipar qué clientes tienen mayor probabilidad de irse.

## 🛠️ Pipeline del Proyecto
1. **Limpieza de Datos:** Tratamiento de duplicados, corrección de errores tipográficos en contratos e imputación de valores nulos en la edad mediante la mediana.
2. **Análisis Exploratorio:** Identificación de inconsistencias lógicas (antigüedad negativa) y preparación de variables.
3. **Machine Learning:** Implementación de un modelo de clasificación **Random Forest**.
4. **Interpretabilidad:** Análisis de importancia de variables para negocio.

## 📊 Hallazgos Clave
* **Factor #1:** Los **Cargos Mensuales** elevados son el predictor más fuerte de abandono.
* **Factor #2:** Los clientes con **poca antigüedad** son más propensos a cancelar el servicio.

![Importancia de Variables](nombre_de_tu_grafico.png)

## 📈 Resultados del Modelo
El modelo Random Forest permite a la empresa priorizar esfuerzos de retención sobre los clientes de alto riesgo identificados por el algoritmo.
