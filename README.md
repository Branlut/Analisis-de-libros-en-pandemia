# Análisis de libros en pandemia

## Descripción

El coranavirus condiciono a todos a aislarse de los demas lo que conllevo a dejar de hacer actividades al aire libre, esto conllevo a centrarse en actividades que se pudieran realizar sin la necesidad de depender de alguien que este fisicamente presente, gracias a esto las startups vieron una opurtunidad con los amantes de los libros, conbinando con esto con enfoque tecnologico se apresuron a realizar apliciones para este nicho.

## Objetivo
Nos han dado una base de datos que contempla los datos de unos de estas aplicaciones de la cual se no pidio analizarla para crear una propuesta de valor diferencial

## Tecnologias
- Python
- Vs code
- pandas
- sqlalchemy

## Tareas
### Encuentra el número de libros publicados después del 1 de enero de 2000.
- Existe 819 libros que se publicaron despues del 1 de Enero del 2000 esto es un 81.9% de los registros por lo que la gran mayoria son libros de hace aproximadamente 24 años
- La mayor cantidad de reseñas por libros es 2 y la mayor es de 7, se puede ver que no se han hecho reseñas de todos los libros.
- El rating de un libro que se puede decir que es bueno se dejara en este caso de 3 hacia arriba los cuales son la gran mayoria.
- Con esto podemos concluir que los libros no estan teniendo muchas reseñas y que por lo general se califican como bastante buenas.

### Identifica la editorial que ha publicado el mayor número de libros con más de 50 páginas.
- La editorial Penguin Books es la que mas libros ha publicado con 42, sabiendo esto se puede buscar hacer una asociacion con la editora para realizar publicaciones dentro de la aplicacion

### Identifica al autor que tiene la más alta calificación promedio del libro: mira solo los libros con al menos 50 calificaciones.
- Las autoras J.K. Rowling/Mary GrandPré	son las que poseen el promedio mas alto de calificaciones, como se puede apreciar esto es debido a que poseen varios libros, en este caso una saga Harry Potter la cual tiene una gran cantidad de calificaciones sus diferentes volumenes por lo que enfocarse en libros que posean varios volumenes es una buena idea.

### Encuentra el número promedio de reseñas de texto entre los usuarios que calificaron más de 50 libros.
- El promedio de reseñas de texto que tienen los usuarios que hicieron mas de 50 calificaciones es de 24 por lo que se podria
toma este numero como referencia base para ver si un libro es exitoso ya que llamo la suficiente atención para que la personas
lo reseñen
