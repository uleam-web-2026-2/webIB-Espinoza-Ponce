# Nuestro negocio

Negocio: Plataforma web para crear, publicar y consultar tutoriales.

Video de Starter Story:https://www.youtube.com/watch?v=l4WEqPX52Cg

Como lo adaptamos a Ecuador: Permitimos que estudiantes y usuarios encuentren tutoriales en un solo lugar, organizados por categorías y disponibles en distintos formatos como video, paso a paso.

## Las dos entidades

1. Tutorial
2. Categoría, que se relaciona con la primera porque cada tutorial pertenece a una categoría y permite organizar los contenidos según el tema que enseñan.

## La entidad que cambia de estado

Entidad: Tutorial

Estados: Borrador -> En revisión -> Publicado

Quien provoca cada cambio: El creador genera el tutorial y posteriormente puede enviarlo a revisión.

## Los dos roles

- Creador de tutoriales: puede crear, editar y enviar a revisión sus propios tutoriales; no puede aprobarlos ni publicarlos directamente.
- Moderador: puede revisar, aprobar y publicar los tutoriales enviados; no puede modificar el contenido del tutorial como si fuera su autor.

## Gestion de tutoriales

El rol que la usa: Creador de tutoriales.

La pregunta que responde: ¿Qué tutoriales he creado y en qué estado se encuentran?

## Pendientes

Definir si un tutorial rechazado tendrá un estado propio o regresará al estado Borrador.