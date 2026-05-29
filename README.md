# ProyectoRappiPlus
- Este repositorio contiene el proyecto final del curso de Tripleten- Proyecto RappiPlus: De datos a decisiones de negocio
Se trabaja con múltiples datasets del negocio:

    **rappiplus_orders_raw.csv** → información de pedidos, precios, descuentos y revenue
    **rappiplus_catalog.csv** → costos de productos, categorías y proveedores
    **rappiplus_marketing_spend.csv** → inversión en marketing por canal y país
    **events / users / user_activity (SQL)** → comportamiento del usuario dentro de la plataforma
    **experiment_checkout_ui.csv** → resultados de un experimento A/B en el checkout

# Análisis de una empresa de telecomunicaciones
## 📂 Contenido del repositorio

- `S12 Estudiante_Proyecto_Final.ipynb`
  → Notebook principal con limpieza, distribuciones, outliers, visualizaciones y conclusiones.

## ✪ Etapas Realizadas:

- Se limpiaron y estandarizaron los datos, eliminando inconsistencias y verificando la ausencia de duplicados y valores faltantes.
- Se hizo un análisis de la rentabilidad del negocio: Se calcularon ingresos totales, costo total, inversión en Marketing y margen sobre costos y marketing. También se calculó el ticket promedio por orden, la cantidad promedio de productos por orden, el gasto en marketing por canal y se encontró el producto más vendido
- Se construyó un funnel de conversión y se hizo un análisis de la conversión entre cada paso para encontrar en qué etapa se pierden más usuarios. Posteriormente se realizó la evaluación de la retención por cohortes.
- Se analizó mediante una prueba Chi-cuadrado si había o no diferencia entre las dos variantes del producto.
- Se realizó un dashboard ejecutivo en Tableau

## ▶ Cómo abrir el notebook en Google Colab

Haz clic en el siguiente botón:
[
[![Open In Colab]([https://colab.research.google.com/assets/colab-badge.svg](https://colab.research.google.com/drive/1HTskTYfvnnDxVyV9DHO5PXQZklvajdPK?usp=sharing))]

O:

1. Abre el archivo `.ipynb` en GitHub
2. Haz clic en **Open in Colab**

## 📘 Cómo reproducir el análisis

1. Abre `S12 Estudiante_Proyecto_Final.ipynb`
2. Ejecuta las celdas en orden (tal vez haya que cambiar el path del dataset porque es relativo)
3. El notebook carga 3 datasets que incluí en /data/

## 🧠 Objetivo del análisis

- Identificar problemas de calidad de datos
- Analizar la rentabilidad del negocio
- Analizar el funnel y cohortes
- Analizar dos variantes del producto para ver si vale la pena cambiarlo por la segunda versión
- Visualizaciones del análisis mediante un dashboard ejecutivo en Tableau
- Generar insights a lo largo del proyecto
