# 📊 Dashboard Ventas Tech — Pipeline Completo de Datos

## Descripción
Proyecto de análisis de ventas end-to-end que simula el flujo de trabajo 
real de un Data Analyst: desde el almacén de datos hasta la visualización.

## Preview
<img width="873" height="625" alt="Dashboard_Ventas_Tech" src="https://github.com/user-attachments/assets/daa86e4c-5795-4580-84c4-712e429e9de5" />


## Pipeline del proyecto
1. **MySQL** — Base de datos relacional con 4 tablas relacionadas
2. **Python + mysql.connector** — Extracción de datos desde MySQL
3. **Pandas** — Limpieza, transformación y análisis
4. **Matplotlib + Seaborn** — Visualización en dashboard

## Modelo de datos
4 tablas relacionadas mediante claves foráneas:
- `clientes` — información de los 8 clientes
- `productos` — catálogo de 13 productos tecnológicos
- `categorias` — 5 categorías de productos
- `pedidos` — 30 transacciones con fecha, cantidad y descuento

## Análisis realizados
- Ingresos totales por categoría de producto
- Ranking de clientes por valor generado
- Evolución de ventas mes a mes
- Distribución de ingresos por segmento (Enterprise, SMB, Consumer)

## Principales hallazgos
- **Laptops** es la categoría con más ingresos (49% del total)
- **Ana Lopez** es la cliente más valiosa con 7.784€
- **Enterprise** representa el 47% de los ingresos totales
- Picos de ventas en **abril y diciembre**

## Tecnologías utilizadas
- Python 3.13
- Pandas
- Matplotlib
- MySQL + mysql.connector
- Jupyter Notebook
- DBeaver

## Autor
Julián Carnevale — Data Analyst en formación
