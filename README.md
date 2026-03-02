# 📊 Análisis de Evasión de Clientes (Churn)
## 📌 Descripción del Proyecto

Este proyecto tiene como objetivo analizar el fenómeno de evasión de clientes (Churn) en una empresa de telecomunicaciones, utilizando técnicas de limpieza de datos, análisis exploratorio y visualización.

El propósito es identificar patrones y factores asociados a la cancelación del servicio para generar recomendaciones estratégicas que permitan reducir la tasa de abandono.

## 🎯 Objetivos

- Analizar la distribución del churn.
- Identificar variables categóricas y numéricas asociadas a la evasión.
- Detectar patrones de comportamiento en clientes que cancelan.
- Generar insights estratégicos basados en datos.

## 🗂 Estructura del Proyecto
📁 churn-analysis
│
├── analisis_churn.ipynb
├── data/
│   └── telecom_churn.csv
├── README.md
└── requirements.txt
## ⚙️ Instalación y Dependencias
🔹 Requisitos

Python 3.9 o superior

Jupyter Notebook o Google Colab

🔹 Librerías utilizadas

- pandas
- numpy
- matplotlib

Instalación rápida:

pip install pandas numpy matplotlib seaborn scikit-learn

O usando requirements.txt:

pip install -r requirements.txt
## ▶️ Cómo Ejecutar el Proyecto

Clonar el repositorio:
```bash
git clone https://github.com/Druiz-leon/challenge2-data-science-LATAM.git
```
Ingresar a la carpeta del proyecto:
```bash
cd churn-analysis
```
Ejecutar Jupyter Notebook:

jupyter notebook

Abrir el archivo:

analisis_churn.ipynb

Ejecutar las celdas en orden.

🧹 Procesamiento de Datos

Durante el análisis se realizaron las siguientes transformaciones:

- Eliminación de valores nulos en la variable objetivo Churn
- Conversión de variables categóricas binarias a formato 0/1
- Creación de la variable Cargo_Diario
- Estandarización de texto
- Codificación de variables categóricas (One-Hot Encoding cuando fue necesario)

## 📊 Análisis Exploratorio

Se realizaron análisis como:

- Distribución general del Churn
- Churn por tipo de contrato
- Churn por método de pago
- Churn por servicio de internet
- Comparación de variables numéricas (tenure, cargo mensual, gasto total)

Visualizaciones incluidas:

- Gráficos de barras
- Histogramas
- Boxplots
- Comparaciones por grupo

## 🔎 Principales Hallazgos

- Los contratos mensuales presentan mayor tasa de evasión.
- Clientes con menor antigüedad tienen mayor probabilidad de cancelar.
- Cargos mensuales más altos están asociados a mayor churn.
- Métodos de pago automáticos reducen la evasión.

## 💡 Recomendaciones Estratégicas

- Incentivar contratos de largo plazo.
- Promover métodos de pago automáticos.
- Implementar estrategias de retención temprana.
- Desarrollar un modelo predictivo de churn.

## 🚀 Posibles Mejoras Futuras

- Implementar modelo de Machine Learning (Logistic Regression, Random Forest).
- Evaluar importancia de variables.
- Crear dashboard interactivo (Power BI o Streamlit).
- Aplicar técnicas de balanceo de datos si el dataset está desbalanceado.

### 👩🏻‍💻 Autor

Proyecto desarrollado por:
Deyanira Ruiz

### 📄 Licencia

Este proyecto se desarrolla con fines académicos y de aprendizaje.
