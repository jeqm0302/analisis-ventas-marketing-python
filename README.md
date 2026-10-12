# Análisis de ventas y campañas de marketing con Python

Proyecto final de Data Analytics (Talento Tech): análisis de las ventas de un comercio integrando datos de transacciones, clientes y campañas de marketing.

[Abrir en Google Colab](https://colab.research.google.com/drive/1vLuuWQvc7_YYr7RZzRMkz4bBN7KybTh1?usp=sharing) · [Ver notebook con gráficos interactivos](https://nbviewer.org/github/jeqm0302/analisis-ventas-marketing-python/blob/main/analisis_ventas.ipynb)

## Pregunta

¿Qué productos sostienen la facturación del negocio y cómo se comportan las ventas a lo largo del tiempo?

## Datos

| Archivo | Contenido |
|---|---|
| `ventas.csv` | ~3.000 ventas: producto, precio, cantidad, fecha y categoría |
| `clientes.csv` | Clientes con edad, ciudad e ingresos |
| `marketing.csv` | Campañas: producto, canal, costo y fechas |

> Los datos son ficticios, provistos por el curso.

## Proceso

1. Carga y limpieza de los tres datasets (tipos de datos, formato de precios y fechas).
2. Integración de ventas con campañas de marketing.
3. Análisis exploratorio y visualizaciones con Matplotlib, Seaborn y Plotly.

## Resultados

- **Productos estrella:** las lámparas de mesa y los auriculares lideran el ranking de ingresos (Top 5) y son la base financiera del negocio.
- **Estacionalidad:** las ventas alcanzan su pico en mayo y caen en junio.

## Cómo ejecutarlo

```bash
git clone https://github.com/jeqm0302/analisis-ventas-marketing-python.git
cd analisis-ventas-marketing-python
pip install -r requirements.txt
jupyter notebook analisis_ventas.ipynb
```

## Estructura

```
├── data/
│   ├── clientes.csv
│   ├── marketing.csv
│   └── ventas.csv
├── analisis_ventas.ipynb
├── requirements.txt
└── README.md
```

## Herramientas

Python · pandas · NumPy · Matplotlib · Seaborn · Plotly · Google Colab

## Autor

**Jesús Enrique Quijada Martínez** · [LinkedIn](https://linkedin.com/in/jesúsenrique-quijada-martínez-57b70922b) · [GitHub](https://github.com/jeqm0302)