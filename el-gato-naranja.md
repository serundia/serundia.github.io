<style>
  html, body {
    background-color: #0d0d0d !important;
    margin: 0 !important;
    padding: 0 !important;
    width: 100% !important;
    height: 100% !important;
  }
  .bunker-gato {
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

  .gato-contenido {
    max-width: 680px !important; 
    margin: 0 auto !important;
    padding: 140px 24px 150px 24px !important;
    font-family: 'Courier New', Courier, monospace !important;
    line-height: 2.3 !important;
    letter-spacing: 0.05em;
  }

  .gato-contenido p {
    color: #ff7675 !important; /* Tu fucsia/coral gastado original */
    font-size: 16px !important;
    margin-bottom: 0 !important;
  }

  /* EL ESPACIO EN BLANCO PARA DEJAR "ME QUEDO SIN TEXTO" EN EL MEDIO */
  .linea-aislada {
    margin-top: 100px !important;    /* Distancia generosa por arriba */
    margin-bottom: 100px !important; /* Distancia generosa por abajo */
    text-align: center !important;   /* Centrado para romper la línea de lectura */
  }

  .recuerdo-volver {
    margin-top: 120px !important;
    border-top: 1px solid #333 !important;
    padding-top: 30px !important;
    display: flex !important;
    justify-content: space-between !important;
    font-family: 'Courier New', Courier, monospace !important;
    font-size: 14px !important;
    letter-spacing: 0.1em;
  }

  .recuerdo-volver a, .recuerdo-volver a:visited {
    color: #ff7675 !important;
    text-decoration: none !important;
    font-weight: bold !important;
  }
  
  .recuerdo-volver a:hover {
    color: #ffffff !important;
  }

  @media (max-width: 768px) {
    .gato-contenido { max-width: 100% !important; }
  }
</style>

<div class="bunker-gato">
  <div class="gato-contenido">

    <!-- PRIMER BLOQUE -->
    <p>
      Si golpeaba las manos a las 12, Lara iba a volver.<br>
      Llegaría corriendo.<br>
      Por la derecha, por donde se iba al supermercado.<br>
      Con la cabeza entre las rejas.<br>
      Un ritual navideño.<br>
      Mamá me acompañaba.<br>
      Se iba después del primer aplauso.<br>
      Nunca apareció. Lara.<br>
      No lloraba por eso.
    </p>

    <br><br>

    <!-- SEGUNDO BLOQUE -->
    <p>
      Lloré cuando abandonamos al gato naranja.<br>
      Que en cambio volvió.
    </p>

    <!-- LA FRASE AISLADA EN MEDIO DEL ABISMO -->
    <p class="linea-aislada">Me quedo sin texto.</p>

    <!-- TERCER BLOQUE -->
    <p>
      La vida es cruel cuando es tierna.<br>
      Tener hijos es lo más tierno.<br>
      También se abandonan los hijos.<br>
      Me costaba tirar la cucharita del helado, la tirábamos juntas.<br>
      Mi hermana y yo.
    </p>

    <br><br>

    <!-- CUARTO BLOQUE -->
    <p>
      Bajé al gato naranja del coche.<br>
      Sin bajarme.<br>
      Empecé a llorar seis horas más tarde.<br>
      Justo a las 12.
    </p>

    <!-- LAS DOS OPCIONES DE SALIDA -->
    <div class="recuerdo-volver">
      <a href="index.html">[ salir ]</a>
      <a href="primavera.html">[ seguir ]</a>
    </div>

  </div>
</div>
