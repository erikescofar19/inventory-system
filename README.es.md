## Read this in: [English](README.md) 

#  Sistema de Gestión de Inventarios

Sistema completo de gestión de inventarios compuesto por un **backend REST API** y un **frontend web**, desarrollado como proyecto profesional para portafolio.

Este sistema permite autenticar usuarios, gestionar productos, controlar stock, registrar movimientos de entrada y salida, y visualizar información desde una interfaz moderna.

---

##  Arquitectura del sistema

El proyecto está dividido en dos aplicaciones independientes:

###  Backend – Inventory API
API REST desarrollada con Node.js y MongoDB.

 [Ir al repositorio Backend](./inventory-backend)

**Responsabilidades:**
- Autenticación con JWT
- Gestión de usuarios y roles
- CRUD de productos
- Control de stock
- Registro de movimientos
- Documentación con Swagger

---

###  Frontend – Inventory Frontend
Aplicación web desarrollada con React + Vite.

 [Ir al repositorio Frontend](./inventory-frontend)

**Responsabilidades:**
- Login de usuarios
- Consumo de API REST
- Visualización de productos
- Registro de movimientos de stock
- Alertas visuales de stock bajo
- Manejo de sesión con JWT

---

##  Estructura general del proyecto

```bash
inventory-system/
├── inventory-backend/
│   ├── README.md
│   └── README.es.md
├── inventory-frontend/
│   ├── README.md
│   └── README.es.md
├── README.md
└── README.es.md
```

## Tecnologías utilizadas
Backend
Node.js

Express.js

MongoDB + Mongoose

JWT

Swagger (OpenAPI)

bcryptjs

Frontend
React

Vite

JavaScript (ES6+)

Axios

CSS

Autenticación JWT

## Objetivo del proyecto
Este proyecto fue desarrollado como práctica profesional, enfocado en:

Arquitectura limpia

Separación de responsabilidades

Seguridad con JWT

Consumo real de APIs REST

Escalabilidad

Buenas prácticas de desarrollo

## Autor
Erik Eduardo Escobar Farías

Proyecto fullstack desarrollado con fines profesionales y de portafolio, simulando un sistema real utilizado en negocios como cafeterías, tiendas y pequeños almacenes.