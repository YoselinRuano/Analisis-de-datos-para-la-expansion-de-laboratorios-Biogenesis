# Analisis-de-datos-para-la-expansion-de-laboratorios-Biogenesis
	🔍 El objetivo de este proyecto es generar insights que permitan identificar ubicaciones estratégicas para nuevos laboratorios, optimizando la disponibilidad de vacunas y fortaleciendo la capacidad de respuesta ante futuras emergencias sanitarias.
 
📌 Descripción
Biogénesis es una empresa farmacéutica comprometida con la expansión y modernización de laboratorios dedicados a la producción de vacunas en Latinoamérica. Esta iniciativa surge como respuesta a la pandemia de COVID-19, la cual expuso las vulnerabilidades de los sistemas de salud y las cadenas de suministro farmacéuticas a nivel mundial, siendo América Latina una de las regiones más afectadas debido a factores como la alta densidad poblacional, desigualdades socioeconómicas y sistemas de salud fragmentados.

📌Dataset
Para este estudio se utilizó un dataset compuesto por 12,216,057 filas y 50 columnas con información relevante de distintos países de Latinoamérica. Se realizó un filtrado específico para los países de interés: Argentina, Chile, México, Perú y Brasil.

📌Herramientas utilizadas
Para el análisis de datos se implementaron las siguientes librerías de Python:

📌python

Se utilizaron las siguientes librerias
 🔖pandas as pd,  para  Manipulación y análisis de datos tabulares  🔖numpy as np, para Operaciones matemáticas y arreglos numéricos 🔖matplotlib.pyplot as plt, para Generación de gráficos
 🔖seaborn as sns, para Visualización avanzada de datos

📌Proceso de Análisis

Carga de Datos
Se utilizó pd.read_csv() para leer los datos.
Se verificaron las columnas disponibles y se aplicaron filtros por fechas y países relevantes para la empresa.
Limpieza y Normalización
Se llevó a cabo la imputación de valores nulos mediante fillna(...) de pandas, con el argumento inplace=True para modificar el DataFrame original.
Se monitorearon advertencias generadas por esta operación.
Se verificó la cantidad de valores limpios tras la imputación.
Cálculo de Estadísticas Descriptivas
Se emplearon bucles for y/o while para automatizar el cálculo de métricas básicas como:
Tendencia central (media, mediana)
Dispersión (desviación estándar, rango)
Valores mínimos y máximos
Estas métricas son clave para:
Identificar datos atípicos o errores (e.g., valores negativos).
Entender la representatividad de los datos.
Validar la amplitud y consistencia de la información.

📌Conclusión
Este proyecto constituye el primer avance en el análisis de datos orientado a la expansión estratégica de laboratorios farmacéuticos en la región. A través de la identificación de patrones y la generación de insights, Biogénesis podrá optimizar su capacidad de respuesta ante pandemias y mejorar el acceso a vacunas para la población latinoamericana.


