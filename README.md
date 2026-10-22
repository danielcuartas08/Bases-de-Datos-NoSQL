# 🍃 Node.js & MongoDB - API REST NoSQL

Proyecto backend enfocado en el diseño, modelado y manipulación de bases de datos **NoSQL** utilizando **MongoDB** con **Mongoose ORM** y servidor web con **Node.js** y **Express**.

---

### 🛠️ Tecnologías Utilizadas

<p align="left">
  <img src="https://skillicons.dev/icons?i=nodejs,express,mongodb,js" alt="Tech Stack"/>
</p>

* **Entorno de ejecución:** Node.js
* **Framework Web:** Express.js
* **Base de Datos NoSQL:** MongoDB
* **ORM / ODM:** Mongoose
* **Gestor de paquetes:** npm

---

### ✨ Características del Proyecto

* 🗄️ **Modelado de Datos:** Esquemas definidos con Mongoose (`models/`) para validación de colecciones y documentos en MongoDB.
* ⚡ **Servidor RESTful:** Manejo de rutas y peticiones HTTP (`server.js`) para operaciones CRUD (Crear, Leer, Actualizar, Eliminar).
* 🌐 **Frontend de prueba:** Recursos estáticos ubicados en `public/` para interactuar con los endpoints de la API.

---

### 📂 Estructura del Proyecto

* `models/` - Definición de esquemas y modelos de datos de Mongoose.
* `public/` - Archivos estáticos e interfaz de prueba cliente.
* `server.js` - Punto de entrada principal y configuración del servidor Express.
* `package.json` - Dependencias y scripts de ejecución.

---

### 🚀 Configuración y Ejecución Local

1. **Requisitos previos:**
   * Tener instalado **Node.js** y un servidor de **MongoDB** (local o MongoDB Atlas).

2. **Instalación de dependencias:**
   ```bash
   npm install
