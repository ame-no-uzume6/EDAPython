# 🌍 Análisis de Emisiones de CO₂ por País y Región

Este proyecto realiza un **análisis exploratorio de datos (EDA)** sobre un conjunto de datos de emisiones de dióxido de carbono (CO₂) a nivel mundial.  
El objetivo es limpiar, transformar y visualizar la información para comprender las tendencias globales, regionales y per cápita de las emisiones.

---

## 📘 Contenido del proyecto

- **Limpieza de datos:**  
  - Renombrado de columnas para mayor claridad.  
  - Eliminación de valores nulos.  
  - Conversión de formatos numéricos europeos (`,` → `.`).  
- **Análisis descriptivo:**  
  - Medidas estadísticas (media, mediana, moda, desviación estándar, varianza, rango).  
  - Frecuencias absolutas, relativas y acumuladas por región.  
- **Visualización de datos:**  
  - Gráficos de barras y de torta (pie chart) por región.  
  - Gráfico de tendencia de emisiones totales por año.  
  - Distribución de emisiones per cápita.  
  - Comparación de emisiones promedio entre regiones.  
- **Exportación:**  
  - Guarda el dataset limpio y las tablas de frecuencia en Google Drive.

---

## 🧠 Librerías utilizadas

El análisis fue desarrollado en **Google Colab** con las siguientes librerías:

- pandas
- numpy
- matplotlib
- seaborn

---

## 🚀 Ejecución del notebook

- Abrir en Google Colab:

  - Sube el notebook o ábrelo directamente desde tu Drive.

  - Asegúrate de tener el archivo Emisiones_CO2.csv en tu ruta: /content/drive/MyDrive/Agrega_Tu_Ruta_Aqui/Emisiones_CO2.csv

- Montar Google Drive:

  from google.colab import drive
  drive.mount('/content/drive')


- Ejecutar las celdas secuencialmente.
  
  Se generarán gráficos y estadísticas automáticas.

- Salida esperada:

  - Dataset limpio (Emisiones_CO2_limpio.csv)

  - Tabla de frecuencias (frecuencia_region.csv)

  - Gráficos visuales de análisis

---

## 📊 Ejemplos de visualizaciones

- Frecuencia absoluta por región

- Distribución relativa (%)

- Tendencia anual de emisiones


## 📈 Métricas de resumen por región

El notebook genera una tabla con estadísticas descriptivas de emisiones promedio, mediana y desviación estándar, tanto en valores totales (co2_kt) como per cápita (co2_per_capita).

## 💾 Guardado de resultados

El script guarda automáticamente los archivos procesados en tu Google Drive:

- Dataset limpio:
/content/drive/MyDrive/Agrega_Tu_Ruta_Aqui/Emisiones_CO2_limpio.csv

- Tabla de frecuencia:
/content/drive/MyDrive/Agrega_Tu_Ruta_Aqui/frecuencia_region.csv

## 🧩 Autor
**Claudia Elisette Urbina Guiñez**
📍 Santiago, Chile
🎓 Estudiante de Programación con mención en Análisis de Datos en Fundación Soymás
📧 claudia.urbina2025@soymas.cl
🔗 [Linkedin](www.linkedin.com/in/claudia-urbina-guiñez)
