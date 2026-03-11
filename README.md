# 📊 Challenge - Telecom X Análisis de Evasión de Clientes

Este proyecto tiene como objetivo analizar los factores que influyen en la **evasión de clientes** en la empresa ficticia **Telecom X**. El análisis permite extraer insights clave para desarrollar estrategias de retención y preparar modelos predictivos que identifiquen a clientes en riesgo de cancelar el servicio.

---

## 🧠 Objetivo

- Comprender el comportamiento de los clientes que cancelan su servicio.
- Identificar patrones asociados con el churn (evasión).
- Visualizar relaciones entre variables demográficas, financieras y contractuales.
- Ofrecer recomendaciones estratégicas al equipo de negocios y data science.

---

## 📁 Estructura del Proyecto

```
📦 TelecomX/
│
├── TelecomX_Data.json            # Datos originales en formato JSON
├── TelecomX_diccionario.md       # Diccionario de datos con definición de columnas
├── TelecomX_Analisis_Churn.ipynb # Notebook principal con todo el flujo de análisis
├── README.md                     # Descripción general del proyecto
```

---

## 📊 Ejemplos de Gráficos e Insights

- **Gráfico 1: Distribución de Churn**
  - Aproximadamente **27%** de los clientes cancelaron su servicio.

- **Gráfico 2: Churn por Tipo de Contrato**
  - Contratos mensuales presentan tasas de evasión mucho más altas que los contratos anuales.

- **Gráfico 3: Cargos Mensuales vs Churn**
  - Clientes que pagan más de **$70 al mes** tienden a cancelar con más frecuencia.

- **Insight clave**: La combinación de **contratos flexibles + cargos altos + pagos manuales** representa un perfil de riesgo.

---

## ⚙️ Instrucciones para Ejecutar el Notebook

Este proyecto puede ejecutarse en diferentes entornos:

### ▶️ 1. Google Colab (Recomendado para uso rápido en la nube)

- Sube los archivos `.ipynb`, `.json` y `.md` a tu Google Drive.
- Abre el archivo `TelecomX_Analisis_Churn.ipynb` con Colab.
- Ejecuta cada celda secuencialmente.

### 💻 2. Jupyter Notebook (Anaconda o local)

- Asegúrate de tener Python 3.7+ y Jupyter instalado. Puedes usar Anaconda o instalar con pip:

```bash
pip install pandas seaborn matplotlib notebook
```
