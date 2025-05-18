# 📋 Historias de Usuario y Evidencia de Pruebas

Este archivo documenta las funcionalidades implementadas en la API para la gestión de productos de una barbería, junto con evidencia de pruebas realizadas desde Swagger.

---

## ✅ HU1 - Ver lista de productos

- 📤 Endpoint: `GET /api/productos`
- 📥 Resultado: `200 OK`
- 📸 ![HU1](./evidencia/hu1_get.png)

---

## ✅ HU2 - Registrar nuevo producto

- 📤 Endpoint: `POST /api/productos`
- 📥 Resultado: `201 Created`
- 📸 ![HU2](./evidencia/hu2_post.png)

---

## ✅ HU3 - Editar producto existente

- 📤 Endpoint: `PUT /api/productos/{id}`
- 📥 Resultado: `200 OK`
- 📸 ![HU3](./evidencia/hu3_put.png)

---

## ✅ HU4 - Eliminar producto

- 📤 Endpoint: `DELETE /api/productos/{id}`
- 📥 Resultado: `204 No Content`
- 📸 ![HU4](./evidencia/hu4_delete.png)

---

## ✅ HU5 - Documentación de la API

- 📤 Acceso: `GET http://localhost:3000/api-docs`
- 📸 ![HU5](./evidencia/hu5_swagger.png)
