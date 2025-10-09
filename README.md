# 💼 Proyecto: Optimización de Talento  
📊 **Consultora:** *Optimind Analytics*  
🏢 **Cliente:** ABC Data Corporation

---

## 🧭 Descripción General del Proyecto

El proyecto **Optimización de Talento** tiene como objetivo ayudar a **ABC Data** a identificar los **factores clave que influyen en la satisfacción laboral** y, en consecuencia, en la **retención de empleados**.  

A lo largo de tres fases, el equipo de *Optimind Analytics* ha desarrollado un proceso completo de análisis de datos, desde la exploración y limpieza hasta la visualización y elaboración de conclusiones estratégicas.

---

## ⚙️ Fases del Proyecto

### 🔹 **Fase 1: Análisis Exploratorio de Datos (EDA)**
- Estudio inicial de la base de datos `ABC_Data.csv`.
- Detección y eliminación de duplicados, valores inconsistentes y variables redundantes.
- Identificación de las principales variables relacionadas con la satisfacción y la retención.
- Generación del archivo resultante `EDA y eliminación de duplicados.parquet`.

📘 **Notebook:** `EDA y Eliminación de duplicados.ipynb.ipynb`

---

### 🔹 **Fase 2: Transformación de Datos**
- Limpieza y tratamiento de **valores nulos** o ausentes.
- Conversión de variables al tipo de dato adecuado.
- Creación del archivo limpio consolidado para análisis posteriores.

📘 **Notebook:** `Limpieza y tratamiento de nulos.ipynb`  
📦 **Salida:** `Archivo limpio.parquet` *(archivo principal para las visualizaciones de Fase 3)*

---

### 🔹 **Fase 3: Análisis Descriptivo y Visualización**
- Generación de **visualizaciones estadísticas** con *Seaborn* y *Matplotlib*.
- Análisis comparativo de **dimensiones de satisfacción**, **rotación (attrition)** y **relación entre ingresos y satisfacción**.
- Elaboración de un **informe ejecutivo** con las conclusiones y recomendaciones para la dirección de ABC Data.

📘 **Notebooks:**  
- `Análisis descriptivo 1.ipynb`  
- `Análisis descriptivo 2.ipynb`  
📄 **Informe:** `Informe Optimización de Talento.md`

---

## 🧩 Objetivos del Proyecto

🎯 **Principal:**  
Identificar los factores más influyentes en la **satisfacción laboral y la retención de empleados** dentro de ABC Data.  

🔍 **Secundarios:**  
- Analizar el impacto del trabajo remoto, el rol y la antigüedad sobre la rotación.  
- Evaluar la relación entre satisfacción e ingresos.  
- Detectar correlaciones entre dimensiones de satisfacción y métricas de desempeño.  
- Proporcionar recomendaciones basadas en datos para la toma de decisiones estratégicas de RRHH.

---

## 🧠 Stack Tecnológico

| Herramienta | Uso principal |
|--------------|----------------|
| **Python 3.11** | Lenguaje de análisis principal |
| **Pandas / NumPy** | Limpieza y manipulación de datos |
| **Seaborn / Matplotlib** | Visualización de resultados |
| **Jupyter Notebooks** | Desarrollo modular y presentación |
| **Parquet / CSV** | Almacenamiento intermedio y persistente |

---

## 🧑‍💻 Equipo Optimind Analytics — *Scrum Team*

| Rol | Nombre |
|------|--------|
| 👩‍💼 Data Analyst | **Ana Pilar Dueñas** |
| 👩‍💻 Data Scientist | **Siuzanna Danielian** |
| 🧭 Scrum Master | **Samai Manuz** |

💡 *La elección de la Scrum Master se realiza aleatoriamente mediante un script incluido en el repositorio.*

📘 **Notebook:** `Elección Scrum Master.ipynb`

---

## 📂 Estructura del Repositorio

    ├── ABC Data.csv                                    # Archivo original proporcionado por ABC Data
    ├── EDA y Eliminación de duplicados.ipynb           # Fase 1
    ├── EDA y eliminación de duplicados.parquet         # Fase 1
    ├── Limpieza y tratamiento de nulos.ipynb           # Fase 2  
    ├── Archivo limpio.parquet                          # Dataset final limpio
    ├── Análisis descriptivo 1.ipynb                    # Fase 3 
    ├── Análisis descriptivo 2.ipynb                    # Fase 3 
    ├── Elección Scrum Master.ipynb                     # Script de elección aleatoria del rol de Scrum Master
    ├── Informe Optimización de Talento.md              # Informe ejecutivo final
    └── README.md                                       # Descripción general del proyecto

---

## 📈 Resultados y Conclusiones Generales

✅ La satisfacción laboral se ve influida principalmente por **factores relacionales y de entorno**.  
📉 La rotación se concentra en **los primeros años de antigüedad** y en **puestos con mayor carga horaria**.  
💰 Los ingresos tienen una correlación positiva con la satisfacción, pero **no son el factor determinante**.  
🌐 El trabajo remoto incrementa el equilibrio vida-trabajo, aunque reduce la interacción social.  
🔗 Las dimensiones de satisfacción se comportan de forma **altamente interconectada**, por lo que las mejoras deben ser integrales.

---

## 📫 Contacto

**Optimind Analytics**  
📧 *insights@optimind-analytics.com*  
🌐 [www.optimind-analytics.com](https://www.optimind-analytics.com)

> “Convertimos los datos en decisiones inteligentes.”
