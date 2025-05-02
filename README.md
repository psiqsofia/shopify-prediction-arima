# 📈 Predicción de Acciones de Shopify con ARIMA

Este proyecto aplica un modelo ARIMA para analizar y predecir el comportamiento del precio de las acciones de Shopify, utilizando datos diarios de 2015 a 2025.

---

## 🔍 Objetivo

- Analizar el histórico de precios de cierre de las acciones de Shopify.
- Ajustar un modelo ARIMA para predicción.
- Estimar los precios para los próximos 10 días hábiles.
- Visualizar y entender la tendencia general.

---

## 📊 Dataset

- `historico.csv`: Datos históricos de las acciones (`date`, `close`).
- `forecast.csv`: Predicciones generadas para los siguientes 10 días (`date`, `predicted_close`).

Fuente de los datos: Kaggle.

---

## 🧪 Metodología

1. Limpieza y exploración de datos.
2. Visualización de tendencias con medias móviles (MA20 y MA50).
3. Modelado ARIMA(2,1,1) con `statsmodels`.
4. Predicción de los próximos 10 días hábiles.
5. Exportación de los resultados a CSV.

---

## 📷 Ejemplo de visualización

![Predicción de precios futuros](images/prediccion_shopify.png)

---

## 🛠 Herramientas utilizadas

- Python (Pandas, Matplotlib, Statsmodels)
- Jupyter Notebook
- Git & GitHub

---

## 🚀 Cómo reproducir

1. Clona el repositorio:
```bash
git clone https://github.com/tu-usuario/shopify-prediccion-arima.git
