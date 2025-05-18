# 🏬 RetailSport - Análisis Predictivo de Ventas

Este proyecto analiza un conjunto de datos simulados para la empresa ficticia **RetailSport**, dedicada a la venta de artículos deportivos por canales físicos y digitales. El objetivo principal es comprender los factores que influyen en las ventas y construir modelos predictivos para apoyar la toma de decisiones estratégicas.

---

## 📊 Objetivos del proyecto

- Explorar y visualizar los datos históricos diarios.
- Identificar variables con mayor influencia en las ventas.
- Construir modelos de regresión lineal simple y múltiple.
- Comparar desempeño predictivo de los modelos.
- Generar visualizaciones mensuales de ventas e inventario.
- Proponer recomendaciones basadas en evidencia.

---

## 🧪 Estructura del análisis

### 1. **Preparación y exploración**
- Carga de datos simulados (5,000 registros diarios).
- Exploración inicial con `.head()`, `.info()`, `.describe()`.
- Histogramas, scatterplots y matriz de correlación.
- Pairplot de variables altamente correlacionadas.

### 2. **Modelado predictivo**
- **Regresión lineal simple**: `Ventas ~ Inventario`
- **Regresión lineal múltiple**: incluye todas las variables independientes.
- Evaluación mediante **R²** y **MSE**.

### 3. **Visualizaciones temporales**
- Evolución mensual de ventas y del inventario promedio.
- Identificación de patrones estacionales y caídas inusuales.

### 4. **Análisis e interpretación**
- Evaluación del impacto de cada variable en el modelo.
- Comparación entre canales de venta.
- Recomendaciones basadas en coeficientes e indicadores.

---

## 📈 Resultados clave

- Las variables con mayor impacto en las ventas son:
  - `Eventos_deportivos`, `Clima_favorable`, `Canal_ecommerce`.
- El modelo múltiple predice mucho mejor que el simple (**R²: 0.339 vs. 0.037**).
- Se observan picos de ventas a inicio y final de año.
- Las promociones tienen un efecto positivo débil.
- La rotación de inventario (días en stock) se relaciona negativamente con las ventas.

---

## 💡 Recomendaciones estratégicas

- Coordinar campañas promocionales con eventos deportivos.
- Priorizar el canal de ventas en línea con mejoras UX y mantenimiento preventivo.
- Implementar estrategias de descuentos en productos de baja rotación.
- Ajustar el stock con base en condiciones climáticas y temporadas pico.
- Utilizar modelos predictivos para planificación de inventario.

---

## 🛠️ Requisitos

- Python 3.13
- Bibliotecas:
  - pandas
  - numpy
  - matplotlib
  - seaborn
  - scikit-learn
---

## 📁 Archivos del proyecto

- `retail_sport.ipynb`: Notebook principal con análisis completo.
- `README.md`: Este documento.
- `ventas_simuladas.csv`
