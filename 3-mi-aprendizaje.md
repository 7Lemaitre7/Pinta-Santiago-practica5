# COMPLETAR  
Comparando sus conocimientos antes de hacer la práctica con sus conocimientos después de hacer la tarea, explicar los principales aprendizajes logrados para beneficio de su formación profesional.  
## Antes de la práctica:
Tenía una idea muy básica de cómo se configuraba un contenedor. Pensaba que para que una aplicación funcione, Docker solo necesitaba la imagen y ya, pero no entendía bien cómo "darle órdenes" personalizadas. Me confundía un poco el tema de los puertos y cómo hacer que una base de datos y una aplicación se hablaran entre sí sin que fuera un relajo de conexiones. Tampoco sabía que podía controlar cuánta memoria o procesador usaba cada cosa, y me daba miedo que un contenedor mal puesto me trabara toda la computadora por usar demasiada RAM.

## Después de la práctica:
Ahora entiendo mucho mejor cómo usar el Dockerfile para crear mis propias imágenes desde cero y no solo bajar las que ya existen. Aprendí a usar los Healthchecks, que básicamente son como un chequeo médico para que Docker sepa si la aplicación adentro está respondiendo de verdad o si se quedó colgada. También aprendí a poner límites de recursos para que mis contenedores no se pasen de listos con la memoria de mi PC.

Lo que más me sirvió fue Docker Compose, porque ahora sé que no tengo que andar lanzando comandos uno por uno para la base de datos y la web. Con un solo archivo puedo armar toda la estructura, conectar las redes y hacer que todo suba en orden. Ya me queda claro que con el flag de reinicio puedo estar tranquilo de que mis servicios se van a intentar levantar solos si algo falla.

Si solucionó un problema presentado al realizar la práctica también se debe documentar.

El único problema encontrado y solucionado fue el siguiente:
<img width="1698" height="199" alt="image" src="https://github.com/user-attachments/assets/97cb5c1e-c641-4fc9-8b5b-db151fce0ff2" />
Al ejecutar el comando indicado se dió ese problema, sin embargo se solucionó iniciando el docker, es decir, la aplicación no estaba abierta.
