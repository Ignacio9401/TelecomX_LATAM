

# 📊 Telecom X – Análisis de Churn de Clientes

## 📝 Descripción del Proyecto
Telecom X es una empresa de telecomunicaciones que enfrenta un alto índice de evasión de clientes (Churn).  
El objetivo de este proyecto es analizar los datos de los clientes para identificar patrones de abandono y proporcionar información clave para reducir la evasión.

El proyecto sigue un flujo ETL completo:  
1. **📌 Extracción**: Carga de datos desde un archivo JSON.  
2. **🔧 Transformación**: Limpieza de datos, manejo de duplicados y valores nulos.  
3. **📊 Carga y Análisis**: Exploración de datos, gráficos de Churn y preparación del CSV limpio.  
4. **📄 Informe Final**: Conclusiones, patrones detectados y recomendaciones estratégicas.

---

## 🛠 Tecnologías Utilizadas
- Python 3.x  
- Pandas  
- Matplotlib  
- Seaborn  
- Google Colab  

---

## 📁 Estructura de Archivos


/content/
├── TelecomX_Data.json # JSON original con los datos de clientes
├── churn_limpio.csv # CSV limpio generado para análisis predictivo
└── proyecto_Churn.ipynb # Notebook con todo el flujo ETL y análisis


---

## 🚀 Flujo del Proyecto

### 1️⃣ Extracción
- Carga del JSON con los datos de clientes.  
- Creación de un DataFrame de Pandas para manipulación y análisis.  

### 2️⃣ Transformación
- Eliminación de duplicados.  
- Manejo de valores nulos (0 para numéricos, "Desconocido" para categóricos).  
- Conversión de columnas con diccionarios/listas a strings.  
- Normalización de nombres de columnas (minúsculas y sin espacios).

### 3️⃣ Carga y Análisis
- Distribución general de Churn.  
- Gráficos exploratorios:  
  - Churn por tipo de plan  
  - Edad vs Churn  
  - Heatmap de correlaciones entre variables numéricas  
- Generación del CSV limpio `churn_limpio.csv` listo para análisis predictivo.

### 4️⃣ Informe Final
- Resumen ejecutivo y distribución de Churn.  
- Variables que influyen en la evasión de clientes.  
- Patrones detectados y recomendaciones estratégicas.

---

## 📌 Conclusiones
- Aproximadamente **1 de cada 4 clientes está en riesgo de evasión**.  
- **Clientes jóvenes con planes básicos** son más propensos a abandonar.  
- **Clientes con servicios combinados** permanecen más tiempo.  
- Se recomienda:  
  - Focalizar campañas de retención.  
  - Ofrecer incentivos a clientes en riesgo.  
  - Mantener los datos limpios y actualizados para análisis predictivo.

---

## ⚡ Cómo Ejecutar
1. Abrir el notebook `proyecto_Churn.ipynb` en Google Colab.  
2. Ejecutar los bloques de **Extracción → Transformación → Carga y Análisis → Informe Final**.  
3. Visualizar gráficos y descargar `churn_limpio.csv` para análisis predictivo.# TelecomX_LATAM
