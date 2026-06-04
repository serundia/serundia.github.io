<style>
  /* LA NOCHE LUMINOSA */
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
    background: radial-gradient(circle, rgba(240,245,255,0.18) 0%, rgba(6,10,20,1) 75%) !important;
    z-index: 999999 !important;
    overflow-y: auto !important;
    box-sizing: border-box !important;
    padding: 0 !important;
  }

  /* CARTEL A PANTALLA COMPLETA */
  .contenedor-cartel-gato {
    width: 100% !important;
    height: 100vh !important;
    display: flex !important;
    justify-content: center !important;
    align-items: center !important;
    box-sizing: border-box;
  }

  /* EL CARTEL EN UN NARANJA CON DESTELLO DE LUZ FRÍA */
  .cartel-gato {
    color: #ff6633 !important; /* Volvemos al naranja encendido */
    font-family: 'Courier New', Courier, monospace !important;
    font-weight: bold !important;
    text-transform: uppercase !important;
    font-size: 28px !important;
    letter-spacing: 0.3em !important;
    text-align: center !important;
    filter: blur(0.3px) !important;
    /* La luz blanca del fondo sigue envolviendo las letras naranjas */
    text-shadow: 0 0 15px rgba(255, 255, 255, 0.5), 0 0 30px #ff6633 !important;
    user-select: none !important;
  }

  /* LA PROSA EN LETRAS FRÍAS */
  .recuerdo-contenido {
    max-width: 440px !important;
    margin: 0 auto !important;
    padding: 100px 24px 180px 24px !important;
    font-family: 'Courier New', Courier, monospace !important;
    line-height: 2.3 !important;
    letter-spacing: 0.05em;
  }

  .recuerdo-contenido p {
    color: #8fa0b5 !important; /* Gris azulado pálido */
    font-size: 17px !important;
    margin-bottom: 38px !important;
  }

  .recuerdo-volver {
    margin-top: 120px !important;
    border-top: 1px solid #141f30 !important;
    padding-top: 25px !important;
  }

  .recuerdo-volver a, .recuerdo-volver a:visited {
    color: #4b5c73 !important;
    font-family: 'Courier New', Courier, monospace !important;
    font-size: 14px !important;
    text-decoration: none !important;
    letter-spacing: 0.1em;
  }
  
  .recuerdo-volver a:hover {
    color: #ff6633 !important;
    text-shadow: 0 0 8px #ff6633 !important;
  }
</style>

<div class="bunker-recuerdo">

  <!-- EL CARTEL CORREGIDO: EL GATO NARANJA -->
  <div class="contenedor-cartel-gato">
    <div class="cartel-gato">EL GATO NARANJA</div>
  </div>

  <!-- LA PROSA SÓLA EN SU NOCHE -->
  <div class="recuerdo-contenido">
    
    <p>Si golpeaba las manos al as 12, Lara iba a volver. Llegaría corriendo. Por la derecha, por donde se iba al supermercado. Con la cabeza entre las rejas. Un ritual navideño. Mamá me acompañaba. Se iba después del primer aplauso.<br>
    Nunca apareció.<br>
    No lloraba por eso.</p>

    <p>Lloré cuando abandonamos al gato naranja. Que en cambio volvió.<br>
    Me quedo sin texto.</p>

    <p>La vida es cruel cuando es tierna.<br>
    Tener hijos es lo más tierno.<br>
    También se abandonan los hijos.<br>
    Me costaba tirar la cucharita del helado, la tirábamos juntas. Mi hermana y yo.</p>

    <p>Bajé al gato naranja del coche. Sin bajarme. Empecé a llorar seis horas más tarde. Justo a las 12.</p>

    <div class="recuerdo-volver">
      <a href="sentimientos-de-culpa.html">[ regresar a la penumbra de la cortina ]</a>
    </div>

  </div>

</div>
