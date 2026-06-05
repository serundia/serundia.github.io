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
    max-width: 440px !important; 
    margin: 0 auto !important;
    padding: 140px 24px 150px 24px !important;
    font-family: 'Courier New', Courier, monospace !important;
    line-height: 2.3 !important;
    letter-spacing: 0.05em;
  }
  .bunker-contenido p {
    color: #b3a7c4 !important; 
    font-size: 17px !important;
    margin-bottom: 24px !important;
  }

  /* AGUJA BLANCA HACIA LA PLAYA */
  .luz-triangular {
    display: block !important;
    position: fixed !important;
    top: 8vh !important;       
    right: 50px !important;    
    width: 0 !important;
    height: 0 !important;
    border-left: 5px solid transparent !important;
    border-right: 5px solid transparent !important;
    border-top: 55vh solid #ffffff !important;      
    filter: drop-shadow(0 0 8px rgba(255, 255, 255, 0.6)) !important;
    cursor: pointer !important;
    z-index: 1000000 !important;
    opacity: 0.7;
    animation: pulsacion-sutil 3s infinite alternate !important;
    transition: opacity 0.3s, filter 0.3s !important;
  }

  .luz-triangular:hover {
    opacity: 1 !important;
    filter: drop-shadow(0 0 15px rgba(255, 255, 255, 1)) !important;
  }

  @keyframes pulsacion-sutil {
    0%, 100% { opacity: 0.5; }
    50% { opacity: 0.8; }
  }

  @media (max-width: 768px) {
    .luz-triangular { right: 20px !important; border-top-width: 50vh !important; }
  }
</style>

<div class="bunker-literario">
  
  <a href="la-playa.html" class="luz-triangular" title="Seguir la luz (La Playa)"></a>

  <div class="bunker-contenido">
    <p>Lavarme los dientes. Dar el paso. Mover el aire.</p>
    <p>Recordar. Recordar a los demás.</p>
    <br>
    <p>Una flecha encorvada que sale de un agujero negro. Y frente al espejo: ¿me estrello? ¿o me quedo inmóvil?</p>
    <br>
    <p>Me duelen los 52 huesos de los pies. Si es que no me falta ninguno.</p>
    <p>Tengo una vértebra menos. Otro diagnóstico tardío.</p>
    <br>
    <p>No voy a correr la cortina.</p>
    <br>
    <p>Podría quitar las sillas y obtener más espacio. Estar sentada me distrae.</p>
    <br>
    <p>¿Qué más puedo quitar?</p>
    <br>
    <!-- CORRECCIÓN REALIZADA AQUÍ: "gusten" -->
    <p>No es que no me gusten los objetos. Es que me aburren.</p>
    <br>
    <p>¿Hay culpa en eso?</p>
    <br>
    <p>En querer perder las cosas.</p>
    <br>
    <p>Siento una culpable libertad cada vez que algo se rompe.</p>
    <p>Ultimamente tiro los platos en vez de lavarlos.</p>
    <p>Tampoco me lavo mucho los dientes.</p>
  </div>

</div>
