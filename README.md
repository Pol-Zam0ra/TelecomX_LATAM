# 📊 Análisis de Evasión de Clientes – Telecom X

Este proyecto forma parte del reto de Data Science de Alura LATAM + Oracle One. El objetivo es analizar la evasión (churn) de clientes de la empresa ficticia Telecom X, identificar patrones relevantes y proponer acciones estratégicas para reducir la tasa de cancelación.

---

## 📌 Objetivo

Explorar y analizar un conjunto de datos de clientes de Telecom X para:

- Detectar perfiles con mayor probabilidad de cancelación.
- Comprender qué variables influyen en la evasión.
- Proporcionar información útil para modelos predictivos futuros.
- Comunicar hallazgos relevantes mediante visualizaciones claras.

---

## 📁 Estructura del proyecto
📦 TelecomX_Analysis/
├── 📄 telecom_final_limpio.json # Dataset ya transformado y limpio
├── 📄 TelecomX_EDA.ipynb # Notebook con el análisis completo
├── 📄 README.md # Este archivo

---

## 🧠 Tecnologías utilizadas

- Python 3.11+
- Pandas
- Matplotlib
- Seaborn
- Google Colab

---

## 🚀 Instrucciones de uso

1. Clona este repositorio o descarga el archivo ZIP.
2. Abre el notebook `TelecomX_EDA.ipynb` en Google Colab o Jupyter.
3. Ejecuta todas las celdas para:
   - Cargar el dataset
   - Aplicar limpieza y transformación
   - Generar visualizaciones
   - Leer conclusiones al final del informe

---

## 📊 Etapas del análisis

### 🔹 Extracción de datos
- Se cargó un archivo JSON con datos anidados desde una API simulada.

### 🔹 Limpieza y transformación
- Se eliminaron inconsistencias (espacios, mayúsculas, valores vacíos).
- Se estandarizaron columnas y se extrajeron variables clave.
- Se crearon nuevas columnas como `cuentas_diarias` y `servicios_activos`.

### 🔹 Análisis exploratorio
- Estadísticas descriptivas de las variables.
- Visualización de evasión por variables categóricas y numéricas.
- Análisis de correlación con `Churn`.

### 🔹 Informe final
- Resumen claro con insights clave y recomendaciones prácticas.

---

## 📈 Principales hallazgos

- Los clientes con **contrato mensual** tienen mayor probabilidad de cancelar.
- **No contar con soporte técnico** influye significativamente en la evasión.
- Los usuarios con **cargos diarios bajos** muestran una mayor tasa de churn.
- El análisis de correlación mostró relaciones útiles para futuros modelos predictivos.

---

## 💡 Recomendaciones

- Incentivar contratos anuales para fidelizar a los clientes.
- Mejorar el soporte técnico como servicio clave de retención.
- Identificar y segmentar usuarios con bajo consumo para ofrecerles promociones específicas.

---

## 👨‍💻 Autor

**Paul Vidal Zamora**  
Proyecto realizado como parte del Bootcamp Alura LATAM + Oracle ONE  

---

## ✅ Estado del proyecto

✔️ Proyecto completo y funcional  
✔️ Listo para revisión o evaluación técnica  
✔️ Apto para ser utilizado como parte de portafolio profesional
