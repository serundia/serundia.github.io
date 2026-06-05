
<style>
  html, body {
    background-color: #eae6df !important;
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
    background-color: #eae6df !important;
    z-index: 999999 !important;
    overflow-y: auto !important;
    box-sizing: border-box !important;
    padding: 0 !important;
  }

  .contenedor-titulo-playa {
    width: 100% !important;
    height: 100vh !important;
    display: flex !important;
    justify-content: center !important;
    align-items: center !important;
    background-color: #eae6df !important;
  }

  .titulo-azul {
    color: #4b6584 !important;
    font-family: 'Courier New', Courier, monospace !important;
    font-weight: normal !important;
    text-transform: uppercase !important;
    font-size: 19px !important;
    letter-spacing: 0.15em !important;
    text-align: center !important;
  }

  /* CAJA MUCHO MÁS ANCHA (780px) PARA EVITAR EFECTO DE ESTROFA */
  .playa-contenido {
    max-width: 780px !important; 
    margin: 0 auto !important;
    padding: 100px 24px 150px 24px !important;
    font-family: 'Courier New', Courier, monospace !important;
    line-height: 2.3 !important;
    letter-spacing: 0.05em;
  }

  .playa-contenido p {
    color: #2c3e50 !important; 
    font-size: 16px !important;
    margin-bottom: 24px !important;
  }

  /* OPCIONES AL FINAL DE LA PROSA */
  .playa-opciones {
    margin-top: 120px !important;
    border-top: 1px solid #d1ccc0 !important;
    padding-top: 30px !important;
    font-family: 'Courier New', Courier, monospace !important;
    font-size: 16px !important;
    letter-spacing: 0.05em;
    color: #2c3e50 !important;
    display: flex !important;
    gap: 40px !important;
  }

  .playa-opciones a, .playa-opciones a:visited {
    color: #4b6584 !important;
    text-decoration: none !important;
    font-weight: bold !important;
    transition: color 0.2s !important;
  }
  
  .playa-opciones a:hover {
    color: #ff3366 !important;
  }

  @media (max-width: 768px) {
    .playa-contenido { max-width: 100% !important; }
  }
</style>

<div class="bunker-playa">

  <div class="contenedor-titulo-playa">
    <span class="titulo-azul">LA PLAYA</span>
  </div>

  <!-- TU TEXTO EN FORMATO DE PÁRRAFO ANCHO Y EXTENDIDO -->
  <div class="playa-contenido">
    
    <p>Un plafón opaco, sucio, liso derrite las nubes y las caras.</p>
    <p>El bar. Con sombrillas rojas. Mesas plásticas. Y círculos pegajosos. Nadie quiere nada pero todos nos sentamos con actitud.</p>
    <p>Un susto me despega de la mesa. Es una desproporción muy evidente. Tengo la nariz seca por dentro y resbalosa por fuera. Todos los pliegues transpiran su especialidad. Coreografía de raquetas, abanicos y chapuzones y un hombre de brazos marrones. Presta ayuda al camión con la maniobra. Irrespetuosa.</p>
    <p>Estoy quieta como un árbol que no puede meterse bajo su propia sombra.</p>
    <p>Los ventiladores revuelven.</p>
    <p>La actitud con la cual nos sentamos sigue manteniéndonos sentados.</p>
    <p>El agua si no es aceite es cerveza.</p>
    <br>
    <p>Calmamos la sed con cacahuetes salados.</p>

    <div class="playa-opciones">
      <a href="el-gato-naranja.html">quiero</a>
      <a href="index.html">no quiero</a>
    </div>

  </div>
</div>
