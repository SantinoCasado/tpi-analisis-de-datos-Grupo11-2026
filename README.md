# Trabajo Práctico Integrador: Análisis de Datos

## Presentación del proyecto

- **Proyecto:** Análisis y predicción del abandono de clientes (Telco Customer Churn)
- **Curso:** Trabajo Práctico Integrador
- **Grupo:** 11
- **Problema de negocio:** identificar los factores asociados a la cancelación de servicios de telecomunicaciones y explorar cómo los datos pueden ayudar a anticipar el abandono de clientes.

El proyecto recorre el ciclo de análisis de datos sobre el conjunto Telco Customer Churn: comprensión del problema y del dataset, ingesta y limpieza, análisis exploratorio y visualización, y preparación y evaluación de modelos predictivos.

### Abrir el notebook principal en Google Colab

[![Abrir en Google Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/SantinoCasado/tpi-analisis-de-datos-Grupo11-2026/blob/main/notebooks/TPI_Analisis_de_Datos.ipynb)

El conjunto de datos original está en `data/raw/WA_Fn-UseC_-Telco-Customer-Churn.csv`. El archivo procesado se encuentra en `data/processed/telco_customer_churn_processed.csv`. El análisis utiliza una única fuente, por lo que no se requiere unir datasets.

## Integrantes y división

- Ariana De Palma — División A
- Franco Moschini — División B1
- Candela Corral — División B2
- Santino Casado — División C

## Stack tecnológico

- **Python**: lenguaje de programación.
- **Pandas y NumPy**: ingesta, limpieza, transformación y análisis de datos.
- **Matplotlib y Seaborn**: visualización y análisis exploratorio.
- **Scikit-learn**: preprocesamiento, partición de datos y modelado predictivo.
- **Jupyter Notebook y Google Colab**: desarrollo y ejecución de los análisis.
- **Git y GitHub**: control de versiones y alojamiento del proyecto.

## Estructura y guía de exploración

```text
.
├── data/
│   ├── raw/
│   │   └── WA_Fn-UseC_-Telco-Customer-Churn.csv
│   └── processed/
│       └── telco_customer_churn_processed.csv
├── docs/
│   └── Trabajo Practico Integrador.pdf
├── notebooks/
│   ├── TPI_Analisis_de_Datos.ipynb
│   ├── TPI_Analisis_de_Datos_Ariana_A.ipynb
│   ├── TPI_Analisis_de_Datos_Candela_B2.ipynb
│   ├── TPI_Analisis_de_Datos_Franco_B1.ipynb
│   └── TPI_Analisis_de_Datos_Santino_C.ipynb
└── README.md
```

Para comenzar, abrí el notebook principal desde el badge de Google Colab. Los notebooks individuales contienen los desarrollos por integrante/división; el informe de presentación está en `docs/`, y los datos originales y procesados se encuentran en `data/raw/` y `data/processed/`, respectivamente.
