# 🚀 TechStore - E-commerce Workshop

¡Bienvenido a **TechStore**! Este es un proyecto desarrollado para el taller de **Diseño y creación de páginas web para negocios digitales**. Se trata de una aplicación web dinámica construida con el stack de Node.js, enfocada en la escalabilidad y la experiencia de usuario.

## 🛠️ Tecnologías Utilizadas

* **Backend:** Node.js & Express
* **Frontend:** EJS (Embedded JavaScript templates) & Bootstrap 5
* **Herramientas de Desarrollo:** Nodemon para reinicio automático del servidor

## 🌟 Características Actuales

* **Navegación Dinámica:** Rutas configuradas para filtrar productos por categorías (Computadores y Periféricos).
* **Motor de Plantillas:** Uso de EJS para renderizar datos dinámicos desde el servidor.
* **Diseño Responsivo:** Interfaz moderna y adaptable gracias a Bootstrap.
* **Vista de Detalles:** Página dedicada para mostrar información completa de cada producto.
* **Identificación Única:** Cada producto tiene un ID único para navegación directa.
* **Estructura Escalable:** Preparado para agregar descripciones detalladas de productos.

## 📂 Estructura del Proyecto

```text
.
├── app.js              # Servidor principal y configuración de rutas
├── package.json        # Gestión de dependencias y scripts
├── .gitignore         # Archivos y directorios ignorados por Git
├── README.md          # Documentación del proyecto
└── views/             # Plantillas de la interfaz (EJS)
    ├── index.ejs      # Vista principal de productos (catálogo)
    └── detalles.ejs   # Vista de detalles individuales del producto

## 🛣️ Rutas Disponibles

* **`GET /`** - Página principal con todos los productos
* **`GET /categoria/:nombreCategoria`** - Filtrar productos por categoría (computadores, perifericos)
* **`GET /producto/:id`** - Ver detalles de un producto específico

## 🚀 Cómo Ejecutar el Proyecto

1. **Instalar dependencias:**
   ```bash
   npm install
   ```

2. **Ejecutar en modo desarrollo:**
   ```bash
   npm run dev
   ```

3. **Ejecutar en modo producción:**
   ```bash
   npm start
   ```

4. **Abrir en el navegador:**
   ```
   http://localhost:3000
   ```

## 📋 Próximas Funcionalidades

* Llenar la propiedad `detalles` de cada producto con descripciones completas
* Sistema de carrito de compras
* Base de datos para persistencia de datos
* Autenticación de usuarios
* Sistema de pagos
* Panel de administración