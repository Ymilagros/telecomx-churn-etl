# telecomx-churn-etl

# 📊 TelecomX Churn — ETL + EDA

Este proyecto tiene como objetivo **extraer, transformar y analizar datos** de clientes de TelecomX, con el fin de detectar factores relacionados con la **evasión de clientes (churn)**.  

El pipeline incluye:  
- **ETL (Extract, Transform, Load)** → limpieza y procesamiento de datos.  
- **EDA (Exploratory Data Analysis)** → análisis exploratorio para encontrar patrones de churn.  
- **Visualización y reportes** para la toma de decisiones.  

---


---

## 📑 Archivos principales

### 📁 `data/`
- **TelecomX_Data.json** → dataset original en bruto.  
- **TelecomX_LATAM.ipynb** → notebook preliminar con pruebas de EDA.  
- **TelecomX_diccionario.md** → diccionario con definición de campos (ej: churn_flag, tenure, contract, etc.).  
- **telecomx_churn_clean.csv** → dataset ya procesado y listo para análisis.

### 📁 `notebooks/views/`
- **etl_churn.ipynb** → notebook principal donde se hace ETL, limpieza, generación de features y análisis de churn.

### 📁 `reports/`
- Carpeta reservada para guardar resultados de análisis, gráficas y reportes finales.

### 📁 `src/`
- Scripts Python para ETL y análisis modular (ejemplo: funciones de carga, limpieza y visualización).

---

## 🚀 Cómo ejecutar el proyecto

1. Clonar este repositorio:  
   ```bash
   git clone https://github.com/Ymilagros/telecomx-churn-etl.git
   cd telecomx-churn-etl

📊 Objetivos de análisis

Calcular tasa de churn (%).

Identificar el tipo de contrato y método de pago con mayor churn.

Explorar relación entre churn y variables demográficas (edad, género, dependientes).

Visualizar métricas clave para la toma de decisiones.

✍️ Autor: Ymilagros


