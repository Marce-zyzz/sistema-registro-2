# 📊 Análisis de Ventas por Tienda

Este proyecto analiza y visualiza información de ventas provenientes de diferentes tiendas con el objetivo de brindar una recomendación comercial al Sr. Juan sobre cuál es la tienda ideal para vender sus productos.

## 🔍 Descripción

A través de técnicas de análisis exploratorio de datos (EDA) y visualización, se examinan diferentes variables que influyen en el rendimiento de cada tienda, incluyendo:

- Ingresos totales por tienda
- Calificación promedio de los clientes
- Costos promedio de envío
- Ventas por categoría y producto
- Productos más y menos vendidos
- Distribución geográfica de las ventas

## 📈 Visualizaciones

El proyecto incluye diferentes tipos de visualizaciones generadas con:
- `matplotlib`
- `seaborn` para gráficos estáticos(extra)
- `folium` para mapas interactivos(extra)

Se utilizan gráficos de barras, pastel, mapas de calor, dispersión geográfica, y visualizaciones interactivas con clusters y heatmaps.

## 🧭 Recomendación Comercial

Con base en los datos analizados, se emite una recomendación al Sr. Juan sobre la tienda con mejores condiciones para vender, considerando factores como:

- Nivel de ingresos
- Buena reputación (calificación alta)
- Costos de envío accesibles
- Ubicación estratégica y volumen de ventas

## 🚀 Cómo usar este proyecto

1. Cloná el repositorio o abrí el notebook en Google Colab.
2. Ejecutá el archivo `.ipynb` paso a paso.
3. Observá las visualizaciones y leé la conclusión para tomar decisiones basadas en datos.

## 🛠️ Requisitos

Este proyecto utiliza las siguientes bibliotecas de Python:

```bash
pip install pandas matplotlib seaborn folium

Estructura del proyecto
├── datos/                  # Archivos CSV o Excel con los datos de ventas
├── visualizaciones/        # Capturas o ejemplos de gráficos generados
├── analisis_tiendas.ipynb  # Notebook principal del proyecto
└── README.md               # Este archivo

