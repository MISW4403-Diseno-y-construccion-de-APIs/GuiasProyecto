## Semana 3 - Crear los módulos, los servicios y la estructura de recursos

### Objetivos

---

Los objetivos de esta actividad son:

- Implementar la estructura de módulos y servicios en Angular.
- Implementar las pruebas unitarias de los servicios.

### Pasos previos

---

- Haber configurado el ambiente local.
- Tener el listado de las HU que se van a implementar.
- Realizar el tutorial de ejemplo.

### Descripción actividad

---

#### ![](./../../assets/images/individuo.png) Actividad individual

Cada integrante, para cada uno de los recursos involucrados en las historias de usuario asignadas, debe:

- Crear el módulo del recurso correspondiente siguiendo las convenciones de nombramiento.
- Crear las clases que representa el recurso: la básica y la detallada. Las clases necesarias en la representación detallada, de otros recursos, se definen en comentarios mientras los demás integran su código.
- Crear el servicio que accede el API REST para ese ese módulo.
- Programar el método `http get` para traer la colección de elementos del recurso.
- Programar la prueba del servicio.
- Verificar que todo esté funcionando.
- Realizar un commit en el repositorio local y solicitar un `pull request`.
- El lider del equipo aprueba o no el `pull request`.

### Recursos

---

- Tutorial de configuración de ambiente de trabajo: https://misovirtual.virtual.uniandes.edu.co/codelabs/EntornoTrabajo/index.html#0

### Entregables

---

- Repositorio de Github actualizado.

### Criterios de evaluación

---

- La implementación cumple con la arquitectura propuesta: módulo, clase del recurso, método del servicio y prueba del método del servicio.

- El código en el repositorio incluye al menos una prueba para cada servicio.

- Las pruebas de los servicios se ejecutan correctamente. Para esto el tutor descargará el proyecto del equipo y ejecutará el comando `ng test`. Se espera que todos los test pasen sin errores.
