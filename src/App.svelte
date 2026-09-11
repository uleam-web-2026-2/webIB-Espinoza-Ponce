<header>
  <p>Nombre de la aplicación: <strong>Mesa de Ayuda</strong></p>

  <p>Enlaces de navegación:</p>
  <nav aria-label="Navegación principal">
    <a href="/tickets">Tickets</a> ·
    <a href="/clientes">Clientes</a> ·
    <a href="/reportes">Reportes</a>
  </nav>

  <p>
    Acción:
    <a href="/tickets/nuevo">Nuevo ticket</a>
  </p>
</header>

<main>
  <h1>Bandeja de tickets</h1>
  <p>Agente: Mariela Zambrano · 6 tickets asignados</p>

  <section aria-labelledby="titulo-filtros">
    <h2 id="titulo-filtros">Filtros</h2>

    <form>
      <p>
        <label for="estado">Estado:</label>
        <select id="estado" name="estado">
          <option>Todos</option>
          <option>Abierto</option>
          <option>En progreso</option>
          <option>En espera</option>
          <option>Resuelto</option>
          <option>Cerrado</option>
        </select>
      </p>

      <p>
        <label for="prioridad">Prioridad:</label>
        <select id="prioridad" name="prioridad">
          <option>Todas</option>
          <option>Alta</option>
          <option>Media</option>
          <option>Baja</option>
        </select>
      </p>

      <p>
        <label for="buscar">Buscar:</label>
        <input
          id="buscar"
          name="buscar"
          type="text"
          placeholder="Asunto o cliente"
        />
      </p>

      <p>
        Acción:
        <button type="submit">Aplicar filtros</button>
      </p>
    </form>
  </section>

  <section aria-labelledby="titulo-resumen">
    <h2 id="titulo-resumen">Resumen</h2>

    <p>
      Abiertos: 2 · En progreso: 2 · En espera: 1 · Resueltos: 1
    </p>
  </section>

  <section aria-labelledby="titulo-listado">
    <h2 id="titulo-listado">Listado de tickets</h2>

    <table aria-labelledby="titulo-listado">
      <thead>
        <tr>
          <th scope="col">N°</th>
          <th scope="col">Asunto</th>
          <th scope="col">Cliente</th>
          <th scope="col">Estado</th>
          <th scope="col">Prioridad</th>
          <th scope="col">Última actualización</th>
          <th scope="col">Acción</th>
        </tr>
      </thead>

      <tbody>
        <tr>
          <td>1041</td>
          <td>No puedo iniciar sesión en el portal</td>
          <td>Comercial Vélez</td>
          <td>Abierto</td>
          <td>Alta</td>
          <td>hace 20 min</td>
          <td><a href="/tickets/1041">Ver</a></td>
        </tr>

        <tr>
          <td>1038</td>
          <td>La factura electrónica no llega al correo</td>
          <td>Ferretería El Progreso</td>
          <td>En progreso</td>
          <td>Media</td>
          <td>hace 2 h</td>
          <td><a href="/tickets/1038">Ver</a></td>
        </tr>

        <tr>
          <td>1035</td>
          <td>Error al exportar el reporte mensual</td>
          <td>Distribuidora Manabí</td>
          <td>En espera</td>
          <td>Media</td>
          <td>ayer</td>
          <td><a href="/tickets/1035">Ver</a></td>
        </tr>

        <tr>
          <td>1031</td>
          <td>Solicitud de un usuario adicional</td>
          <td>Clínica San Rafael</td>
          <td>Abierto</td>
          <td>Baja</td>
          <td>ayer</td>
          <td><a href="/tickets/1031">Ver</a></td>
        </tr>

        <tr>
          <td>1027</td>
          <td>Lentitud al cargar el inventario</td>
          <td>Comercial Vélez</td>
          <td>En progreso</td>
          <td>Alta</td>
          <td>hace 3 días</td>
          <td><a href="/tickets/1027">Ver</a></td>
        </tr>

        <tr>
          <td>1019</td>
          <td>Cambio de RUC en la cuenta</td>
          <td>Panadería Doña Luz</td>
          <td>Resuelto</td>
          <td>Baja</td>
          <td>hace 5 días</td>
          <td><a href="/tickets/1019">Ver</a></td>
        </tr>
      </tbody>
    </table>
  </section>
</main>

<footer>
  <p>Mesa de Ayuda · Proyecto docente 2026-2</p>
  <p>
    Última sincronización:
    <time datetime="2026-09-11T09:40">hoy, 09:40</time>
  </p>
</footer>