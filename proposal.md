# Propuesta TP DSW

## Grupo
### Integrantes
47057 - Bruzzesi, Ignacio <br>
47240 - Oviedo, Bernardo <br>
46122- Sabbioni, Santiago

### Repositorios
* [frontend app](http://hyperlinkToGihubOrGitlab)
* [backend app](http://hyperlinkToGihubOrGitlab)
*Nota*: si utiliza un monorepo indicar un solo link con fullstack app.

## Tema
Gestion de clubes de Futbol
### Descripción
Pagina web destinada a clubes de futbol incorporando la gestion de socios, pagos de cuotas, noticias, entre otras. Esto servira para poder llevar la cantidad de socios dentro del club, poder saber si llevan al dia la cuota y para los socios poder tener informacion, manteniendo transparencia en dicha institucion.
Las noticias que tengan lugar dentro del club actualizadas momento a momento con notas de jugadores post partidos y logros obtenidos. 

### Modelo
![imagen del modelo]()<br>
[Link del modelo de dominio](https://drive.google.com/file/d/1iKmK5JbkXMSjraB80hQBhKbSSrEA-kAw/view).

## Alcance Funcional 
### Alcance Mínimo

*Nota*: el siguiente es un ejemplo para un grupo de 3 integrantes para un sistema de hotel. El 

Regularidad:
|Req|Detalle|
|:-|:-|
|CRUD simple|1. CRUD Usuario <br>2. CRUD Noticias<br>3. CRUD Cuota|
|CRUD dependiente|1. CRUD Socio {depende de} CRUD Cuota<br>2. CRUD Multimedia {depende de} CRUD Noticias|
|Listado<br>+<br>detalle| 1. Listado de SOCIO filtrado por los que estan al dia y los que no, muestra nro y tipo de socio => detalle CRUD Socio<br> 2. Listado de noticias filtrado por rango de fecha, muestra titulo de la noticia, fecha, foto de la noticia y breve descripcion => detalle muestra un listado de noticias|
|CUU/Epic|1. Asociarte al club<br>2. Realizar una edicion dentro de las noticias del club|


Adicionales para Aprobación
|Req|Detalle|
|:-|:-|
|CRUD |1. CRUD Eventos/partidos<br>2. CRUD Plantel/Jugadores<br>3. CRUD Entradas<br>4. CRUD Administrador|
|CUU/Epic|1. <br>2. <br>3. |


### Alcance Adicional Voluntario

*Nota*: El Alcance Adicional Voluntario es opcional, pero ayuda a que la funcionalidad del sistema esté completa y será considerado en la nota en función de su complejidad y esfuerzo.

|Req|Detalle|
|:-|:-|
|Listados |1. Estadía del día filtrado por fecha muestra, cliente, habitaciones y estado <br>2. Reservas filtradas por cliente muestra datos del cliente y de cada reserve fechas, estado cantidad de habitaciones y huespedes|
|CUU/Epic|1. Consumir servicios<br>2. Cancelación de reserva|
|Otros|1. Envío de recordatorio de reserva por email|
