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