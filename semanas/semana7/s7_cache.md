## Semana 7 - Incorporar cache

### Objetivos

---

El objetivo de esta actividad es:

- Incorporar cache en el API desarrollada con el fin de mejorar su deseméño.

### Pasos previos

---

- Haber realizado previamente el tutorial sobre cache en Nest.js.

### Descripción de actividad

---

#### ![](./../../assets/images/individuo.png) Actividad individual

- Agregar en los servicios el código que permite incorporar el caché. Esto se debe hacer en los métodos de tipo findAll.
- Agregar un conjunto significativo de datos (aprox. 100.000 registros) en las tablas que representam recursos y asociaciones para comparar el desempeño del API con y sin caché. 
- Elaborar las pruebas de desempeño con JMeter. 

### Recursos

- Tutorial de caché en Nest.js: http://misovirtual.virtual.uniandes.edu.co/codelabs/MISW4403_202212_Caching/index.html#0 

### Entregable

---

- Repositorio de GitHub actualizado.

### Criterio de calificación

---

- Al revisar la aplicación se evidencia que en todos los métodos del servicio se ha incluido el código para administrar el cache.
- Existe una carpeta scripts que contiene un archivo SQL con una cantidad significativa de datos para cada tabla que represente un recurso o una asociación (100.000 registros aprox).
- En la wiki se incluyen las evidencias (e.g., capturas de pantalla de JMeter) que demuestran el mejoramiento del desempeño del API.
