Análisis de Datos: Estilo de Vida y Patrones de Sueño
📘 Descripción

Este proyecto analiza el dataset "Lifestyle and Sleep Patterns" de Kaggle, enfocándose en cómo los hábitos de vida afectan los niveles de estrés. El análisis incluye limpieza, exploración, visualización y preparación de datos para modelado predictivo.

Dataset original: Kaggle - Lifestyle and Sleep Patterns

🎯 Objetivo

Estudiar la relación entre:

Horas y calidad de sueño

Nivel de actividad física y pasos diarios

Presión arterial, frecuencia cardiaca y categoría de IMC

Presencia de trastornos del sueño

con los niveles de estrés y generar un dataset listo para modelado.

🗂 Estructura del Notebook

Librerías: pandas, numpy, matplotlib, seaborn, scikit-learn.

Subir y cargar CSV: carga automática en Colab.

Exploración inicial: dimensiones, tipos de datos y nulos.

Transformación categórica: convierte variables a tipo category.

EDA univariante: histogramas y estadísticas descriptivas.

Filtrado de outliers: método IQR para valores extremos.

Variable objetivo binaria: stress_binary (0 = moderado, 1 = alto).

Análisis bivariante: gráficos que comparan estrés con otras variables.

Matriz de correlación: relaciones entre variables numéricas.

División Train/Test: dataset estratificado listo para modelado.

📊 Ejemplos de Gráficos

Sleep Duration vs Estrés

Physical Activity Level vs Estrés

Sleep Disorder vs Estrés

Matriz de correlación

(Estas imágenes son ejemplos; en tu repositorio puedes subir capturas de tus gráficos generados en Colab.)

💡 Conclusiones

Menos horas de sueño y menor actividad física aumentan el riesgo de estrés.

Trastornos del sueño se asocian a estrés alto.

El filtrado de outliers mejora la estabilidad del análisis.

La división estratificada asegura proporciones balanceadas en train/test.

🧰 Requisitos

Python 3.x

Librerías: pandas, numpy, matplotlib, seaborn, scikit-learn

Google Colab recomendado para ejecución y subida de archivos.

Instalación:

pip install pandas numpy matplotlib seaborn scikit-learn

⚡ Uso

Abrir notebook en Google Colab.

Ejecutar celda de subida de CSV y seleccionar el archivo descargado de Kaggle.

Ejecutar celdas en orden para realizar EDA, limpieza, visualización y división Train/Test.

Obtendrás train.csv y test.csv listos para modelado.
