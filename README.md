<style>
  /* CREAMOS UN LIENZO NUEVO QUE TAPA ABSOLUTAMENTE TODO LO DE GITHUB */
  html, body {
    background-color: #0d0d0d !important;
    margin: 0 !important;
    padding: 0 !important;
    width: 100% !important;
    height: 100% !important;
  }

  /* Este contenedor creará tu búnker limpio desde el borde superior de la pantalla */
  .bunker-literario {
    position: fixed !important;
    top: 0 !important;
    left: 0 !important;
    width: 100% !important;
    height: 100% !important;
    background-color: #0d0d0d !important;
    z-index: 999999 !important; /* Se coloca por encima de absolutamente todo */
    overflow-y: auto !important; /* Permite hacer scroll si el texto es largo */
    box-sizing: border-box !important;
    padding: 80px 24px !important;
  }

  /* El contenedor del texto centrado */
  .bunker-contenido {
    max-width: 650px !important;
    margin: 0 auto !important;
    font-family: 'Courier New', Courier, monospace !important;
    line-height: 2.2 !important;
    letter-spacing: 0.05em;
  }
  
  /* Tu color morado amatista desgastado */
  .bunker-contenido, .bunker-contenido p, .bunker-contenido div {
    color: #b3a7c4 !important; 
    font-family: 'Courier New', Courier, monospace !important;
    font-size: 17px !important;
  }

  /* Título en un lavanda pálido, en mayúsculas, sin negrita y separado del texto */
  .bunker-titulo {
    color: #d1c7e0 !important; 
    font-family: 'Courier New', Courier, monospace !important;
    font-weight: normal !important;
    text-transform: uppercase;
    text-decoration: none !important;
    border-bottom: none !important;
    margin-bottom: 50px !important; /* Espacio extra debajo del título */
    font-size: 18px !important;
    letter-spacing: 0.08em;
  }

  /* Forzar el espacio vertical entre párrafos individuales */
  .bunker-contenido p {
    margin-bottom: 35px !important;
  }
</style>

<div class="bunker-literario">
  <div class="bunker-contenido">

    <div class="bunker-titulo">SENTIMIENTOS DE CULPA</div>

    <p>Lavarme los dientes. Dar el paso. Mover el aire. Recordar. Recordar a los demás. Una flecha encorvada que sale de un agujero negro. Y frente al espejo: ¿me estrello o me quedo inmóvil?</p>

    <p>Me duelen los 52 huesos de los pies. Si es que no me falta ninguno. En el cuello: falta la segunda vértebra. Otro diagnóstico tardío.</p>

    <p>Estoy cambiando la piel y duele.</p>

    <p>No quiero abrir las cortinas. Prefiero seguir respirando mis propios desechos.</p>

    <p>Podría quitar las sillas y obtener más espacio. Estar sentada me distrae.</p>

    <p>¿Qué más puedo quitar?</p>

    <p>No es que no me gusten los objetos. Es que me aburren.</p>

    <p>¿Hay culpa en eso?</p>

    <p>En querer perder las cosas.</p>

    <p>Siento una culpable libertad cada vez que algo se rompe.</p>

    <p>Últimamente tiro los platos en vez de lavarlos.</p>

    <p>Tampoco me lavo mucho los dientes.</p>

  </div>
</div>
