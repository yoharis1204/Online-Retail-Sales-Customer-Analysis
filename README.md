# Online-Retail-Sales-Customer-Analysis

# 📊 Análisis de ventas y comportamiento de clientes

Este proyecto analiza los datos de ventas de una tienda minorista en línea para **evaluar el desempeño comercial, identificar productos y mercados relevantes, analizar devoluciones y segmentar clientes mediante RFM**. El objetivo es obtener **insights basados en datos** que apoyen decisiones sobre ventas, productos y fidelización de clientes.

## 🛠️ Herramientas y tipo de proyecto

![Python](https://img.shields.io/badge/Python-357ebd?style=for-the-badge\&logo=python\&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-357ebd?style=for-the-badge\&logo=pandas\&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-357ebd?style=for-the-badge\&logo=numpy\&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-357ebd?style=for-the-badge\&logo=matplotlib\&logoColor=white)
![RFM](https://img.shields.io/badge/RFM_Analysis-295F98?style=for-the-badge)
![Data Analysis](https://img.shields.io/badge/Data_Analysis-295F98?style=for-the-badge)

**Tipo de proyecto:** Análisis exploratorio de datos y segmentación de clientes.

## 🎯 Preguntas clave

1. ¿Cuál es el comportamiento de las ventas a lo largo del tiempo?
2. ¿Qué países generan mayores ingresos?
3. ¿Cuáles son los productos con mayor volumen de ventas e ingresos?
4. ¿Cuál es la tasa de devoluciones y qué productos presentan más devoluciones?
5. ¿Qué segmentos de clientes tienen mayor valor según el análisis RFM?

## 🔎 Metodología

* **Limpieza de datos:** tratamiento de valores nulos, duplicados, devoluciones y valores atípicos.
* **Transformación:** creación de variables temporales y cálculo de `TotalVenta`.
* **Análisis comercial:** ventas, pedidos, productos, países y evolución mensual.
* **Análisis de devoluciones:** cálculo de la tasa de devolución e identificación de productos con mayor incidencia.
* **Segmentación RFM:** clasificación de clientes según **Recency, Frequency y Monetary**.
* **Visualización:** representación gráfica de los principales indicadores y patrones encontrados.

## 📈 Principales resultados

* **Ventas brutas:** £10,642,110.80
* **Ventas netas:** £9,726,006.95
* **Pedidos:** 25,900
* **Unidades vendidas:** 5,162,502
* **Clientes identificados:** 4,372
* **Tasa de devolución:** 8,40%
* **Principal mercado:** Reino Unido
* **Mes con mayores ventas:** noviembre de 2011

### 🔄 Devoluciones

Los productos con mayor cantidad de unidades devueltas fueron **PAPER CRAFT, LITTLE BIRDIE (80.995)**, **MEDIUM CERAMIC TOP STORAGE JAR (74.494)** y **printing smudges/thrown away (19.200)**.

### 👥 Segmentación de clientes

El análisis **RFM** permitió identificar clientes según su **recencia, frecuencia y valor monetario**, facilitando la identificación de clientes de alto valor y oportunidades de fidelización y reactivación.

## 💡 Recomendaciones

* Priorizar estrategias de fidelización para clientes de alto valor.
* Revisar los productos con mayor cantidad de devoluciones.
* Optimizar inventario para productos de alta rotación.
* Analizar oportunidades de crecimiento en mercados secundarios.
* Utilizar los patrones de ventas para mejorar la planificación comercial.

## 📚 Diccionario de datos

* `InvoiceNo`: número de factura.
* `StockCode`: código del producto.
* `Description`: descripción del producto.
* `Quantity`: cantidad comprada o devuelta.
* `InvoiceDate`: fecha de la transacción.
* `UnitPrice`: precio unitario.
* `CustomerID`: identificador del cliente.
* `Country`: país del cliente.
* `TotalVenta`: valor de la transacción (`Quantity × UnitPrice`).
