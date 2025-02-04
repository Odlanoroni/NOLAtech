# NOLAtech Dashboard

![NOLAtech](NOLAtech-img.png)

Este proyecto es una aplicación web construida utilizando el stack MERN (MongoDB, Express, React, Node.js). La aplicación cuenta con un backend en Node.js y Express que se conecta a una base de datos MongoDB, y un frontend en React.

## Requisitos

Antes de ejecutar el proyecto, asegúrate de tener instalados los siguientes requisitos:

- [Node.js](https://nodejs.org/) - Versión 14 o superior
- [MongoDB Atlas](https://www.mongodb.com/cloud/atlas) (o una instancia local de MongoDB)

## Configuración

### Variables de Entorno

Crea un archivo `.env` en la carpeta raíz del proyecto y configura las siguientes variables de entorno:

- MONGO_URI=mongodb+srv://user:<db_password>@cluster0.duav4.mongodb.net/?retryWrites=true&w=majority&appName=Cluster0
- PORT=5000
- JWT_SECRET=your_super_secret_jwt_secret
- NODE_ENV=development

## Instrucciones para correr en local

- Clonar repocitorio
- Instalar dependencias en root folder y en frontend folder (npm install)
- Crear cluster en MONGO DB
- Crear .env con variables de entorno
- Correr npm run dev en root folder y en frontend folder

## Credenciales de ejemplo para login (credenciales de users)

### Admin

- email: admin1@gmail.com
- password: 123456

### Manager

- email: manager1@gmail.com
- password: 123456

### Manager

- email: employee1@gmail.com
- password: 123456

## Demo:

[https://nolatech-752j.onrender.com/](https://nolatech-752j.onrender.com/)
