# 📊 Alura Store - Data Analysis

Bienvenid@ al análisis de datos realizado como parte del primer desafío del curso de Ciencia de Datos.

Este proyecto analiza el desempeño de las tiendas de la cadena **Alura Store** con el objetivo de identificar cuál de ellas es la menos eficiente y recomendar cuál debería venderse para iniciar un nuevo emprendimiento.

---

## 📌 Objetivo

Evaluar el desempeño de las 4 tiendas de Alura Store utilizando métricas de ventas, reseñas y otros datos clave, con el fin de recomendar cuál tienda debería venderse.

---

## 🧠 Datos analizados

Los datos utilizados provienen de archivos CSV que contienen ventas de productos de las siguientes tiendas:

- Tienda 1
- Tienda 2
- Tienda 3
- Tienda 4

Cada archivo contiene información sobre:

- Producto
- Precio
- Categoría del Producto
- Costo de envío
- Calificación del cliente

---

## 📊 Métricas analizadas

Durante este análisis se evaluaron las siguientes métricas:

### 🔹 Ingresos Totales por Tienda
Suma de los ingresos generados por cada tienda.

### 🔹 Categorías Más Vendidas
Identificación de las categorías con más ventas por tienda.

### 🔹 Calificación Promedio
Promedio de las reseñas de los clientes por tienda.

### 🔹 Productos Más Vendidos
Los productos con mayores unidades vendidas.

### 🔹 Costo Promedio de Envío
Promedio del costo de envío por tienda.

---

## 📈 Visualizaciones

Se generaron múltiples gráficos para presentar los resultados de forma clara y visual:

- Gráfico de barras de ingresos totales por tienda
- Gráfico de barras de calificaciones promedio
- Gráfico de barras de costo de envío promedio
- Gráfico de barras de categorías más vendidas
- Gráfico circular de distribución de categorías

---

## 📊 Resultados principales

- ⭐ La Tienda 4 presenta el **menor ingreso total** entre las 4 tiendas.
- 📉 El desempeño de Tienda 4 es inferior, aun cuando su volumen de ventas es similar.
- 🚚 El costo de envío promedio y las calificaciones no son significativamente mejores que en las demás tiendas.
- 📦 En las demás tiendas hay categorías y productos que se destacan más claramente.

---

## 🎯 Recomendación final

Basándonos en:

- El menor ingreso total
- Ausencia de ventaja competitiva en categorías o productos
- Calificación del cliente similar al de otras tiendas

Se **recomienda vender la Tienda 4** de Alura Store, ya que muestra el menor rendimiento general en comparación con las demás.

---

## 🛠 Tecnologías y herramientas utilizadas

El análisis fue realizado utilizando:

- 🐍 Python
- 📚 Pandas (manipulación de datos)
- 📊 Matplotlib (visualizaciones)
- 🧠 Google Colab (entorno de desarrollo)

---

## 📁 Estructura del repositorio

alura-store-data-analysis/
│
├── .ipynb (Notebook con todo el análisis)
├── data/ (Carpeta con archivos .csv de cada tienda)
├── README.md (Este archivo)

## 📌 ¿Cómo ejecutar este proyecto?

1. Clona el repositorio:
```bash
git clone https://github.com/Narlemus/alura-store-data-analysis.git

Abre el notebook en Colab o Jupyter.

Ejecuta todas las celdas en orden para ver resultados y gráficos.

