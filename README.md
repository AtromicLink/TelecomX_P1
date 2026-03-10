# Telecom X — Análisis de Evasión de Clientes

### Challenge 1 · Data Science · Alura Latam + Oracle Next Education

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.10+-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python">
  <img src="https://img.shields.io/badge/Pandas-Data%20Analysis-150458?style=for-the-badge&logo=pandas&logoColor=white" alt="Pandas">
  <img src="https://img.shields.io/badge/Jupyter-Notebook-F37626?style=for-the-badge&logo=jupyter&logoColor=white" alt="Jupyter">
  <img src="https://img.shields.io/badge/License-MIT-green?style=for-the-badge" alt="MIT License">
  <img src="https://img.shields.io/badge/Status-Completed-success?style=for-the-badge" alt="Status">
</p>

---

## Tabla de Contenidos

1. [Sobre el Proyecto](#sobre-el-proyecto)
2. [Problema de Negocio](#problema-de-negocio)
3. [Metodología ETL](#metodología-etl)
4. [Resultados del Análisis](#resultados-del-análisis)
5. [Conclusiones e Insights](#conclusiones-e-insights)
6. [Recomendaciones Estratégicas](#recomendaciones-estratégicas)
7. [Estructura del Repositorio](#estructura-del-repositorio)
8. [Tecnologías Utilizadas](#tecnologías-utilizadas)
9. [Instalación y Uso](#instalación-y-uso)
10. [Autor](#autor)

---

## Sobre el Proyecto

Este proyecto desarrolla un análisis integral de evasión de clientes (*churn*) para Telecom X, a partir de un dataset en formato JSON con información demográfica, servicios contratados, facturación y estado de cancelación.

El objetivo principal fue transformar datos crudos en información accionable mediante un proceso estructurado de extracción, limpieza, estandarización y análisis exploratorio, con el fin de identificar patrones asociados a la pérdida de clientes.

---

## Problema de Negocio

La evasión de clientes representa un reto crítico para empresas del sector telecomunicaciones, ya que impacta de forma directa los ingresos recurrentes, incrementa los costos de adquisición y debilita la estabilidad comercial.

En este contexto, el análisis busca responder preguntas como:

- ¿Qué perfiles de clientes presentan mayor riesgo de evasión?
- ¿Qué variables contractuales, financieras o de servicio están asociadas al churn?
- ¿Qué hallazgos pueden orientar estrategias de retención más efectivas?

---

## Metodología ETL

El proyecto fue desarrollado bajo una lógica ETL compuesta por tres fases principales:

### 1. Extracción
Se realizó la carga del dataset desde una fuente JSON pública y su transformación a una estructura tabular con `pandas.json_normalize()`.

### 2. Transformación
Se llevaron a cabo tareas de:

- exploración de columnas y tipos de datos,
- tratamiento de valores nulos y registros inconsistentes,
- corrección de formatos,
- estandarización de variables categóricas,
- renombre de columnas para facilitar su interpretación,
- creación de la variable `Cuentas_Diarias`.

### 3. Carga y Análisis
Con la base ya limpia, se ejecutó el análisis exploratorio de datos, incluyendo métricas descriptivas, visualizaciones y evaluación de la distribución del churn en variables categóricas y numéricas.

---

## Resultados del Análisis

Entre los hallazgos más relevantes del análisis se destacan los siguientes:

### 1. Distribución general de churn
Se identificó una proporción relevante de clientes que cancelaron el servicio, lo que confirma la importancia del problema y la necesidad de estrategias de retención basadas en datos.

### 2. Tipo de contrato
Los clientes con contratos más flexibles, especialmente mes a mes, presentan una mayor tendencia a la evasión frente a aquellos con compromisos de mayor duración.

### 3. Antigüedad del cliente
Los clientes con menor tiempo de permanencia muestran mayor vulnerabilidad al churn, lo que sugiere una ventana crítica en los primeros meses de relación.

### 4. Cargos mensuales
Se observó que los clientes con evasión tienden a registrar cargos mensuales más altos, lo que podría indicar sensibilidad al precio o baja percepción de valor.

### 5. Método de pago
Ciertos métodos de pago presentan una asociación más fuerte con la evasión, especialmente aquellos que no generan automatización o compromiso recurrente.

---

## Conclusiones e Insights

El análisis permitió confirmar que la evasión no ocurre de manera aleatoria, sino que responde a patrones identificables en variables de permanencia, estructura contractual, facturación y método de pago.

Estos resultados aportan una base sólida para futuras etapas de modelado predictivo, segmentación de clientes y diseño de estrategias de retención más precisas.

---

## Recomendaciones Estratégicas

A partir de los hallazgos obtenidos, se sugieren las siguientes acciones:

- fortalecer estrategias de fidelización para clientes con contratos mensuales,
- diseñar acciones de retención temprana durante los primeros meses del ciclo de vida,
- revisar propuestas de valor para clientes con cargos mensuales elevados,
- incentivar métodos de pago automáticos,
- utilizar estas variables como insumo base para un modelo predictivo de churn.

---

## Estructura del Repositorio

```bash
TelecomX_P1/
│
├── TelecomX_LATAM.ipynb
├── README.md
├── LICENSE
├── telecomx_clientes_limpio.csv
│
└── assets/
    ├── banner_alura.svg
    └── images/
        └── img.png
```
### 📩 

AtromicLink(LinkedGTF)
Jose Torreglosa.

<img src="./images/Despedida.gif" alt="GIF de Bienvenida" width="600">

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/jtorreglosam/)
[![Gmail](https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:josddaniel1@gmail.com)

---
