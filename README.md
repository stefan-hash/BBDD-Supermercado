Descripción del proyecto
 Durante mis prácticas empresariales, desarrollé una base de datos relacional completa para un supermercado ficticio que incluye productos, categorías, marcas, eventos, proveedores y sistema de subastas. 
 El objetivo fue estructurar y optimizar la gestión de información para poder conectar la base de datos al videojuego que estaba desarollando la empresa.

# 🛒 Supermercado DB — Sistema de Gestión Comercial

Este proyecto fue desarrollado durante mis prácticas empresariales y representa una simulación completa de la base de datos de un supermercado moderno. Incluye la gestión de productos generales, pescadería, eventos, marcas, IVA, categorías y proveedores.

## 📦 Características principales

- Estructura relacional con más de 12 tablas conectadas
- Clasificación de artículos por tipo, marca y categoría
- Control de stock y calendario de disponibilidad para productos del mar
- Integración de IVA según tipo de producto
- Eventos automovilísticos gestionados con ubicación y fechas
- Subastas conectadas a productos de pescadería

## 🧠 Modelo relacional

La base de datos sigue principios de normalización y eficiencia:
- `productos`: productos generales
- `pescaderia`: productos marinos con técnica de pesca y subasta
- `eventos del motor`: ferias y exposiciones con sistema de venta
- `categoria`, `marca`, `iva`: información clasificatoria
- `proveedor`, `subastapescado`: datos externos relacionados

## 🛠️ Tecnologías usadas

- **MySQL** y exportación JSON desde **phpMyAdmin**
- Datos ficticios estructurados para consultas SQL
- Preparado para integrarse con backend en PHP o Java

## 📂 Archivo JSON

> Puedes descargar la base de datos en formato `.json` para visualización o carga:

[📥 supermarket.json](docs/supermercado.json)

## 👨‍💻 Autor

**Stefan Liviu Goran**  
Técnico Superior en Desarrollo de Aplicaciones Multiplataforma  
📧 [stefangoran61@gmail.com](mailto:stefangoran61@gmail.com)


