# 🤖 Proyecto Capstone: Detección de Autofraude con Machine Learning

Este repositorio contiene el desarrollo completo de un sistema de detección de fraude, enfocado especialmente en identificar casos de **autofraude**. El proyecto abarca desde la exploración inicial de los datos hasta el despliegue del modelo final.

---

## 📚 Tabla de Contenidos

- [🤖 Proyecto Capstone: Detección de Autofraude con Machine Learning](#-proyecto-capstone-detección-de-autofraude-con-machine-learning)
  - [📚 Tabla de Contenidos](#-tabla-de-contenidos)
  - [🚀 Objetivo del Proyecto](#-objetivo-del-proyecto)
  - [🧱 Estructura de la Presentación (`presentacion-capstone/`)](#-estructura-de-la-presentación-presentacion-capstone)
  - [🧱 Estructura del Proyecto (`ml-capstone-project/`)](#-estructura-del-proyecto-ml-capstone-project)

---

## 🚀 Objetivo del Proyecto

Desarrollar un sistema capaz de detectar patrones de comportamiento asociados a **autofraude** en reclamos de fraude, utilizando técnicas de *machine learning* entrenadas con datos históricos de clientes.  

El sistema incluye:
- Identificación de patrones relevantes,
- Optimización del punto de corte,
- Maximización del beneficio esperado,
- Aplicación de técnicas de procesamiento de lenguaje natural (NLP),
- Modelos multivariables para segmentación y análisis de demanda potencial (*Customer Lifetime Value*).

---

## 🧱 Estructura de la Presentación (`presentacion-capstone/`)

```bash
presentacion-capstone/
│
├── explicar-el-problema/       # Diferencia entre fraude y autofraude, impacto en la industria
├── objetivos/                  
│   ├── obj1/                   # Objetivo original: detección de autofraude
│   ├── obj2/                   # Incorporación de NLP como objetivo adicional
│   └── obj3/                   # Modelo multivariable: segmentación, CLV y evaluación de demanda
├── alcances/                   # Límites del proyecto, decisiones tomadas
├── metodologia/                # Descripción de la metodología utilizada
├── revision-bibliografica/    # Revisión teórica y antecedentes (en progreso)
├── desarrollo-metodologico/
│   ├── eda/                    # Análisis exploratorio de datos
│   ├── ingenieria-atributos/   # Creación y selección de variables
│   └── analisis-sens-costos/   # Análisis de sensibilidad y costos
```

---

## 🧱 Estructura del Proyecto (`ml-capstone-project/`)

```bash
ml-capstone-project/
│
├── README.md                   # Descripción general del proyecto
├── requirements.txt            # Dependencias del entorno (pip)
├── environment.yml             # Configuración alternativa con Conda
├── .gitignore                  # Archivos excluidos del control de versiones
│
├── data/                       # Datos del proyecto
│   ├── raw/                    # Datos originales sin procesar
│   ├── processed/              # Datos transformados y listos para modelar
│   └── external/               # Datos externos complementarios
│
├── notebooks/                  # Notebooks para análisis y desarrollo
│   ├── 01_EDA.ipynb
│   ├── 02_FeatureEngineering.ipynb
│   └── 03_ModelTraining.ipynb
│
├── src/                        # Código fuente del proyecto
│   ├── __init__.py
│   ├── data_preprocessing.py
│   ├── feature_engineering.py
│   ├── model_training.py
│   └── evaluate.py
│
├── models/                     # Modelos entrenados y serializados
│   └── final_model.pkl
│
├── outputs/                    # Resultados y visualizaciones
│   ├── figures/
│   └── metrics/
│
├── app/                        # Código de despliegue del modelo (opcional)
│   ├── main.py
│   └── model_utils.py
│
└── reports/                    # Informes y presentaciones
    ├── capstone_report.pdf
    └── slides.pptx
```