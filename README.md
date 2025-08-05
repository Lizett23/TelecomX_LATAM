# TelecomX_LATAM
# 📊 Análisis de Evasión de Clientes (Churn) - Telecom X

Este proyecto analiza el fenómeno de **evasión de clientes** en una empresa de telecomunicaciones, con el objetivo de identificar patrones que expliquen por qué algunos usuarios abandonan el servicio. A través de técnicas de análisis exploratorio de datos (EDA), se generan visualizaciones e insights que permiten sugerir estrategias para **mejorar la retención**.

---

## 🎯 Propósito del Análisis

La finalidad de este trabajo es:
- Analizar las características de los clientes que abandonan el servicio (*Churn*).
- Explorar variables categóricas y numéricas que se relacionan con la evasión.
- Identificar comportamientos y factores críticos para generar estrategias que reduzcan el churn.
- Apoyar la toma de decisiones de negocio con base en datos reales.

---


> ✅ **Nota**: Todos los pasos del análisis están incluidos en el notebook: carga de datos, limpieza, visualización, conclusiones y recomendaciones.

---

## 📈 Ejemplos de Visualizaciones e Insights

### 🔹 Distribución de Churn por Método de Pago
Clientes que pagan mediante `Electronic Check` tienden a abandonar más que quienes utilizan métodos automáticos como tarjeta de crédito o transferencia bancaria.

![Método de Pago vs Churn](https://github.com/Lizett23/TelecomX_LATAM/blob/main/Churn_metodo.png)

---

### 🔹 Meses de Contrato
La evasión ocurre principalmente durante los **primeros meses del contrato**, indicando que la fidelización temprana es crítica.

![Meses Contrato vs Churn](img/meses_contrato.png)

---

### 🔹 Cargo Mensual
Los clientes con cargos mensuales más altos tienden a abandonar con mayor frecuencia, sugiriendo una posible **sensibilidad al precio**.

![Cargo Mensual vs Churn](img/cargo_mensual.png)

---

## ⚙️ Instrucciones para Ejecutar el Proyecto

Puedes ejecutar el análisis de dos formas:

### 1. 🔗 Google Colab (Recomendado)
- Abre el notebook desde este [enlace de Colab](https://colab.research.google.com/).
- Sube tu archivo `dataset.csv` si es necesario.
- Ejecuta las celdas paso a paso.

### 2. 🖥️ Localmente
Asegúrate de tener instalado:

```bash
Python 3.10+
Jupyter Notebook o VS Code
pandas
matplotlib
seaborn
git clone https://github.com/TU_USUARIO/TU_REPOSITORIO.git
cd TU_REPOSITORIO
jupyter notebook

