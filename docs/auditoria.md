# Auditoría

## 1. Lo que vio la herramienta
Semana 4
Antes (listado de la semana 3): 100 / 100
hallazgos: ninguno (la pantalla anterior no contenía controles interactivos que auditar)

Con el formulario recién agregado, primera pasada: 100 / 100
qué corregimos: le dimos espacio y relleno al botón para que no salte el error de tamaño al tocarlo con el dedo, y conectamos bien las etiquetas con sus casillas.

## 2. Lo que no vio y cómo lo encontramos (mínimo dos)
Barrera: En la tabla de la semana pasada, el estado del tutorial solo se entendía por el color.
A quién dejaba afuera: A personas con daltonismo que confunden los colores y a quienes usan lectores de pantalla porque el lector no te dice qué color estás viendo.
Cómo la encontramos: Revisando el código y viendo que hacía falta escribir la palabra ("Borrador", "Publicado") directo en el texto de la celda y tambien con los ejemplos de la clase.

Barrera: La página venía configurada en inglés (`lang="en"`) desde que se creó el proyecto con Vite.
A quién dejaba afuera: A personas ciegas que usan lectores de pantalla, porque el sintetizador intentaba leer el texto en español como si fuera una voz gringa.
Cómo la encontramos: Nos dimos cuenta revisando a mano la primera línea del archivo `index.html`y gracias a las indicaciones del taller.

## . La paleta (si cambió)
- Color anterior: #ff0000 | Color nuevo: #b3261e | Contraste antes: 3.99 | Contraste después: 6.5 | Por qué: Se ajustó el tono del mensaje de error para superar el ratio mínimo de 4.5:1 exigido en WCAG AA sobre fondo blanco.
- Se ajustó para garantizar la legibilidad a personas con baja visión.