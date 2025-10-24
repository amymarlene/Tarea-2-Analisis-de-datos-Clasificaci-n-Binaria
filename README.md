# 🧠 **Análisis de Datos: Estilo de Vida y Patrones de Sueño**

![Python](https://img.shields.io/badge/Python-3.11-blue.svg) ![Colab](https://img.shields.io/badge/Colab-Yes-brightgreen.svg) ![Dataset](https://img.shields.io/badge/Dataset-374%20filas%2C%2012%20columnas-orange.svg)

---

## **📘 Descripción**

Este proyecto analiza el dataset **"Lifestyle and Sleep Patterns"** de Kaggle, explorando cómo los hábitos de vida afectan los niveles de estrés.  

Se realiza un **flujo completo de análisis de datos**, incluyendo:

- **Limpieza y exploración (EDA)**: Se realiza EDA y transformación inicial para asegurar consistencia de datos y preparar el dataset para análisis estadístico y modelado, evitando errores por tipos incorrectos o datos faltantes.
- **Filtrado de outliers**: Se elimina valores extremos para mejorar estabilidad de estadísticas y modelos predictivos, evitando que datos atípicos distorsionen resultados.
- **Creación de variable binaria de estrés** (**stress_binary**): La variable binaria es más útil para clasificación y permite entrenar modelos predictivos de manera clara.
- **Análisis univariante y bivariante con gráficos**: Permite entender la distribución y concentración de datos, identificar patrones y preparar estrategias de filtrado y análisis bivariante. Identifica qué variables están fuertemente asociadas al estrés, permitiendo priorizar las más relevantes en modelos predictivos.
- **Matriz de correlación**: Se eliminan variables redundantes o con menos relevancia, manteniendo las más representativas para evitar multicolinealidad.
- **División train/test lista para modelado predictivo**: La estratificación asegura que la proporción de la variable objetivo se mantenga, evitando sesgos en modelos predictivos.

**Dataset original:** [Kaggle - Lifestyle and Sleep Patterns](https://www.kaggle.com/datasets/minahilfatima12328/lifestyle-and-sleep-patterns)

---

## **🎯 Objetivo**

Analizar la relación entre hábitos de vida y niveles de estrés, preparando los datos para un **modelo predictivo**.

**Variables clave:**

- Horas y calidad de sueño  
- Nivel de actividad física y pasos diarios  
- Presión arterial, frecuencia cardiaca y categoría de IMC  
- Presencia de trastornos del sueño  

---

## **🗂 Estructura del Notebook**

<details>
<summary>📌 **Ver estructura completa**</summary>

### **1️⃣ Librerías**  
- pandas, numpy, matplotlib, seaborn, scikit-learn  

### **2️⃣ Subida y carga del CSV**  
- Desde Google Colab  

### **3️⃣ Exploración inicial**  
- Filas, columnas, tipos de datos y valores nulos  

### **4️⃣ Transformación de columnas categóricas**  
- Convertir variables a tipo `category`  

### **5️⃣ Análisis univariante**  
- Estadísticas descriptivas y histogramas  

### **6️⃣ Filtrado de outliers (IQR)**  
- Eliminación de valores extremos  

### **7️⃣ Variable objetivo binaria**  
- Creación de **stress_binary**  

### **8️⃣ Análisis bivariante con gráficos**  
- Comparación de estrés con otras variables  

### **9️⃣ Matriz de correlación**  
- Identificación de relaciones entre variables numéricas  

### **🔟 División Train/Test**  
- Estratificada y exportación a CSV  

### **1️⃣1️⃣ Descarga de CSV**  
- Guardar archivos localmente desde Colab  

</details>

---

## **📊 Ejemplos de Gráficos**

<details>
<summary>📌 **Ver gráficos**</summary>

**Sleep Duration vs Estrés**  

<img width="701" height="479" alt="image" src="https://github.com/user-attachments/assets/a1b1f511-d814-4c71-bedf-ef1dee40de90" />


**Physical Activity Level vs Estrés**  

<img width="696" height="479" alt="image" src="https://github.com/user-attachments/assets/affe6add-184b-484a-8982-c2ecbdcfd44a" />


**Sleep Disorder vs Estrés**  

<img width="696" height="479" alt="image" src="https://github.com/user-attachments/assets/822352f2-c1f3-438f-b6ba-695bac56865d" />


**Matriz de correlación**  

<img width="952" height="841" alt="image" src="https://github.com/user-attachments/assets/fdfab5e6-64e3-435a-95e1-d244ec33b08f" />


</details>

---

## **💡 Conclusiones**

<details>
<summary>📌 **Ver conclusiones**</summary>

- Dormir menos horas y tener menor actividad física aumenta el riesgo de estrés  
- Trastornos del sueño están fuertemente asociados a estrés alto  
- Filtrado de outliers mejora la estabilidad y confiabilidad del análisis  
- División estratificada asegura proporciones balanceadas entre train/test  

</details>

---

## **🧰 Requisitos**

- Python 3.x  
- Librerías: `pandas`, `numpy`, `matplotlib`, `seaborn`, `scikit-learn`  
- Google Colab recomendado  

