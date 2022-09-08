## Semana 6 - Asegurar los endpoints 

### Objetivos

---

El objetivo de esta actividad es:

- Incorporar mecanismos de seguridad en el API desarrollado.

### Pasos previos

---

- Haber realizado previamente el tutorial sobre seguridad en Nest.js.

### Descripción de actividad

---

#### ![](./../../assets/images/individuo.png) Actividad individual

- Definir un conjunto de usuarios con sus contraseñas y permisos. Debe existir un usuario admin con todos los permisos, un usuario con permisos de lectura para todos los recursos, un usuario con permisos de lectura para un recurso específico, un usuario con permisos de escritura (creación y actualización) y otro con permisos de eliminación.
- Implementar un endpoint /users/login que valide las credenciales del usuario y genere un token de autorización. 
- Agregar en los controladores el código que permite incorporar seguridad. Cada usuario definido anteriormente solo tendrá acceso a los endpoints necesarios.


### Recursos

- Tutorial de seguridad en Nest.js: 

### Entregable

---
- Wiki con el listado de usuarios, credenciales para autenticarse y permisos que tiene para cada endpoint.
- Repositorio de GitHub actualizado.

### Criterio de calificación

---

- Al revisar la aplicación se evidencia que en los controladores se ha habilitado la opción de seguridad.
- No se puede consultar ningún endpoint sin que el usuario esté autenticado y tenga un token válido.
- No se pueden ejecutar operaciones de consulta, creación, actualización o eliminación por usuarios que no estén autenticados y autorizados. 
- Al revisar la wiki se encuentra el listado de usuarios, credenciales para autenticarse y permisos que tiene para cada endpoint

