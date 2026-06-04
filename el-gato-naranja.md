<style>
  /* LA NOCHE LUMINOSA - COLORES MANTENIDOS */
  html, body {
    background-color: #060a14 !important;
    margin: 0 !important;
    padding: 0 !important;
    width: 100% !important;
    height: 100% !important;
  }

  .bunker-recuerdo {
    position: fixed !important;
    top: 0 !important;
    left: 0 !important;
    width: 100% !important;
    height: 100% !important;
    background-color: #060a14 !important;
    z-index: 999999 !important;
    overflow-y: auto !important;
    box-sizing: border-box !important;
    padding: 0 !important;
  }

  /* EL CARTEL EN EL MEDIO */
  .contenedor-cartel-gato {
    width: 100% !important;
    height: 100vh !important;
    display: flex !important;
    justify-content: center !important;
    align-items: center !important;
    box-sizing: border-box;
  }

  /* EL CARTEL EN NARANJA CON EL DESTELLO BLANCO LUNA */
  .cartel-gato {
    color: #ff6633 !important;
    font-family: 'Courier New', Courier, monospace !important;
    font-weight: bold !important;
    text-transform: uppercase !important;
    font-size: 28px !important;
    letter-spacing: 0.3em !important;
    text-align: center !important;
    filter: blur(0.3px) !important;
    text-shadow: 0 0 15px rgba(255, 255, 255, 0.7), 0 0 35px #ff6633 !important;
    user-select: none !important;
  }

  /* LA PROSA EN AMARILLO SEMÁFORO - ORACIONES EN UNA SOLA LÍNEA */
  .recuerdo-contenido {
    max-width: 440px !important;
    margin: 0 auto !important;
    padding: 100px 24px 180px 24px !important;
    font-family: 'Courier New', Courier, monospace !important;
    line-height: 2.3 !important;
    letter-spacing: 0.05em;
  }

  .recuerdo-contenido p {
    color: #ffcc00 !important;
    font-size: 17px !important;
    margin-bottom: 24px !important;
    text-shadow: 0 0 1px rgba(255, 204, 0, 0.3) !important;
  }

  /* BOTÓN SALIR: MÁS CHICO Y CON EL COLOR IDÉNTICO A SERUNDIA */
  .recuerdo-volver {
    margin-top: 140px !important;
    text-align: center !important;
  }

  .recuerdo-volver a, .recuerdo-volver a:visited {
    display: inline-block !important;
    color: #ff0055 !important; /* El fucsia/rosa idéntico de Serundia */
    font-family: 'Courier New', Courier, monospace !important;
    font-size: 13px !important; /* Más pequeño y sutil */
    font-weight: bold !important;
    text-transform: uppercase !important;
    letter-spacing: 0.2em !important;
    text-decoration: none !important;
    border: 1.5px solid #ff0055 !important; /* Línea más fina */
    padding: 8px 24px !important; /* Menos relleno, más compacto */
    border-radius: 4px !important;
    transition: background-color 0.3s, color 0.3s, box-shadow 0.3s !important;
    box-shadow: 0 0 8px rgba(255, 0, 85, 0.15) !important;
  }
  
  .recuerdo-volver a:hover {
    background-color: #ff0055 !important;
    color: #060a14 !important;
    box-shadow: 0 0 15px #ff0055, 0 0 30px rgba(255, 0, 85, 0.5) !important;
  }
</style>

<div class="bunker-recuerdo">

  <!-- EL CARTEL -->
  <div class="contenedor-cartel-gato">
    <div class="cartel-gato">EL GATO NARANJA</div>
  </div>

  <!-- LA PROSA FRAGMENTADA -->
  <div class="recuerdo-contenido">
    
    <p>Si golpeaba las manos a las 12, Lara iba a volver.</p>
    <p>Llegaría corriendo.</p>
    <p>Por la derecha, por donde se iba al supermercado.</p>
    <p>Con la cabeza entre las rejas.</p>
    <p>Un ritual navideño.</p>
    <p>Mamá me acompañaba.</p>
    <p>Se iba después del primer aplauso.</p>
    <p>Nunca apareció. Lara.</p>
    <p>No lloraba por eso.</p>
    <br>
    <p>Lloré cuando abandonamos al gato naranja.</p>
    <p>Que en cambio volvió.</p>
    <p>Me quedo sin texto.</p>
    <br>
    <p>La vida es cruel cuando es tierna.</p>
    <p>Tener hijos es lo más tierno.</p>
    <p>También se abandonan los hijos.</p>
    <p>Me costaba tirar la cucharita del helado, la tirábamos juntas.</p>
    <p>Mi hermana y yo.</p>
    <br>
    <p>Bajé al gato naranja del coche.</p>
    <p>Sin bajarme.</p>
    <p>Empecé a llorar seis horas más tarde.</p>
    <p>Justo a las 12.</p>

    <!-- EL BOTÓN SALIR AJUSTADO Y DE MARCA -->
    <div class="recuerdo-volver">
      <a href="index.html">SALIR</a>
    </div>

  </div>

</div>
