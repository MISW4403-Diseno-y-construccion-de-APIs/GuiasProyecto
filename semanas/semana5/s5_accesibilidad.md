## Semana 5 - Incorporar accesibilidad

### Objetivos

---

El objetivo de esta actividad es:

- Incorporar elementos de accesibilidad en la aplicación web, para garantizar un nivel de conformidad equivalente a AA según la pauta WCAG 2.1 de 2018.

### Pasos previos

---

Cada estudiante debe haber:

- Revisado el material sobre accesibilidad.
- Realizado la lectura sobre "Historias de accesibilidad".
- Avanzado en la implementación de las HU relacionadas con los despliegues.

### Descripción actividad

---

#### ![](./../../assets/images/grupo.png) Actividad de equipo

- Durante el proceso de elaboración de la aplicación web, el equipo debe constratar que cada una de las guías correspondientes al nivel de conformidad AA según la pauta WCAG 2.1 2018 se cumplen.

- Para efectos de brevedad, la tabla solo presenta un resumen de criterios alineados con el nivel AA; no obstante en la referencia rápida de la guía (https://www.w3.org/WAI/WCAG21/quickref/) se encuentra información detallada de cada uno.

| Criterio       | Categoría                             | Guía                                           |
| -------------- | ------------------------------------- | ---------------------------------------------- |
| 1. Perceptible | 1.1 Alternativas textuales            | 1.1.1 Contenido no textual                     |
|                | 1.2 Medios basados en el tiempo       | 1.2.1 Contenido en audio y video (pregrabado)  |
|                |                                       | 1.2.2 Subtítulos                               |
|                |                                       | 1.2.3 Descripción de audio o medio alternativo |
|                |                                       | 1.2.4 Subtítulos en vivo                       |
|                |                                       | 1.2.5 Descripción del audio                    |
|                | 1.3 Adaptable                         | 1.3.1 Información y relaciones                 |
|                |                                       | 1.3.2 Secuencia con significado                |
|                |                                       | 1.3.3 Características sensoriales              |
|                |                                       | 1.3.4 Orientación                              |
|                |                                       | 1.3.5 Identificar el propósito de la entrada   |
|                | 1.4 Distinguible                      | 1.4.1 Uso de color                             |
|                |                                       | 1.4.2 Control de audio                         |
|                |                                       | 1.4.3 Contraste mínimo                         |
|                |                                       | 1.4.4 Ajuste del tamaño del texto              |
|                |                                       | 1.4.5 Imágenes de texto                        |
|                |                                       | 1.4.10 Scrolling                               |
|                |                                       | 1.4.11 Contraste para no texto                 |
|                |                                       | 1.4.12 Espaciado del texto                     |
|                |                                       | 1.4.13 Contenido en "Hover" o en foco          |
| 2. Operable    | 2.1 Teclado accesible                 | 2.1.1 Teclado                                  |
|                |                                       | 2.1.2 Sin trampas de teclado                   |
|                |                                       | 2.1.4 Atajos de teclado                        |
|                | 2.2 Tiempo sifuciente                 | 2.2.1 Tiempo ajustable                         |
|                |                                       | 2.2.2 Pausar, parar, ocultar                   |
|                | 2.3 Convulsiones y reacciones físicas | 2.3.1 Tres parpadeos o menos                   |
|                | 2.4 Navegable                         | 2.4.1 Obviar bloques de contenido              |
|                |                                       | 2.4.2 Títulos de páginas                       |
|                |                                       | 2.4.3 Orden del foco                           |
|                |                                       | 2.4.4 Propósito del link                       |
|                |                                       | 2.4.5 Múltiples vías                           |
|                |                                       | 2.4.6 Encabezados y etiquetas                  |
|                |                                       | 2.4.7 Foco visible                             |
|                | 2.5 Modalidades de entrada            | 2.5.1 Gestos del puntero                       |
|                |                                       | 2.5.2 Cancelación del puntero                  |
|                |                                       | 2.5.3 Etiquetas en el nombre                   |
|                |                                       | 2.5.4 Actuación con movimiento                 |
| 3. Entendible  | 3.1 Leible                            | 3.1.1 Idioma de la página                      |
|                |                                       | 3.1.2 Idioma de las partes                     |
|                | 3.2 Predecible                        | 3.2.1 Al recibir el foco                       |
|                |                                       | 3.2.2 Al recibir una entrada                   |
|                |                                       | 3.2.3 Navegación consistente                   |
|                |                                       | 3.2.4 Identificación consistente               |
|                | 3.3 Asistencia de entrada             | 3.3.1 Identificación del error                 |
|                |                                       | 3.3.2 Etiquetas o instrucciones                |
|                |                                       | 3.3.3 Sugerencia de errores                    |
|                |                                       | 3.3.4 Prevención de errores                    |
| 4. Robusto     | 4.1 Compatible                        | 4.1.1 Parsing                                  |
|                |                                       | 4.1.2 Nombre, rol, valor                       |
|                |                                       | 4.1.3 Mensajes de estado                       |

- La primera actividad consiste en la revisión de los criterios. Para esto de común acuerdo con su grupo, distribuya los criterios de forma equitativa. A quien se le asigne el criterio será responsable de verificar si este está o no presente en la aplicación.

- La segunda actividad consiste en la correción de los hallazgos. De igual forma, la asignación de las correciones se hará de forma equitativa.

#### ![](./../../assets/images/individuo.png) Actividad individual

- Luego de haber constratado la aplicación con cada una de las guías de la tabla anterior, la aplicación deberá ser analizada utilizando el plugin AXE. Para eso, instale el plugin AXE en su navegador. Está disponible para Chrome (https://chrome.google.com/webstore/detail/axe-web-accessibility-tes/lhdoppojpmngadmnindnejefpokejbdd) y para Firefox (https://addons.mozilla.org/es/firefox/addon/axe-devtools/).

- En el caso de Chrome, luego de haber instalado el plugin, vaya a las herramientas para desarrolladores (ubicadada en el menú Más herramientas) y en las opciones seleccione AXE. Luego haga clic al botón _Analyze_. Eso mostrará un listado de todos los issues reportados por la herramienta. Asegúrese de revisar cada uno de ellos y de resolverlos.

- Luego de la corrección, ejectute la herramienta hasta asegurarse de que no queda ningún issue por resolver.

### Recursos

---

- Herramienta de verificación de accesibilidad - Plugin para Chrome: https://chrome.google.com/webstore/detail/axe-web-accessibility-tes/lhdoppojpmngadmnindnejefpokejbdd.

- Herramienta de verificación de accesibilidad - Plugin para Firefox: https://addons.mozilla.org/es/firefox/addon/axe-devtools/

### Entregable

---

- Repositorio de Github actualizado.

### Criterios de evaluación

---

- Para evaluar el cumplimiento de esta tarea, el tutor descargará el código del repositorio y ejecutará la herramienta de validación. Se espera no encontrar ningún issue reportado.
