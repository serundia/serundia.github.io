<style>
  /* LA INUNDACIÓN DE LUZ SUCIA Y ABRASADORA */
  html, body {
    background-color: #f4f3ef !important; /* Blanco hueso/arena gastada por el sol */
    margin: 0 !important;
    padding: 0 !important;
    width: 100% !important;
    height: 100% !important;
  }

  .bunker-playa {
    position: fixed !important;
    top: 0 !important;
    left: 0 !important;
    width: 100% !important;
    height: 100% !important;
    background-color: #f4f3ef !important;
    z-index: 999999 !important;
    overflow-y: auto !important;
    box-sizing: border-box !important;
    padding: 0 !important;
  }

  /* EL ESPACIO EXTERIOR: EL CARTEL EN EL MEDIO DEVORADO POR EL SOL */
  .contenedor-cartel-playa {
    width: 100% !important;
    height: 100vh !important; /* Ocupa toda la pantalla, puro espacio de luz */
    display: flex !important;
    flex-direction: column !important;
    justify-content: center !important;
    align-items: center !important;
    background-color: #f4f3ef !important;
    padding: 24px !important;
    box-sizing: border-box !important;
    position: relative !important;
  }

  /* EL CARTEL COMIDO POR LA LUZ */
  .cartel-playa {
    color: rgba(38, 38, 38, 0.85) !important; /* Negro ceniza desgastado y translúcido */
    font-family: 'Courier New', Courier, monospace !important;
    font-weight: bold !important;
    text-transform: uppercase !important;
    font-size: 32px !important;
    letter-spacing: 0.3em !important;
    text-align: center !important;
    margin-bottom: 25px !important;
    
    /* Efecto quemado/comido: la luz se traga los bordes */
    filter: blur(0.6px) !important;
    text-shadow: 0 0 12px #f4f3ef, 0 0 4px rgba(38, 38, 38, 0.2) !important;
    user-select: none !important;
  }

  /* LA FLECHA QUE INDICA EL PROPIO CARTEL */
  .flecha-indicadora {
    color: rgba(38, 38, 38, 0.5) !important; /* Más lavada aún por el sol */
    font-family: 'Courier New', Courier, monospace !important;
    font-size: 24px !important;
    margin-bottom: 40px !important;
    transform: rotate(90deg); /* Apunta hacia abajo, directo al cartel */
    animation: vibracion-solar 2s infinite ease-in-out !important; /* Flota temblando por el calor */
  }

  @keyframes vibracion-solar {
    0%, 100% { transform: rotate(90deg) translateY(0); opacity: 0.4; }
    50% { transform: rotate(90deg) translateY(-8px); opacity: 0.7; filter: blur(0.5px); }
  }

  /* LA PROSA BAJO LA ARENA (Aparece haciendo scroll hacia abajo) */
  .playa-contenido {
    max-width: 440px !important;
    margin: 0 auto !important;
    padding: 100px 24px 180px 24px !important;
    font-family: 'Courier New', Courier, monospace !important;
    line-height: 2.3 !important;
    letter-spacing: 0.05em;
  }

  .playa-contenido p {
    color: #4a4946 !important; /* Texto oscuro pero afectado por la claridad */
    font-size: 17px !important;
    margin-bottom: 38px !important;
  }

  /* Señal sutil para volver a encerrarse */
  .playa-volver {
    margin-top: 120px !important;
    border-top: 1px solid #dcdbda !important;
    padding-top: 25px !important;
  }

  .playa-volver a, .playa-volver a:visited {
    color: #9c9b98 !important;
    font-family: 'Courier New', Courier, monospace !important;
    font-size: 14px !important;
    text-decoration: none !important;
    letter-spacing: 0.1em;
    opacity: 0.7;
    transition: color 0.3s;
  }
  
  .playa-volver a:hover {
    color: #262626 !important;
  }
</style>

<div class="bunker-playa">

  <!-- EL EXTERIOR ENCANDILANTE -->
  <div class="contenedor-cartel-playa">
    
    <!-- La flecha que delata al cartel -->
    <div class="flecha-indicadora">←</div>
    
    <!-- El cartel desgastado -->
    <div class="cartel-playa">LA PLAYA</div>
    
  </div>

  <!-- LA PROSA ESCONDIDA EN LA LUZ -->
  <div class="playa-contenido">
    
    <p>AQUÍ VA TU NUEVO TEXTO. El lector se desprende de la imagen quemada del cartel haciendo scroll hacia abajo para empezar a leer tu playa en la claridad sucia.</p>

    <div class="playa-volver">
      <a href="sentimientos-de-culpa.html">[ regresar a la penumbra de la cortina ]</a>
    </div>

  </div>

</div>
