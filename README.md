# NODE JS: API REST (CRUD) con MongoDB

En este repositorio podrás encontrar una API REST desarrollada con **Node.js** y **Express**, que permite realizar operaciones CRUD (crear, leer, actualizar y eliminar) sobre una colección de libros almacenada en una base de datos **MongoDB**.

La aplicación utiliza **Mongoose** como modelado para definir esquemas y facilitar la interacción con la base de datos.

Para el entorno de desarrollo, se ha utilizado **Docker** a través de `docker-compose`, permitiendo levantar de forma rápida y sencilla un contenedor de MongoDB sin necesidad de instalaciones adicionales.

Además, se ha utilizado **MongoDB Compass** como interfaz gráfica para visualizar y gestionar la base de datos de forma más cómoda durante el desarrollo

## NECESARIO:

-   **NODE**: Se debe instalar NODE en el sistema operativo
-   **DOCKER**: Para poder levantar la imagen de Mongo en el contenedor
-   **GIT**: Debe tener Instalado GIT

## Guía de uso


1.  Cloná el repositorio haciendo  `git clone https://github.com/gerysx/rest-api-node-mongo-docker`
2.  Abre el proyecto en su editor de código
3.  Instalació de los paquetes y módulos requeridos:  `npm install`
4.  Agrega las variables de entorno que correspondan usando como plantilla  `.env.template`
5.  Teniendo abierto Docker Desktop ejecuta  `docker compose up -d` para evitar perder tu terminal activa.
6.  Levanta el servidor haciendo  `npm run dev` o configura package.json a tu elección.

