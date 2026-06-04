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
  }
  .bunker-contenido p {
    color: #b3a7c4 !important; 
    font-size: 17px !important;
  }

  /* LA CORTINA DE LA PLAYA (IZQUIERDA) */
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

  /* EL SEMÁFORO DE 2 LUCES (ABAJO A LA DERECHA) */
  .contenedor-semaforo {
    margin-top: 100px !important;
    display: flex !important;
    justify-content: flex-end !important;
    width: 100% !important;
    border-top: 1px solid #1a1a1a !important;
    padding-top: 40px !important;
  }

  .semaforo-caja {
    background-color: #151515 !important;
    border: 2px solid #262626 !important;
    border-radius: 6px !important;
    padding: 10px 8px !important;
    display: flex !important;
    flex-direction: column !important;
    gap: 12px !important;
    width: 32px !important;
    align-items: center !important;
    box-shadow: 0 4px 12px rgba(0,0,0,0.5) !important;
  }

  .luz {
    width: 18px !important;
    height: 18px !important;
    border-radius: 50% !important;
    display: block !important;
    transition: transform 0.2s, filter 0.2s;
  }

  /* ROJO: RETORNO AL VESTÍBULO */
  .luz-roja {
    background-color: #ff3333 !important;
    box-shadow: 0 0 8px #ff3333, inset 0 0 4px rgba(255,255,255,0.6) !important;
  }

  /* AMARILLO: RECUERDOS (PARPADEO DE PRECAUCIÓN) */
  .luz-amarilla {
    background-color: #ffcc00 !important;
    box-shadow: 0 0 8px #ffcc00, inset 0 0 4px rgba(255,255,255,0.6) !important;
    animation: parpadeo-semaforo 1.5s infinite alternate !important;
  }

  .semaforo-caja a:hover .luz-roja {
    transform: scale(1.15);
    filter: brightness(1.3) drop-shadow(0 0 6px #ff3333) !important;
  }

  .semaforo-caja a:hover .luz-amarilla {
    transform: scale(1.15);
    filter: brightness(1.3) drop-shadow(0 0 6px #ffcc00) !important;
  }

  @keyframes parpadeo-semaforo {
    0%, 100% { opacity: 1; filter: brightness(1); }
    50% { opacity: 0.7; filter: brightness(0.8); }
  }

  @keyframes cortocircuito-lineal {
    0%, 100% { opacity: 0.9; transform: scaleX(1); }
    7% { opacity: 0.2; transform: scaleX(0.7); }
    10% { opacity: 1; transform: scaleX(1.2); }
    14% { opacity: 0.1; transform: scaleX(0.5); }
    50% { opacity: 0.8; transform: scaleX(0.9); }
  }

  @media (max-width: 768px) {
    .cortina-abstracta { left: 4px !important; width: 2px !important; }
  }
</style>

<div class="bunker-literario">
  
  <a href="la-playa.html" class="cortina-abstracta" title="Abrir la cortina (La Playa)"></a>

  <!-- TÍTULO -->
  <div class="contenedor-titulo-culpa">
    <span class="titulo-naranja">SENTIMIENTOS DE CULPA</span>
  </div>

  <!-- TEXTO -->
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

    <!-- EL SEMÁFORO REGULADOR DE DOS POSICIONES -->
    <div class="contenedor-semaforo">
      <div class="semaforo-caja">
        <!-- Luz Roja: Regresa al vestíbulo -->
        <a href="index.html" title="Frenar - Volver a la entrada de Serundia">
          <span class="luz luz-roja"></span>
        </a>
        <!-- Luz Amarillo Semáforo: Conecta con los recuerdos -->
        <a href="el-gato-naranja.html" title="Precaución - Abrir los Recuerdos">
          <span class="luz luz-amarilla"></span>
        </a>
      </div>
    </div>

  </div>
</div>
