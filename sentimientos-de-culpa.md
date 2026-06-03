
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
    padding: 0 !important; /* Quitamos el padding fijo para controlar el espacio con el scroll */
  }

  /* EL ESPACIO INICIAL PARA EL TÍTULO */
  .contenedor-titulo-culpa {
    width: 100% !important;
    height: 100vh !important; /* Ocupa la pantalla entera al entrar */
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

  /* EL CONTENIDO MORADO TRAS EL ENORME ESPACIO NEGRO */
  .bunker-contenido {
    max-width: 440px !important; 
    margin: 0 auto !important;
    padding: 100px 24px 150px 24px !important; /* Espacio antes y después de la prosa */
    font-family: 'Courier New', Courier, monospace !important;
    line-height: 2.3 !important;
    letter-spacing: 0.05em;
  }
  .bunker-contenido p {
    color: #b3a7c4 !important; 
    font-size: 17px !important;
    margin-bottom: 38px !important;
  }

  /* LA FISURA DE LA CORTINA */
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
    transition: width 0.2s, left 0.2s;
  }
  .cortina-abstracta:hover {
    width: 6px !important;
    left: 13px !important;
    box-shadow: 0 0 25px #ffffff, 0 0 40px rgba(255,255,255,0.6) !important;
  }

  @keyframes cortocircuito-lineal {
    0%, 100% { opacity: 0.9; transform: scaleX(1); }
    7% { opacity: 0.2; transform: scaleX(0.7); }
    10% { opacity: 1; transform: scaleX(1.2); }
    14% { opacity: 0.1; transform: scaleX(0.5); }
    18% { opacity: 0.9; transform: scaleX(1); }
    50% { opacity: 0.8; transform: scaleX(0.9); }
    82% { opacity: 0.3; transform: scaleX(0.6); }
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
  .bunker-volver a:hover {
    opacity: 1 !important;
    color: #ff3366 !important;
  }

  @media (max-width: 768px) {
    .cortina-abstracta { left: 4px !important; width: 2px !important; }
  }
</style>

<div class="bunker-literario">
  
  <a href="la-playa.html" class="cortina-abstracta" title="Correr la cortina"></a>

  <!-- IMPACTO DEL TÍTULO -->
  <div class="contenedor-titulo-culpa">
    <span class="titulo-naranja">SENTIMIENTOS DE CULPA</span>
  </div>

  <!-- EL ABISMO SE RECORRE HACIENDO SCROLL HACIA ABAJO -->
  <div class="bunker-contenido">
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
