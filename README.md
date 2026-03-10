# Telecom X — Análisis de Evasión de Clientes (Churn)

## Descripción del proyecto
Este proyecto desarrolla un análisis de datos orientado a identificar patrones de evasión de clientes (*churn*) en Telecom X. A partir de un dataset en formato JSON, se realiza un proceso completo de extracción, transformación, limpieza, estandarización y análisis exploratorio de datos, con el objetivo de generar información útil para la toma de decisiones estratégicas.

El enfoque del proyecto combina una perspectiva técnica y de negocio: no solo busca preparar los datos correctamente, sino también comprender qué variables pueden estar asociadas con una mayor probabilidad de cancelación del servicio.

---

## Objetivo
Analizar el comportamiento de los clientes de Telecom X para detectar factores relacionados con la evasión, apoyando la formulación de estrategias que contribuyan a la retención de usuarios y a la reducción del churn.

---

## Problema de negocio
La evasión de clientes representa uno de los principales retos para las empresas de telecomunicaciones, ya que impacta directamente los ingresos, la estabilidad comercial y los costos de adquisición de nuevos usuarios.

En este contexto, el análisis de churn permite responder preguntas clave como:

- ¿Qué tipo de clientes presentan mayor tendencia a cancelar el servicio?
- ¿Existen variables contractuales, demográficas o financieras asociadas con la evasión?
- ¿Qué patrones pueden orientar acciones preventivas de retención?

---

## Alcance del análisis
El proyecto contempla las siguientes etapas:

1. **Extracción de datos** desde una fuente JSON.
2. **Conversión y normalización** de la información a un DataFrame de Pandas.
3. **Exploración de la estructura del dataset**, tipos de datos y variables disponibles.
4. **Limpieza y tratamiento de datos**, incluyendo validación de nulos, duplicados e inconsistencias.
5. **Creación de nuevas variables**, como `Cuentas_Diarias`.
6. **Estandarización de datos y renombre de columnas** para facilitar su interpretación.
7. **Análisis exploratorio de datos (EDA)** con métricas descriptivas y visualizaciones.
8. **Identificación de patrones de churn** en variables categóricas y numéricas.
9. **Elaboración de conclusiones e insights** con enfoque estratégico.

---

## Fuente de datos
Los datos utilizados en este proyecto provienen del challenge de Telecom X en formato JSON, e incluyen información relacionada con:

- datos demográficos del cliente,
- servicios contratados,
- información de cuenta y facturación,
- estado de evasión (*churn*).

---

## Tecnologías utilizadas
- **Python 3**
- **Pandas**
- **NumPy**
- **Matplotlib**
- **Seaborn**
- **Jupyter Notebook**

---

## Metodología aplicada
La metodología del análisis se desarrolló en cinco bloques principales:

### 1. Extracción y carga
Se realizó la lectura del archivo JSON directamente desde la fuente de datos y su transformación a una estructura tabular mediante `pandas.json_normalize()`.

### 2. Exploración inicial
Se inspeccionaron columnas, tipos de datos y estructura general del dataset para comprender la naturaleza de las variables y su relevancia para el análisis de evasión.

### 3. Limpieza y tratamiento
Se identificaron y corrigieron problemas de calidad de datos, como:
- valores nulos o vacíos,
- variables numéricas almacenadas como texto,
- categorías inconsistentes,
- registros no aptos para el análisis de la variable objetivo.

### 4. Transformación y estandarización
Se aplicaron ajustes para mejorar la legibilidad y el análisis, entre ellos:
- conversión de variables categóricas a formatos más consistentes,
- renombre de columnas,
- creación de variables derivadas,
- preparación de campos para análisis descriptivo y visual.

### 5. Análisis exploratorio
Se estudiaron patrones de churn mediante:
- estadísticas descriptivas,
- distribución de la variable objetivo,
- análisis por variables categóricas,
- análisis comparativo de variables numéricas.

---

## Estructura del repositorio
```bash
.
├── telecomx_churn_analysis.ipynb
├── telecomx_churn_analysis_executed.ipynb
├── telecomx_clientes_limpio.csv
└── README.md
