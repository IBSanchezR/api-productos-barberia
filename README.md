# API de Productos - Barbería 💈

Este proyecto es una API REST creada con Node.js y Express para gestionar los productos de una barbería.  
Incluye documentación Swagger, conexión a base de datos PostgreSQL, y pruebas por cada historia de usuario.

---

## 🧩 Funcionalidades principales

- Ver listado de productos
- Registrar nuevos productos
- Editar productos existentes
- Eliminar productos
- Acceso a documentación Swagger

---

## 📦 Tecnologías utilizadas

- Node.js
- Express
- PostgreSQL
- pg-pool
- Swagger UI
- dotenv

--- 
## 📂 Estructura del proyecto

```
api-productos-barberia/
├── backend/               # Código fuente del backend
├── evidencia/             # Capturas de pruebas Swagger
├── HU.md                  # Historias de usuario con evidencia
├── README.md              # Este archivo
└── .gitignore             # Ignorar node_modules y .env
```

---

## 🔗 Documentación

- Swagger UI: [http://localhost:3000/api-docs](http://localhost:3000/api-docs)
- Historias de usuario: [`HU.md`](./HU.md)

---

## 🧪 ¿Cómo probar?

1. Clona el repositorio
2. Configura tu archivo `.env`
3. Instala dependencias y corre el backend:

```bash
npm install
node index.js
```

4. Abre Swagger en el navegador:
[http://localhost:3000/api-docs](http://localhost:3000/api-docs)

---

## 📸 Evidencia

Consulta el archivo [`HU.md`](./HU.md) para ver las pruebas realizadas por historia de usuario.

Backend Node.js con Express y Swagger para la gestión de productos en una barbería. Incluye documentación y evidencia de pruebas por historia de usuario.
