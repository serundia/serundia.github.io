<style>
  /* LA NOCHE LUMINOSA - COLORES MANTENIDOS */
  html, body {
    background-color: #060a14 !important; /* El azul noche asfáltico mate */
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
    color: #ff6633 !important; /* Naranja intacto */
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
    color: #ffcc00 !important; /* Amarillo semáforo intacto */
    font-size: 17px !important;
    margin-bottom: 24px !important;
    text-shadow: 0 0 1px rgba(255, 204, 0, 0.3) !important;
  }

  /* BOTÓN SALIR: CLONADO EXACTO DE ENTRAR */
  .recuerdo-volver {
    margin-top: 120px !important;
    text-align: center !important; /* Centrado como en el vestíbulo */
  }

  .recuerdo-volver a, .recuerdo-volver a:visited {
    display: inline-block !important;
    color: #ff3366 !important; /* El rojo/rosa de Serundia */
    font-family: 'Courier New', Courier, monospace !important;
    font-size: 16px !important;
    font-weight: bold !important;
    text-transform: uppercase !important;
    letter-spacing: 0.2em !important;
    text-decoration: none !important;
    border: 2px solid #ff3366 !important;
    padding: 12px 34px !important;
    border-radius: 4px !important;
    transition: background-color 0.3s, color 0.3s, box-shadow 0.3s !important;
    box-shadow: 0 0 10px rgba(255, 51, 102, 0.2) !important;
  }
  
  .recuerdo-volver a:hover {
    background-color: #ff3366 !important;
    color: #060a14 !important; /* Fondo oscuro del búnker para el contraste */
    box-shadow: 0 0 20px #ff3366, 0 0 40px rgba(255, 51, 102, 0.6) !important;
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

    <!-- EL BOTÓN SALIR EN ROJO DE SERUNDIA, CENTRADO Y ROTUNDO -->
    <div class="recuerdo-volver">
      <a href="index.html">SALIR</a>
    </div>

  </div>

</div>
