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

  .bunker-contenido {
    max-width: 680px !important; 
    margin: 0 auto !important;
    padding: 140px 24px 150px 24px !important;
    font-family: 'Courier New', Courier, monospace !important;
    line-height: 2.3 !important;
    letter-spacing: 0.05em;
  }

  .titulo-morado {
    color: #b3a7c4 !important; 
    font-size: 19px !important;
    text-transform: uppercase !important;
    letter-spacing: 0.15em !important;
    text-align: center !important;
    display: block !important;
    margin-bottom: 40px !important; 
  }

  .bunker-contenido p {
    color: #b3a7c4 !important; 
    font-size: 16px !important;
    margin-bottom: 24px !important;
  }

  /* LA CORTINA: LÍNEA VERTICAL ANCHA Y PARPADEANTE */
  .cortina-luz {
    display: block !important;
    position: fixed !important;
    top: 0 !important;
    bottom: 0 !important;
    right: 80px !important; /* Separada elegantemente a la derecha */
    width: 12px !important;  /* Línea notablemente más ancha */
    background-color: #ffffff !important;
    box-shadow: 0 0 15px rgba(255, 255, 255, 0.8), 0 0 30px rgba(255, 255, 255, 0.4) !important;
    cursor: pointer !important;
    z-index: 1000000 !important;
    animation: parpadeo-cortina 4s infinite ease-in-out !important; /* Simula el movimiento del viento */
    transition: opacity 0.3s, width 0.3s !important;
  }

  .cortina-luz:hover {
    width: 16px !important; /* Se ensancha sutilmente al pasar el cursor */
    box-shadow: 0 0 25px rgba(255, 255, 255, 1), 0 0 40px rgba(255, 255, 255, 0.6) !important;
  }

  /* ANIMACIÓN ASIMÉTRICA DE PARPADEO (EFECTO TELA) */
  @keyframes parpadeo-cortina {
    0%, 100% { opacity: 0.3; }
    15% { opacity: 0.75; }
    30% { opacity: 0.4; }
    45% { opacity: 0.85; }
    60% { opacity: 0.35; }
    80% { opacity: 0.9; }
  }

  @media (max-width: 768px) {
    .cortina-luz { right: 15px !important; width: 8px !important; }
    .bunker-contenido { max-width: 100% !important; }
  }
</style>

<div class="bunker-literario">
  
  <!-- LA CORTINA QUE TE LLEVA A LA PLAYA -->
  <a href="la-playa.html" class="cortina-luz" title="Cruzar la cortina (La Playa)"></a>

  <div class="bunker-contenido">
    
    <span class="titulo-morado">CULPA</span>

    <p>Lavarme los dientes. Dar el paso. Mover el aire. Recordar. Recordar a los demás.</p>
    <br>
    <p>Una flecha encorvada que sale de un agujero negro. Me estrello o me quedo inmóvil.</p>
    <br>
    <p>Me duelen los 52 huesos de los pies. Si es que no me falta ninguno. Tengo una vértebra menos. Otro diagnóstico tardío.</p>
    <br>
    <p>No voy a correr la cortina.</p>
    <br>
    <p>Podría quitar las sillas y obtener más espacio. Sentada me distraigo.</p>
    <p>¿Qué más puedo quitar?</p>
    <p>No es que no me gusten los objetos. Es que me aburren.</p>
    <p>¿Hay culpa en eso? En querer perder las cosas.</p>
    <br>
    <p>Siento una culpable libertad cada vez que algo se rompe.</p>
    <p>Ultimamente tiro los platos en vez de lavarlos.</p>
    <p>Tampoco me lavo mucho los dientes.</p>
  </div>

</div>
