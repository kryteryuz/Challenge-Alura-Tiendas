# Alura Store 📊🛍️

![Portada](assets/alura-store-cover.png)

## Insignias

[![Estado del Proyecto](https://img.shields.io/badge/estado-en%20desarrollo-blue)](https://github.com/tu_usuario/alura-store)  
[![Licencia](https://img.shields.io/badge/licencia-MIT-green)](https://opensource.org/licenses/MIT)

## Índice

1. [Descripción del Proyecto](#descripción-del-proyecto)
2. [Estructura del Proyecto](#estructura-del-proyecto)
3. [Ejemplos de Gráficos e Insights](#ejemplos-de-gráficos-e-insights)
4. [Instrucciones para Ejecutar](#instrucciones-para-ejecutar)
5. [Tecnologías Utilizadas](#tecnologías-utilizadas)
6. [Personas Contribuyentes](#personas-contribuyentes)
7. [Personas Desarrolladoras del Proyecto](#personas-desarrolladoras-del-proyecto)
8. [Licencia](#licencia)

---

## Descripción del Proyecto

**Alura Store** es un proyecto de análisis de datos enfocado en el rendimiento comercial de una tienda online. A partir de los datos de ventas, productos, clientes y tiendas, se busca obtener insights que ayuden a la toma de decisiones estratégicas.

El propósito del análisis es identificar:
- Comportamiento de ventas por tienda y categoría
- Productos más y menos vendidos
- Envíos promedio por tienda
- Calificación general de las tiendas
- Patrones geográficos de desempeño con visualización interactiva

---

## Estructura del Proyecto

alura-store/
│
├── data/ # Archivos CSV con los datos de entrada
│ ├── orders.csv
│ ├── products.csv
│ └── customers.csv
│
├── assets/ # Imágenes y recursos multimedia (gráficos y portada)
│ └── ...
│
├── folium_map.html # Mapa interactivo generado con Folium
│
├── Alura_Store_Analysis.ipynb # Notebook principal del análisis
│
└── README.md # Este archivo


---

## Ejemplos de Gráficos e Insights

### 🧾 1. Análisis de facturación por tienda
Se identificaron tiendas con ingresos superiores a otras. Por ejemplo, la tienda **Store A** generó S/. 123,450.00, mientras que **Store C** solo alcanzó S/. 45,600.00.

![Factura por tienda](assets/facturacion.png)

---

### 🛒 2. Ventas por categoría
Las categorías **Electrónica** y **Hogar** dominan en volumen de ventas, mientras que otras como **Juguetería** y **Libros** son marginales.

![Ventas por categoría](assets/categorias.png)

---

### ⭐ 3. Calificación promedio por tienda
La tienda **Store B** destaca con una calificación promedio de **4.5**, mostrando un excelente nivel de satisfacción del cliente.

---

### 🔼🔽 4. Productos más y menos vendidos
Identificamos productos como “Auriculares Bluetooth” en el top de ventas, mientras que productos como “Webcam HD” apenas registraron movimiento.

---

### 🚚 5. Envío promedio por tienda
El tiempo de entrega promedio es de 6.2 días. La tienda **Store D** destaca con entregas más rápidas, de solo 4.8 días promedio.

---

### 🗺️ 6. Mapa interactivo de tiendas (Folium)
Se generó un mapa con **Folium** para visualizar el desempeño por ubicación geográfica. Haz zoom, clic en los marcadores y explora los insights.

🔗 [Ver el mapa interactivo](folium_map.html)

---

## Tecnologías utilizadas

- **Python 3**: Lenguaje principal.
- **Pandas**: Manejo de datos tabulares.
- **Matplotlib y Seaborn**: Visualizaciones estadísticas.
- **Folium**: Visualizaciones geográficas interactivas.

---

## Personas Contribuyentes

Este proyecto es completamente gestionado por el desarrollador principal. Sin embargo, si alguna persona decide contribuir en el futuro, se listarán aquí.

---

## Personas Desarrolladoras del Proyecto

- **Bryan Vera** - Desarrollador principal del proyecto.

---

## Licencia

Este proyecto está bajo la Licencia MIT. Puedes leer el texto completo de la licencia en [LICENSE](LICENSE).
