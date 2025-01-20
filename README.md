## Foro Hub - Desafío - Back End
Este proyecto es mi respuesta al desafío de back-end de Foro Hub planteado por Alura. La solución se enfoca en desarrollar una API REST que permite realizar operaciones CRUD (Crear, Leer, Actualizar y Eliminar) sobre los tópicos de un foro.

## Descripción del Proyecto
En plataformas educativas como Alura, los foros son espacios fundamentales donde estudiantes, docentes y moderadores pueden interactuar para resolver inquietudes, compartir conocimientos y colaborar. Este proyecto no solo implementa las funciones principales del foro, sino que también incluye validaciones de negocio, un sistema de autenticación y autorización, y una base de datos para garantizar la persistencia de los datos.

El sistema permite a los usuarios iniciar sesión utilizando JWT (JSON Web Token). Este estándar de seguridad garantiza el acceso a los recursos protegidos sin la necesidad de mantener sesiones activas en el servidor, brindando una experiencia más segura y eficiente.

## Tecnologías Utilizadas
Java 17: Lenguaje principal en el que se basa la implementación del proyecto.
Maven: Herramienta para la gestión y organización de dependencias.
Spring Boot: Framework utilizado para agilizar el desarrollo del back-end.
Dependencias Clave:
Lombok: Reduce la cantidad de código repetitivo mediante anotaciones prácticas.
Spring Web: Facilita la creación de controladores REST para gestionar las solicitudes HTTP.
Spring Boot DevTools: Ofrece reinicios automáticos para acelerar el proceso de desarrollo.
Spring Data JPA: Simplifica el manejo de la persistencia mediante la especificación JPA.
Flyway Migration: Permite gestionar y versionar los cambios en la base de datos.
MySQL Driver: Driver para la integración con bases de datos relacionales basadas en MySQL.
Validation: Proporciona herramientas para validar datos de entrada.
Spring Security: Implementa mecanismos robustos de autenticación y control de acceso.
JWT Token: Facilita la transmisión de datos seguros a través de tokens cifrados.
Funciones Clave
## Crear un tópico nuevo: Permite agregar un nuevo tema de discusión al foro.
## Listar todos los tópicos: Devuelve un listado completo de los tópicos disponibles.
## Consultar un tópico específico: Recupera información detallada de un tema en particular.
## Actualizar un tópico: Modifica los datos de un tópico existente.
## Eliminar un tópico: Remueve un tema específico de la base de datos.
