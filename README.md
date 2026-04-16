# ACTIVIDAD 1
## Restricciones:

Duración: 120 minutos.
Máximo grupos de tres alumnos.

## Descripción:

Usted se encuentra desarrollando un MVP que permite registrar tareas y asociar notas a esas tareas. Una tarea está compuesta por un nombre (clave) y una descripción, un ejemplo sería:  

Nombre: Examen 1 - Cálculo, 
Descripción: Examen final Calculo, Universidad ORT

Por otro lado, las notas, se asocian a una tarea, un nombre de estudiante y el valor numérico de la nota. (No hay restricciones respecto a la nota)

## Consigna:

**1.- En este repo y desarrollado en nodeJS usted deberá lograr los siguientes puntos:**

A. Extensión de funcionalidad: 
Se debe agregar las siguientes funcionalidades:

- Alta de una tarea
- Alta de una nota
- Listado de notas para una tarea

La persistencia de esta información debe desarrollarse sobre el servicio de AWS.
*Pueden utilizar otras tecnologías diferentes a NodeJS y DynamoDB para el desarrollo de esta actividad. (Sugerimos nodejs+dynamo porque las dimos en clase)*
<br><br>
B. Portabilidad: La aplicación debe tener especificado correctamente Docker + Docker Compose.
<br><br>
C. Despliegue: La aplicación debe ser desplegada en AWS utilizando ECS. Debe permitir acceder mediante cliente HTTP (ej: CURL, Postman) a la nueva funcionalidad de gestión de tareas.

Importante: Debe tomar capturas de pantalla que muestren el proceso seguido y el resultado obtenido. Esto debe quedar incluído en una carpeta llamada “evidencia” en el repositorio.
<br><br>
**2.- Responda las siguientes preguntas relacionadas con 12 factor app modificando el README.md del repositorio**


a. Elijan 2 factores que creen haber aplicado correctamente en el desarrollo de la aplicación y expliquen por qué

b. Elijan 1 factor que no aplicaron y expliquen qué cambios realizaría para que se cumpla.

c. Pensando en el factor de “Concurrencia”: describa cómo diseñaría el sistema (incluyendo despliegue en AWS) para añadir el envío de las notas por mail.




Todo el desarrollo de la aplicación así como la evidencia y  las respuestas de las preguntas se deben encontrar en el repositorio de GitHub dentro de la organización: IngSoft-ASP-2023-2. 
