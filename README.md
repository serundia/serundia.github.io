<style>
  /* CREAMOS UN LIENZO NUEVO QUE TAPA ABSOLUTAMENTE TODO LO DE GITHUB */
  html, body {
    background-color: #0d0d0d !important;
    margin: 0 !important;
    padding: 0 !important;
    width: 100% !important;
    height: 100% !important;
  }

  /* Contenedor que centra el cartel exactamente en mitad de la pantalla */
  .bunker-entrada {
    position: fixed !important;
    top: 0 !important;
    left: 0 !important;
    width: 100% !important;
    height: 100% !important;
    background-color: #0d0d0d !important;
    z-index: 999999 !important;
    display: flex !important;
    flex-direction: column !important;
    justify-content: center !important;
    align-items: center !important;
    box-sizing: border-box !important;
    padding: 24px !important;
  }

  /* Tu nombre en un rojo frío y luminoso (carmín/neón) */
  .cartel-luminoso {
    color: #ff3366 !important; 
    font-family: 'Courier New', Courier, monospace !important;
    font-weight: normal !important;
    text-transform: uppercase;
    font-size: 26px !important; /* Un punto más de tamaño para el neón */
    letter-spacing: 0.25em; /* Letras expandidas de cartel */
    margin-bottom: 35px !important;
    text-shadow: 0 0 10px rgba(255, 51, 102, 0.3) !important; /* Ligero destello de tubo de neón */
  }

  /* El picaporte sutil en la gama de los rojos fríos apagados */
  .picaporte a, .picaporte a:visited {
    color: #a63a50 !important;
    font-family: 'Courier New', Courier, monospace !important;
    font-size: 14px !important;
    text-decoration: none !important;
    letter-spacing: 0.1em;
    opacity: 0.6;
    transition: opacity 0.3s, color 0.3s;
  }
  
  .picaporte a:hover {
    opacity: 1 !important;
    color: #ff3366 !important; /* Se enciende al pasar el cursor */
  }
</style>

<div class="bunker-entrada">
  <div class="cartel-luminoso">SERUNDIA</div>
  <div class="picaporte">
    <a href="sentimientos-de-culpa.html">[ entrar ]</a>
  </div>
</div>
