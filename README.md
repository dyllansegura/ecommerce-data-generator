ENG. README Version 1.

E-Commerce Synthetic Data Generator

This is a Python project that generates synthetic e-commerce data using probabilistic distributions, business rules, and relationships between customers, products, and orders. The goal is to create a structured and reproducible dataset that can be used for database practice and data analysis.

Project Overview

This project simulates an e-commerce business by generating three related datasets:

+ **Orders:** transaction dates, products, quantities, prices, payment methods, order sizes, and customer segments.
+ **Customers:** customer classifications, ages, genders, countries, and signup dates.
+ **Products:** product names, categories, subcategories, base prices, and price ranges.

The generated data covers a simulated period from 2021 to 2025 and incorporates different purchasing patterns to make the dataset more useful for analytical exercises.

Key Features

+ **Synthetic data generation:** creates artificial customer, product, and order records.
+ **Reproducibility:** uses a fixed random seed for consistent results when the same code and environment are used.
+ **Probabilistic distributions:** assigns customer classes, countries, payment methods, and other attributes using weighted probabilities.
+ **Relational data modeling:** connects orders with customers and products through identifiers.
+ **Business rules:** introduces relationships between product prices, quantities, seasonal periods, and purchasing behavior.
+ **Data transformation:** uses Pandas to merge, transform, classify, and organize data.
+ **Excel export:** saves the generated datasets into separate worksheets in a single Excel workbook.

Technologies

+ Python
+ Pandas
+ NumPy
+ Random
+ Datetime

Future Improvements

+ Improving code organization and modularity.
+ Strengthening data validation and referential integrity.
+ Refining date generation and purchasing distributions.
+ Improving customer segmentation logic.
+ Integrating the generated data into MySQL.
+ Developing Power BI dashboards and analytical reports.

Disclaimer

All records are synthetically generated for educational and portfolio purposes. They do not represent actual transactions, customers, or business performance.

Author

**Dyllan Segura**

Industrial Physics Engineer | Python | Data Modeling | Scientific and Quantitative Problem-Solving

#####################################################################################################

ES. README Versión 1.

Generador de Datos Sintéticos para E-Commerce

Este es un proyecto en Python que genera datos sintéticos de comercio electrónico mediante distribuciones probabilísticas, reglas de negocio y relaciones entre clientes, productos y pedidos. El objetivo es crear un conjunto de datos estructurado y reproducible que pueda utilizarse para practicar bases de datos y análisis de datos.

Descripción del proyecto

El proyecto simula el funcionamiento de un negocio de comercio electrónico mediante la generación de tres conjuntos de datos relacionados:

+ **Pedidos (`orders`):** fechas de transacción, productos, cantidades, precios, métodos de pago, tamaños de pedido y segmentos de clientes.
+ **Clientes (`customers`):** clasificación de clientes, edades, géneros, países y fechas de registro.
+ **Productos (`products`):** nombres, categorías, subcategorías, precios base y rangos de precios.

Los datos representan un periodo simulado de 2021 a 2025 e incorporan diferentes patrones de compra para facilitar ejercicios de análisis.

Características principales

+ **Generación de datos sintéticos:** creación artificial de registros de clientes, productos y pedidos.
+ **Reproducibilidad:** uso de una semilla aleatoria fija para obtener resultados consistentes al ejecutar el mismo código en condiciones equivalentes.
+ **Distribuciones probabilísticas:** asignación de clases de clientes, países, métodos de pago y otros atributos mediante probabilidades ponderadas.
+ **Modelado de datos relacionales:** conexión de pedidos con clientes y productos mediante identificadores.
+ **Reglas de negocio:** incorporación de relaciones entre precios, cantidades, temporadas y comportamiento de compra.
+ **Transformación de datos:** uso de Pandas para combinar, transformar, clasificar y organizar la información.
+ **Exportación a Excel:** almacenamiento de las tablas generadas en hojas separadas dentro de un mismo archivo.

Tecnologías utilizadas

+ Python
+ Pandas
+ NumPy
+ Random
+ Datetime

Mejoras futuras

+ Mejorar la organización y modularidad del código.
+ Fortalecer la validación de datos y la integridad referencial.
+ Refinar la generación de fechas y las distribuciones de compra.
+ Mejorar la lógica de segmentación de clientes.
+ Integrar los datos generados con MySQL.
+ Desarrollar dashboards y reportes analíticos en Power BI.

Aviso

Todos los registros se generan artificialmente con fines educativos y de portafolio. No representan transacciones, clientes ni resultados comerciales reales.

Autor

**Dyllan Segura**

Ingeniero Físico Industrial | Python | Modelado de Datos | Resolución de Problemas Científicos y Cuantitativos

