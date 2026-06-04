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
    padding: 0 !important;
  }

  .contenedor-titulo-culpa {
    width: 100% !important;
    height: 100vh !important;
    display: flex !important;
    justify-content: center !important;
    align-items: center !important;
    background-color: #0d0d0d !important;
  }

  .titulo-naranja {
    color: #ff6633 !important;
    font-family: 'Courier New', Courier, monospace !important;
    font-weight: normal !important;
    text-transform: uppercase !important;
    font-size: 19px !important;
    letter-spacing: 0.15em !important;
    text-align: center !important;
  }

  .bunker-contenido {
    max-width: 440px !important; 
    margin: 0 auto !important;
    padding: 100px 24px 150px 24px !important;
    font-family: 'Courier New', Courier, monospace !important;
    line-height: 2.3 !important;
    letter-spacing: 0.05em;
    position: relative !important;
  }
  .bunker-contenido p {
    color: #b3a7c4 !important; 
    font-size: 17px !important;
  }

  /* IZQUIERDA: LA CORTINA HACIA LA PLAYA */
  .cortina-abstracta {
    display: block !important;
    position: fixed !important;
    top: 0 !important;
    left: 15px !important;
    width: 3px !important;
    height: 100% !important;
    background: linear-gradient(to bottom, #ffffff 20%, #e6e6e6 50%, #ffffff 80%) !important;
    border-radius: 2px 4px 1px 3px !important;
    box-shadow: -1px 0 15px rgba(255,255,255,0.8), 2px 0 8px rgba(255,255,255,0.4) !important;
    animation: cortocircuito-lineal 2s infinite alternate !important;
    cursor: pointer;
    z-index: 1000000 !important;
  }

  /* DERECHA: "MEMORIA" REUBICADA MÁS ABAJO Y AL MARGEN */
  .puerta-recuerdo {
    display: block !important;
    position: fixed !important;
    bottom: 40px !important; /* Desplazada hacia el suelo de la pantalla */
    right: 25px !important;  /* Más pegada al margen derecho */
    color: #cccccc !important; 
    text-shadow: 1px 1px 2px rgba(255,255,255,0.2) !important;
    font-family: 'Courier New', Courier, monospace !important;
    font-size: 14px !important;
    font-weight: bold !important;
    text-transform: uppercase !important;
    letter-spacing: 0.2em !important;
    text-decoration: none !important;
    opacity: 0.4;
    z-index: 1000000 !important;
    transition: opacity 0.3s, color 0.3s, text-shadow 0.3s;
  }
  .puerta-recuerdo:hover {
    opacity: 1 !important;
    color: #ffffff !important; 
    text-shadow: 0 0 8px #ffffff, 0 0 15px rgba(200,200,200,0.5) !important;
  }

  @keyframes cortocircuito-lineal {
    0%, 100% { opacity: 0.9; transform: scaleX(1); }
    7% { opacity: 0.2; transform: scaleX(0.7); }
    10% { opacity: 1; transform: scaleX(1.2); }
    14% { opacity: 0.1; transform: scaleX(0.5); }
    50% { opacity: 0.8; transform: scaleX(0.9); }
    86% { opacity: 1; transform: scaleX(1.3); }
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

  @media (max-width: 900px) {
    .puerta-recuerdo { position: static !important; display: block !important; margin-top: 40px; text-align: right; }
    .cortina-abstracta { left: 4px !important; width: 2px !important; }
  }
</style>

<div class="bunker-literario">
  
  <!-- INTERFERENCIAS LATERALES -->
  <a href="la-playa.html" class="cortina-abstracta" title="Abrir la cortina (La Playa)"></a>
  <a href="el-gato-naranja.html" class="puerta-recuerdo">MEMORIA</a>

  <div class="contenedor-titulo-culpa">
    <span class="titulo-naranja">SENTIMIENTOS DE CULPA</span>
  </div>

  <div class="bunker-contenido">
    <p>Lavarme los dientes. Dar el paso. Mover el aire. Recordar. Recordar a los demás. Una flecha encorvada que sale del agujero negro. Y frente al espejo: ¿me estrello o me quedo inmóvil?</p>
    <br><br>
    <p>Me duelen los 52 huesos de los pies. Si es que no me falta ninguno. En el cuello: falta la segunda vértebra. Otro diagnóstico tardío.</p>
    <br><br>
    <p>Estoy cambiando la piel y duele.</p>
    <br><br>
    <p>No quiero abrir las cortinas. Prefiero seguir respirando mis propios desechos.</p>
    <br><br>
    <p>Podría quitar las sillas y obtener más espacio. Estar sentada me distrae.</p>
    <br><br>
    <p>¿Qué más puedo quitar?</p>
    <br><br>
    <p>No es que no me gusten los objetos. Es que me aburren.</p>
    <br><br>
    <p>¿Hay culpa en eso?</p>
    <br><br>
    <p>En querer perder las cosas.</p>
    <br><br>
    <p>Siento una culpable libertad cada vez que algo se rompe.</p>
    <br><br>
    <p>Últimamente tiro los platos en vez de lavarlos.</p>
    <br><br>
    <p>Tampoco me lavo mucho los dientes.</p>

    <div class="bunker-volver">
      <a href="index.html">[ volver al vestíbulo ]</a>
    </div>
  </div>
</div>

