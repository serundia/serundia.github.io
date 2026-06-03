<style>
  html, body {
    background-color: #0d0d0d !important;
    margin: 0 !important;
    padding: 0 !important;
    width: 100% !important;
    height: 100% !important;
  }
  .bunker-literario {
    position: fixed !important;
    top: 0 !important;
    left: 0 !important;
    width: 100% !important;
    height: 100% !important;
    background-color: #0d0d0d !important;
    z-index: 999999 !important;
    overflow-y: auto !important;
    box-sizing: border-box !important;
    padding: 140px 24px !important;
  }
  .bunker-contenido {
    max-width: 440px !important; 
    margin: 0 auto !important;
    font-family: 'Courier New', Courier, monospace !important;
    line-height: 2.3 !important;
    letter-spacing: 0.05em;
    position: relative !important; /* Base para calcular el costado */
  }
  .bunker-contenido p {
    color: #b3a7c4 !important; 
    font-family: 'Courier New', Courier, monospace !important;
    font-size: 17px !important;
    margin-bottom: 38px !important;
  }
  .titulo-naranja {
    color: #ff6633 !important;
    font-family: 'Courier New', Courier, monospace !important;
    font-weight: normal !important;
    text-transform: uppercase !important;
    font-size: 19px !important;
    letter-spacing: 0.15em !important;
    margin-bottom: 70px !important;
    display: block !important;
  }

  /* LA DISTRACCIÓN FIJA A LA IZQUIERDA */
  .puerta-blanca {
    display: block !important;
    position: fixed !important;
    /* Se posiciona a la izquierda del texto, con una distancia prudente */
    top: 45% !important;
    left: calc(50% - 360px) !important; 
    width: 35px !important;
    height: 55px !important;
    background-color: #ffffff !important;
    box-shadow: 0 0 20px #ffffff, 0 0 40px #ffffff !important;
    animation: chispazo 1.2s infinite alternate !important; /* Parpadeo un poco más errático */
    cursor: pointer;
    transition: transform 0.3s;
    z-index: 1000000 !important;
  }
  
  .puerta-blanca:hover {
    transform: scale(1.1);
    box-shadow: 0 0 35px #ffffff, 0 0 70px #ffffff !important;
  }

  /* CORTOCIRCUITO VISUAL COPORTÁNDOSE MAL */
  @keyframes chispazo {
    0%, 100% { opacity: 1; }
    8% { opacity: 0.2; }
    12% { opacity: 1; }
    18% { opacity: 0.1; }
    24% { opacity: 1; }
    75% { opacity: 0.9; }
    80% { opacity: 0.3; }
    85% { opacity: 1; }
  }

  .bunker-volver {
    margin-top: 100px !important;
    border-top: 1px solid #1a1a1a !important;
    padding-top: 25px !important;
    width: 100%;
  }
  .bunker-volver a, .bunker-volver a:visited {
    color: #a63a50 !important;
    font-family: 'Courier New', Courier, monospace !important;
    font-size: 14px !important;
    text-decoration: none !important;
    letter-spacing: 0.1em;
    opacity: 0.5;
  }
  .bunker-volver a:hover {
    opacity: 1 !important;
    color: #ff3366 !important;
  }

  /* Ajuste para pantallas medianas/pequeñas para que no choque con el texto */
  @media (max-width: 900px) {
    .puerta-blanca {
      position: static !important;
      margin: 0 0 50px 0 !important;
    }
  }
</style>

<div class="bunker-literario">
  
  <!-- LA SEÑALÉTICA DE DISTRACCIÓN (FLOTANDO AL COSTADO) -->
  <a href="la-playa.html" class="puerta-blanca" title="Salir a la luz"></a>

  <div class="bunker-contenido">
    <span class="titulo-naranja">SENTIMIENTOS DE CULPA</span>
    
    <p>Lavarme los dientes. Dar el paso. Mover el aire. Recordar. Recordar a los demás. Una flecha encorvada que sale del agujero negro. Y frente al espejo: ¿me estrello o me quedo inmóvil?</p>
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

    <div class="bunker-volver">
      <a href="index.html">[ volver al vestíbulo ]</a>
    </div>
  </div>
</div>
