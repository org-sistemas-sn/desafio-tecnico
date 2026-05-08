# Desafío técnico 

<img src="./assets/repository-header.jpg">


Desde la _Secretaría de Innovación y Ciudad Inteligente_ estamos muy contentos de que estés interesado/a en formar parte de nuestro equipo de desarrollo, por lo que vamos a proponerte realizar un desafío técnico para que podamos evaluar tus conocimientos utilizando las tecnologías con las cuales trabajamos a diario.


## Requerimientos

Deberás realizar una aplicación web que permita a los vecinos de nuestra ciudad realizar un trámite de forma online.

El trámite a implementar queda a elección del aspirante, pudiendo tomar como referencia el listado disponible en el siguiente link:
https://www.sannicolasciudad.gob.ar/tramites

No es necesario replicar el trámite en su totalidad, pueden omitirse pasos o simplificarse el flujo.

### Funcionalidades principales

#### Ciudadanos
- Crear un trámite completando un formulario (mínimo 8 campos)
- Al menos uno de los campos debe ser de tipo archivo
- Visualizar el estado del trámite
- Consultar el historial de cambios del trámite

#### Administradores
- Visualizar todos los trámites
- Cambiar el estado de un trámite
- Agregar comentarios
- Visualizar historial completo de acciones

---

## Requerimientos adicionales 

Para diferenciar tu solución, deberás implementar al menos **2 de las siguientes mejoras**:

### 1. Estados controlados
Implementar un sistema de estados con transiciones válidas (por ejemplo: pendiente → en revisión → aprobado/rechazado), evitando cambios inválidos.

### 2. Actualización en tiempo real
Cuando el estado de un trámite cambie, el usuario debe poder ver la actualización sin necesidad de recargar la página (WebSockets).

### 3. Historial de eventos
Registrar cada acción realizada sobre un trámite (creación, cambios de estado, comentarios), mostrando una línea de tiempo.

### 4. Validaciones avanzadas
Agregar validaciones tanto en frontend como en backend (por ejemplo: tipos de archivo, tamaños, campos obligatorios, etc.).

### 5. Búsqueda y filtros
Permitir a los administradores buscar y filtrar trámites por estado, fecha u otros criterios.

---

## Especificaciones técnicas

Para el desarrollo deberás utilizar:

### Backend
- Node.js con javascript o typescript
- Express
- Base de datos PostgreSQL
- Protocolo S3 o remoto para almacenamiento de archivos

### Frontend
- React JS / Typescript
- Tailwind CSS

Puedes añadir cualquier otra tecnología que consideres necesaria.

---

## Criterios de evaluación

Se evaluará:

- Calidad y organización del código
- Buenas prácticas
- Diseño de la base de datos
- Manejo de estados y lógica de negocio
- Experiencia de usuario
- Diseño de la página web
- Claridad en la documentación

---

## Formato de entrega :package:

Tendrás 10 días para completar este desafío.

Una vez finalizado, deberás enviar:

- Link al repositorio del frontend
- Link al repositorio del backend
- Un breve video (3-5 minutos) explicando:
  - Funcionamiento general
  - Decisiones técnicas tomadas
