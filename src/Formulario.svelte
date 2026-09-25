<section aria-labelledby="titulo-nuevo">
  <h2 id="titulo-nuevo">Nuevo tutorial</h2>

  <form action="#" method="post">
    <!-- Campo 1: Título (obligatorio) -->
    <label for="titulo">Título del tutorial</label>
    <input type="text" id="titulo" name="titulo" required>

    <!-- Campo 2: Categoría (obligatorio) -->
    <label for="categoria">Categoría</label>
    <select id="categoria" name="categoria" required>
      <option value="">Seleccione una categoría</option>
      <option value="programacion">Programación</option>
      <option value="diseno">Diseño</option>
      <option value="bases-datos">Bases de datos</option>
    </select>

    <!-- Campo 3: Formato (obligatorio) -->
    <label for="formato">Formato</label>
    <select id="formato" name="formato" required>
      <option value="">Seleccione un formato</option>
      <option value="paso-a-paso">Paso a paso</option>
      <option value="video">Video</option>
      <option value="interactivo">Interactivo</option>
    </select>

    <!-- Campo 4: Descripción (opcional) -->
    <label for="descripcion">Descripción o resumen</label>
    <input type="text" id="descripcion" name="descripcion">

    <!-- Botón de envío nativo -->
    <button type="submit">Crear tutorial</button>
  </form>
</section>