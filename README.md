# Predicción del Abandono de Clientes en un Gimnasio

## 📌 Descripción del Proyecto

La retención de clientes es uno de los mayores desafíos para los negocios basados en suscripciones, como los gimnasios.

Este proyecto analiza el comportamiento de los clientes para identificar los factores asociados con la cancelación de su membresía (*churn*). Además, se desarrollan modelos de **Machine Learning** para predecir el abandono de clientes y se aplican técnicas de segmentación para identificar diferentes perfiles de usuarios.

---

## 🎯 Objetivo

Los principales objetivos de este proyecto son:

* Realizar un Análisis Exploratorio de Datos (EDA).
* Identificar las variables relacionadas con el abandono de clientes.
* Construir modelos de clasificación predictiva.
* Comparar el rendimiento de diferentes modelos.
* Segmentar clientes utilizando el algoritmo K-Means.
* Generar recomendaciones de negocio para mejorar la retención de clientes.

---

## 📊 Conjunto de Datos

El conjunto de datos contiene información de aproximadamente **4,000 clientes** de un gimnasio e incluye variables demográficas, de comportamiento y relacionadas con su contrato.

Algunas de las variables incluidas son:

* Género
* Edad
* Cercanía al gimnasio
* Membresía corporativa
* Invitación por amigos
* Duración del contrato
* Asistencia a clases grupales
* Gasto promedio en servicios adicionales
* Frecuencia promedio de asistencia
* Antigüedad del cliente
* Churn (Variable Objetivo)

---

## 🛠 Tecnologías Utilizadas

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-Learn
* SciPy

---

## 📈 Análisis Exploratorio de Datos

El análisis exploratorio incluyó:

* Inspección de los datos.
* Análisis de valores faltantes.
* Detección de registros duplicados.
* Estadísticas descriptivas.
* Histogramas.
* Análisis de distribuciones.
* Matriz de correlación (Heatmap).

### Principales hallazgos

* Los clientes con contratos de mayor duración tienden a permanecer más tiempo en el gimnasio.
* Una alta frecuencia de asistencia está fuertemente relacionada con una mayor retención de clientes.
* Los clientes que viven cerca del gimnasio tienen mayor probabilidad de mantenerse activos.
* Un mayor gasto en servicios adicionales se asocia con menores tasas de abandono.

---

## 🤖 Machine Learning

Se entrenaron dos modelos de clasificación:

* Regresión Logística.
* Random Forest.

### Desempeño

| Modelo              | Exactitud (Accuracy) | F1 Score |
| ------------------- | -------------------: | -------: |
| Regresión Logística |                 0.92 |     0.83 |
| Random Forest       |                 0.92 |     0.83 |

Ambos modelos obtuvieron un excelente desempeño predictivo, destacando la Regresión Logística por presentar un mejor equilibrio entre precisión y sensibilidad (*Recall*).

---

## 👥 Segmentación de Clientes

La segmentación de clientes se realizó utilizando:

* StandardScaler.
* Clustering Jerárquico (Dendrograma).
* K-Means.

Se identificaron **cinco grupos de clientes**, cada uno con diferentes comportamientos respecto al abandono de la membresía.

Los clientes con:

* Contratos de larga duración.
* Alta frecuencia de asistencia.
* Mayor gasto en servicios adicionales.

presentaron las menores tasas de abandono.

---

## 💡 Recomendaciones de Negocio

* Incentivar la contratación de planes de mayor duración.
* Promover las actividades grupales para incrementar el compromiso de los clientes.
* Desarrollar programas de fidelización para nuevos miembros.
* Ofrecer promociones personalizadas a clientes con alto riesgo de abandono.

---

## 📂 Estructura del Repositorio

```text
gym-churn-prediction/
│
├── Gym_Churn.ipynb
├── README.md
├── data/
│   └── gym_churn_us.csv
└── images/
```

---

## 🚀 Cómo Ejecutar el Proyecto

Clona el repositorio:

```bash
git clone https://github.com/tuusuario/gym-churn-prediction.git
```

Instala las dependencias:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn scipy
```

Abre el notebook:

```bash
jupyter notebook Gym_Churn.ipynb
```

---

## 📌 Resultados

* Se alcanzó una **exactitud del 92%** en la predicción del abandono de clientes.
* Se identificaron las características de los clientes asociadas con la cancelación de la membresía.
* Se segmentó a los clientes en cinco grupos con comportamientos diferenciados.
* Se propusieron estrategias de negocio orientadas a mejorar la retención de clientes.

---

## 👨‍💻 Autor

**Diego Alonso Morales Salazar**

**Analista de Datos | Python | SQL | Power BI**

GitHub: https://github.com/diegoverclock

LinkedIn: www.linkedin.com/in/diego-morales-salazar
