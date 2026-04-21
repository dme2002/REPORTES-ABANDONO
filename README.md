Proyecto de Análisis de Clientes y Automatización de Datos
Descripción del proyecto

Este proyecto se enfoca en el análisis del comportamiento de clientes en un conjunto de datos bancarios utilizando Python. Incluye procesos de limpieza de datos, automatización del procesamiento y generación de indicadores clave (KPIs) para identificar patrones relacionados con la pérdida de clientes, satisfacción y comportamiento financiero.

El objetivo es simular un flujo de trabajo real de análisis de datos combinando procesamiento, análisis exploratorio y generación de insights de negocio.

Objetivos
Automatizar la limpieza y preprocesamiento de datos
Analizar el comportamiento de clientes y patrones financieros
Identificar factores que influyen en la pérdida de clientes (churn)
Generar KPIs útiles para la toma de decisiones
Visualizar información mediante gráficos
Descripción del dataset

El dataset incluye las siguientes variables:

CustomerId (ID del cliente)
CreditScore (puntaje crediticio)
Geography (país)
Gender (género)
Age (edad)
Balance (saldo)
NumOfProducts (número de productos)
HasCrCard (tiene tarjeta de crédito)
IsActiveMember (cliente activo o no)
EstimatedSalary (salario estimado)
Exited (abandono del cliente)
Satisfaction Score (nivel de satisfacción)
Card Type (tipo de tarjeta)
Point Earned (puntos acumulados)
Tecnologías utilizadas
Python
Pandas
NumPy
Matplotlib
Jupyter Notebook
Flujo del proyecto
1. Carga de datos

Importación y revisión del dataset.

2. Limpieza de datos
Eliminación de duplicados
Manejo de valores nulos
Estandarización de columnas
3. Automatización del procesamiento

Creación de funciones reutilizables para limpiar y transformar datos automáticamente.

4. Análisis exploratorio de datos (EDA)
Distribución de clientes
Análisis financiero
Comportamiento de abandono
5. Generación de KPIs

Cálculo de métricas clave para análisis de negocio.

6. Visualización de datos

Creación de gráficos para representar los insights.

KPIs principales
Tasa de abandono de clientes (Churn Rate)
Edad promedio de clientes
Saldo promedio
Puntaje crediticio promedio
Nivel de satisfacción promedio
Distribución de clientes por país
Clientes activos vs inactivos
Productos por cliente
Churn por país
Correlación entre variables
Insights principales
La tasa de abandono está relacionada con la satisfacción del cliente
Los clientes inactivos tienen mayor probabilidad de abandonar el banco
Existen diferencias de comportamiento entre países
Variables financieras como saldo y productos influyen en la retención
Automatización
Pipeline automático de limpieza de datos
Funciones reutilizables para procesamiento
Generación automática de KPIs
Optimización del tiempo de análisis
Cómo ejecutar el proyecto
Clonar el repositorio
Instalar dependencias:
pip install pandas numpy matplotlib
Abrir Jupyter Notebook:
jupyter notebook
Ejecutar todas las celdas en orden
Futuras mejoras
Implementar modelo de Machine Learning para predicción de churn
Crear dashboard en Power BI
Añadir visualizaciones interactivas
Mejorar ingeniería de características
Autor

David Meza
Estudiante de Ingeniería en Sistemas
Enfoque en análisis de datos, automatización y desarrollo de software

Nota

Este proyecto forma parte de un portafolio personal orientado a demostrar habilidades en análisis de datos, automatización y visualización con Python.
