# 🛍️ Proyecto de Base de Datos: La Meva Botiga
![](https://media.tenor.com/67660YGQRV4AAAAM/squishiverse-squishie.gif)

[![MIT License](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![Made with MySQL](https://img.shields.io/badge/Database-MySQL-blue)](https://www.mysql.com/)
[![Contributors Welcome](https://img.shields.io/badge/Contributions-Welcome-brightgreen)](#contribuciones)

Este proyecto consiste en una base de datos que gestiona los productos y categorías de una tienda llamada **La Meva Botiga**. La base de datos está diseñada para almacenar y gestionar los datos relacionados con los productos disponibles en la tienda y sus respectivas categorías.

## 🚀 Características

- 📂 **Gestión de categorías**: Organiza tus productos por categorías.
- 🛒 **Productos detallados**: Almacena el nombre, descripción y precio de cada producto.
- 🔗 **Relaciones sólidas**: Tablas interrelacionadas para un manejo eficiente de los datos.
- 💾 **Escalable**: Compatible con otras tecnologías para ampliar funcionalidades.

---

## 📋 Tabla de Contenidos

- [Descripción](#-descripción)
- [Estructura de la Base de Datos](#-estructura-de-la-base-de-datos)
- [Instalación](#-instalación)
- [Uso](#-uso)
- [Contribuciones](#-contribuciones)
- [Licencia](#-licencia)

---

## 📚 Descripción

La base de datos almacena información sobre los productos y sus categorías. Está diseñada para un entorno de tienda en línea, aunque puede adaptarse a otras necesidades comerciales.

### Tablas principales

- **Categories**: Contiene información sobre las categorías de productos.
- **Productes**: Contiene información sobre los productos (nombre, descripción, precio, y la categoría a la que pertenecen).

---

## 🗂️ Estructura de la Base de Datos

### 🗃️ Categories
| Campo          | Tipo     | Descripción                                |
|----------------|----------|--------------------------------------------|
| `id`           | INT      | Identificador único de la categoría         |
| `nom`          | VARCHAR  | Nombre de la categoría                     |

### 🗃️ Productes
| Campo          | Tipo     | Descripción                                |
|----------------|----------|--------------------------------------------|
| `id`           | INT      | Identificador único del producto           |
| `nom`          | VARCHAR  | Nombre del producto                        |
| `descripció`   | TEXT     | Descripción detallada del producto         |
| `preu`         | DECIMAL  | Precio del producto                        |
| `categoria_id` | INT      | Identificador de la categoría del producto |

---

## 🛠️ Instalación

### Requisitos previos

- **Servidor de base de datos**: (como MySQL)
- **Lenguaje de programación**: PHP
- **Conexión a la base de datos**: Asegúrate de que tu aplicación esté correctamente conectada a la base de datos.

### Pasos para instalar

1. **Clona el repositorio**:
   ```bash
   git clone https://github.com/Ivanoviix/DAW-php-app.git
   cd DAW-php-app
![](https://c.tenor.com/AQM9IEdO0K8AAAAd/clone.gif?raw=true)
