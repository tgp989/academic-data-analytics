# Academic Data Analytics

## Descripción

Este repositorio reúne diferentes trabajos, talleres y evaluaciones desarrollados durante mi formación en **análisis de datos y Machine Learning**.

Los contenidos corresponden a trabajos académicos desarrollados en tres áreas principales:

- Integración de datos y prospectiva
- Machine Learning supervisado
- Machine Learning no supervisado

El repositorio funciona como complemento de los proyectos principales de mi portafolio. Los trabajos seleccionados como proyectos principales cuentan con repositorios independientes y documentación específica, mientras que este repositorio conserva otros ejercicios y proyectos desarrollados durante el proceso de formación.

---

## Contenido

### Integración de datos y prospectiva

Esta sección reúne trabajos relacionados con el análisis de riesgo operacional, integración de datos, teoría de la credibilidad, distribución de pérdidas y análisis de diferentes escenarios de riesgo.

Incluye:

- **Reto 1 – Gestión de riesgos operacionales en FINTECH**
  - Análisis de frecuencia y severidad.
  - Distribución agregada de pérdidas (LDA).
  - Simulación de pérdidas mediante Monte Carlo.

- **Reto 2 – Teoría de la Credibilidad en FINTECH**
  - Integración de una base interna y una base externa.
  - Análisis de credibilidad.
  - Caracterización de pérdidas.
  - Simulación mediante Monte Carlo.

- **Reto 3 – Integración de Datos en una Entidad Prestadora de Salud**
  - Análisis de sucursales.
  - Teoría de la credibilidad.
  - Métodos de aceptación y rechazo.
  - Comparación de afinidad entre sucursales.

- **Reto 5 – Evaluación del Riesgo Operacional en Canales Electrónicos**
  - Matrices de frecuencia y severidad.
  - Análisis de pérdidas agregadas.
  - Evaluación del riesgo operacional.

Los Retos 4 y 6 de este conjunto fueron seleccionados como proyectos principales y, por esta razón, no se duplican en este repositorio.

---

### Machine Learning supervisado

Esta sección reúne diferentes ejercicios y evaluaciones relacionados con modelos de aprendizaje supervisado, principalmente problemas de regresión y clasificación.

Incluye:

- **Parcial 1 – Regresión múltiple y regularización**
  - Análisis de factores asociados a los salarios.
  - Regresión múltiple.
  - Métodos de regularización.

- **Taller 1 – Predicción de ventas**
  - Predicción de ventas de clientes.
  - Regresión lineal.
  - Ridge.
  - Lasso.
  - Random Forest.

- **Taller extra – Insurance**
  - Análisis y modelación de información relacionada con cargos médicos.

- **Taller Real Estate**
  - Modelación de información relacionada con precios inmobiliarios.

- **Taller de regresión logística**
  - Predicción del riesgo de enfermedad coronaria.
  - Regresión logística.
  - Evaluación del desempeño del modelo.

- **Taller de redes neuronales**
  - Predicción de satisfacción laboral.
  - Construcción de redes neuronales utilizando Keras.

El **Parcial 2 – Redes neuronales para Customer Churn** fue seleccionado como proyecto principal y cuenta con un repositorio independiente.

---

### Machine Learning no supervisado

Esta sección reúne ejercicios relacionados con clustering, análisis exploratorio, segmentación de clientes y procesamiento de texto.

Incluye:

- **Taller Parcial 2 – Satisfacción de clientes bancarios**
  - Segmentación de clientes.
  - Caracterización de grupos.
  - Análisis de satisfacción.

- **Taller Parcial – Accidentalidad en Medellín**
  - Análisis de accidentes de tránsito.
  - Identificación de patrones relacionados con horarios, fechas y ubicación.
  - Apoyo a la planeación de agentes de tránsito y ambulancias.

- **Taller de análisis de sentimientos y procesamiento de texto**
  - Limpieza de texto.
  - Eliminación de stopwords.
  - Análisis de sentimientos con TextBlob.
  - Comparación con otro método de análisis de sentimientos.

- **Taller 4 – Extracción de información web**
  - Obtención de información desde Wikipedia.
  - Extracción y almacenamiento de tablas mediante Python.

- **Ejercicio de clustering – EastWest Airlines**
  - Segmentación de pasajeros.
  - Identificación de grupos con características similares.
  - Análisis orientado a diferentes ofertas de millas.

- **Taller 1 – Análisis descriptivo**
  - Exploración y análisis descriptivo de información de clientes.
  - Uso de la base Customer Personality Analysis.

El **Proyecto Final – Airline Review Analytics** fue seleccionado como proyecto principal y cuenta con un repositorio independiente.

---

## Herramientas y tecnologías

Los trabajos incluidos en este repositorio fueron desarrollados utilizando diferentes herramientas y librerías de análisis de datos:

### Lenguajes

- **Python**

### Análisis y manipulación de datos

- **Pandas**
- **NumPy**

### Visualización

- **Matplotlib**
- **Seaborn**

### Machine Learning

- **Scikit-learn**
- **K-Means**
- **DBSCAN**
- **Clustering jerárquico**
- **Regresión lineal**
- **Regresión logística**
- **Ridge**
- **Lasso**
- **Random Forest**
- **Redes neuronales**

### Análisis estadístico y de riesgo

- **Monte Carlo**
- **Loss Distribution Approach (LDA)**
- **Teoría de la Credibilidad**
- **Métodos de aceptación y rechazo**

### Procesamiento de lenguaje natural

- **TextBlob**
- **BeautifulSoup**
- **Requests**

### Entorno

- **Google Colab**
- **Jupyter Notebook**

---

## Estructura del repositorio

```text
academic-data-analytics/
│
├── README.md
│
├── data-integration-prospectivity/
│   ├── Reto 1.ipynb
│   ├── Reto 2.ipynb
│   ├── Reto 3.ipynb
│   └── Reto 5.ipynb
│
├── supervised-learning/
│   ├── Parcial_1.ipynb
│   ├── Taller extra.ipynb
│   ├── Taller real estate.ipynb
│   ├── Taller1.ipynb
│   ├── Taller_RL.ipynb
│   └── Taller_redes_neuronales.ipynb
│
└── unsupervised-learning/
    ├── Taller_parcial_2.ipynb
    ├── Taller_parcial_Santiago_Giraldo.ipynb
    ├── Taller analisis de sentimientos.ipynb
    ├── Taller 4.ipynb
    ├── Ejercicio.ipynb
    └── Taller 1 - Analisis descriptivo.ipynb
