# Prácticas de testing de APIs con Postman

Este repositorio reúne colecciones de Postman creadas como práctica de un curso de testing de APIs. Los archivos contienen solicitudes a APIs de ejemplo y ejercicios para explorar operaciones REST, autenticación, variables y validaciones de respuestas. No es una aplicación ni requiere compilarse.

## Stack y herramientas

- **Postman** para crear, organizar y ejecutar solicitudes HTTP y colecciones.
- **JavaScript en Postman Sandbox** para scripts previos a las solicitudes, datos dinámicos y pruebas automatizadas de respuesta.
- **JSON** para los cuerpos de las solicitudes y el manejo de respuestas.
- **APIs REST públicas o de demostración** como servicios de prueba.

## Contenidos

| Colección | Prácticas incluidas |
| --- | --- |
| [Curso de API testing Postman - APIs clases](<Curso de API testing Postman -APIs clases.postman_collection.json>) | Solicitudes iniciales y organización en carpetas; consultas y operaciones CRUD de productos; autenticación básica, por API key y Bearer token; variables; scripts pre-request, datos dinámicos y aserciones. |
| [API deportes](<API deportes1-solucion.postman_collection.json>) | Consultas de ligas, equipos y jugadores; generación de un país aleatorio y pruebas sobre contenido, campos, encabezados y tiempo de respuesta. |
| [API tienda de mascotas](<API tienda de mascotas.postman_collection.json>) | Creación, consulta y eliminación de usuarios en Petstore. |
| [Práctica de autenticación](<Practica Autenticacion APIs Postman.postman_collection.json>) | Ejemplos de autenticación Basic, Bearer token y API key con servicios de demostración. |
| [API cócteles](<API cocteles.postman_collection.json>) | Búsqueda de cócteles e ingredientes mediante variables de colección y parámetros de consulta. |
| [API Libros](<colección API Libros.postman_collection.json>) | Consulta del catálogo de libros y búsqueda por ISBN. |

## Funcionalidades practicadas

- Envío de solicitudes **GET, POST, PUT y DELETE**.
- Lectura de respuestas JSON y uso de parámetros de ruta y de consulta.
- Envío de cuerpos JSON en solicitudes de creación y actualización.
- Organización de solicitudes en colecciones y carpetas.
- Configuración de autenticación **Basic**, **Bearer** y **API key**.
- Uso de variables globales, de colección y de entorno, además de variables dinámicas de Postman.
- Ejecución de scripts *pre-request* y pruebas con `pm.test` y `pm.expect`.
- Validación de códigos de estado, encabezados, campos y valores del cuerpo, tipos de datos y tiempo de respuesta.

## Cómo usar las colecciones

1. Descarga o clona este repositorio.
2. En Postman, selecciona **Import** y elige uno o más archivos `.postman_collection.json`.
3. Revisa las variables que aparecen entre llaves, por ejemplo `{{URL}}`, `{{CATEGORIA}}` o `{{coctel}}`, y configura los valores requeridos en Postman.
4. Comprueba la autenticación y los datos de las solicitudes antes de ejecutarlas. Puedes ejecutar una solicitud individual o usar el **Collection Runner** para correr una colección.

Las APIs de demostración pueden cambiar, limitar solicitudes o dejar de estar disponibles; por ello, el resultado de una práctica puede variar con el tiempo. Algunas colecciones incluyen valores de autenticación de ejemplo: revísalos y reemplázalos por credenciales de prueba propias. No agregues claves reales ni tokens privados al repositorio.
