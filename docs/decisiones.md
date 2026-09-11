## Aplicar filtros usa button y no enlace

**Elegido:** `<button>` para la acción «Aplicar filtros».
**Descartado:** `<a>`.
**Consecuencia que evita:** el botón representa una acción que se ejecuta en la misma vista; un enlace daría a entender que se navega a otra página.

## El listado de tickets usa table y no lista

**Elegido:** `<table>` para mostrar los seis tickets.
**Descartado:** una lista con `<ul>` y `<li>`.
**Consecuencia que evita:** la tabla relaciona cada dato con su columna, como Cliente, Estado o Prioridad; en una lista esa relación sería menos clara.