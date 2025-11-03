# Propuesta TP DSW

## Grupo
### Integrantes
47057 - Bruzzesi, Ignacio <br>
47240 - Oviedo, Bernardo <br>
46122- Sabbioni, Santiago

### Repositorios
* [frontend app](https://github.com/bernioviedo/TP-Club/tree/main/client)
* [backend app](https://github.com/bernioviedo/TP-Club/tree/main/server)

## Tema
Gestion de clubes
### Descripción
Pagina web destinada a instituciones deportivas incorporando la gestión de socios, noticias, contenido de los partidos y entrenamientos, entre otras. Esto servirá para que los socios o fanáticos del club puedan estar al tanto de novedades y tengan un lugar donde gestionar su membresía como socios en el caso de serlo. También ayuda a tener datos internos como la cantidad exacta de socios del club, cuántos usuarios son socios y cuántos no y a saber qué opinan los usuarios de las noticias del club mediante una sección de comentarios individual para cada novedad.
Las noticias que tengan lugar dentro del club actualizadas momento a momento con notas de jugadores post partidos, logros obtenidos, futuros encuentros deportivos, actividades realizadas dentro de la institución o nuevo merchandising del club.

### Modelo

[Link del modelo de dominio](https://drive.google.com/file/d/1iKmK5JbkXMSjraB80hQBhKbSSrEA-kAw/view).

## Alcance Funcional 
### Alcance Mínimo

Regularidad:
|Req|Detalle|
|:-|:-|
|CRUD simple|1. CRUD Usuario <br>2. CRUD Noticias<br>3. CRUD Media<br>4. CRUD Comentarios|
|CRUD dependiente|1. CRUD Noticias {depende de} CRUD Administrador<br>2. CRUD Comentario {depende de} CRUD Noticias|
|Listado<br>+<br>detalle| 1. Listado de COMENTARIOS filtrado por antiguedad, muestra contenido, autor y fecha => detalle CRUD Comentario<br> 2. Listado de noticias filtrado por rango de fecha, muestra título de la noticia, fecha, foto de la noticia y breve descripción => detalle muestra un listado de noticias|
|CUU/Epic|1. Realizar un comentario en una noticia<br>2. Realizar una edición dentro de las noticias del club<br>3. Cambiar tipo de usuario a administrador|


Adicionales para Aprobación
|Req|Detalle|
|:-|:-|
|CRUD |1. CRUD Eventos/partidos<br>2. CRUD Plantel/Jugadores<br>3. CRUD Entradas<br>4. CRUD Comentarios|
|CUU/Epic|1. Cargar un evento a la app<br>2. Agregar jugadores al plantel <br>3. Sacar entradas para un evento <br> 4. Agregar comentarios a las noticias|


### Alcance Adicional Voluntario

*Nota*: El Alcance Adicional Voluntario es opcional, pero ayuda a que la funcionalidad del sistema esté completa y será considerado en la nota en función de su complejidad y esfuerzo.

|Req|Detalle|
|:-|:-|
|Listados |1. |
|CUU/Epic|1.|
|Otros|1. |

