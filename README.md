🧠 **Análisis de Datos: Estilo de Vida y Patrones de Sueño**



📘 **Descripción**

Este proyecto analiza el dataset "Lifestyle and Sleep Patterns" de Kaggle, explorando cómo los hábitos de vida afectan los niveles de estrés. Se realiza un flujo completo de análisis:

Limpieza y exploración (EDA)

Filtrado de outliers

Creación de variable binaria de estrés (stress_binary)

Análisis univariante y bivariante con gráficos

Matriz de correlación

División train/test lista para modelado predictivo

Dataset original: Kaggle - Lifestyle and Sleep Patterns

🎯 **Objetivo**

Analizar la relación entre hábitos de vida y estrés, preparando los datos para un modelo predictivo. Variables clave:

Horas y calidad de sueño

Nivel de actividad física y pasos diarios

Presión arterial, frecuencia cardiaca y categoría de IMC

Presencia de trastornos del sueño

🗂 **Estructura del Notebook**

Librerías

Subida y carga del CSV

Exploración inicial

Transformación de columnas categóricas

Análisis univariante

Filtrado de outliers (IQR)

Creación de variable binaria stress_binary

Análisis bivariante con gráficos

Matriz de correlación

División Train/Test

Descarga de CSV para tu PC

📊 **Ejemplos de Gráficos**

Sleep Duration vs Estrés

Physical Activity Level vs Estrés

Sleep Disorder vs Estrés

Matriz de correlación

(Reemplaza estas imágenes con capturas reales de tus gráficos en Colab antes de subir a GitHub.)

💡 **Conclusiones**

Dormir menos y tener menor actividad física aumenta el riesgo de estrés.

Trastornos del sueño se asocian a estrés alto.

Filtrado de outliers mejora la estabilidad del análisis.

División estratificada mantiene proporciones balanceadas entre train/test.

🧰 **Requisitos**

Python 3.x

Librerías: pandas, numpy, matplotlib, seaborn, scikit-learn

Google Colab recomendado

Instalación rápida:

pip install pandas numpy matplotlib seaborn scikit-learn

⚡ **Uso**

Abrir el notebook en Google Colab.

Ejecutar la celda de subida de CSV.

Ejecutar todas las celdas en orden.

Se generarán train.csv y test.csv listos para modelado.
