# Desafío técnico 🚀

<img src="./assets/repository-header.jpg">

## Información general

Desde la _Secretaría de Innovación y Transformación Digital_ estamos muy contentos de que estés interesado/a en sumarte a nuestro equipo de desarrollo, pero antes, vamos a proponerte que realices un desafío para que puedas familiarizarte con las tecnologías con las cuales trabajamos.

## Requisitos

El desafío consiste en desarrollar un sitio web que cuente con las siguientes pantallas.

### Registro

Deberá incluir un formulario con los campos: nombre, apellido, email y contraseña.

### Inicio de sesión

Deberá incluir un formulario que permita autenticarse con email y contraseña. En caso de que las credenciales ingresadas sean correctas, redigir al usuario a la pantalla principal.

### Pantalla principal

Si el usuario es administrador, deberá mostrarse una tabla dónde se listen todos los usuarios registrados.
En caso contrario, solo mostrar un mensaje de bienvenida.  
No te olvides de proteger esta ruta, es decir, que solo puedan acceder aquellos usuarios que hayan iniciado sesión previamente.

## Especificaciones técnicas

Para el desarrollo del frontend deberás utilizar la biblioteca [React](https://reactjs.org). Puedes utilizar CSS/SASS o el framework que prefieras (Ej: [Bootstrap](https://react-bootstrap.github.io/)) para ayudarte con el estilado del sitio. No olvides comunicar al usuario los mensajes de éxito o error que tengan lugar en las distintas pantallas.   
En cuanto al backend, deberás utilizar [Node.js](https://nodejs.org/) en conjunto con el framework [Express](https://expressjs.com). La base de datos deberá ser SQL, utilizando [Sequelize](https://sequelize.org) con transacciones para realizar las consultas.
Te recomendamos gestionar tu base de datos con [MySQL Workbench](https://www.mysql.com/products/workbench/).

## Formato de entrega

Una vez terminado el proyecto, deberás enviarnos el link del repositorio para que podamos revisarlo. No olvides incluir un archivo README explicando brevemente el funcionamiento del sitio y detallando los pasos a seguir para que podamos probarlo en local.