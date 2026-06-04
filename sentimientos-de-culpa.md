
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

  /* LA PROSA INTRODUCTORIA MORADA */
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
  }

  /* NUEVA LUZ: TRIÁNGULO FINO, SUSPENDIDO EN LOS 2/3 SUPERIORES */
  .luz-triangular {
    display: block !important;
    position: fixed !important;
    
    /* Posicionamiento: no toca el techo y se suspende a la derecha */
    top: 8vh !important;       /* Margen superior para que NO toque el techo */
    right: 50px !important;    /* Despegado del borde derecho */
    
    /* Dimensiones: ocupa aproximadamente los dos tercios superiores */
    width: 0 !important;
    height: 0 !important;
    
    /* Construcción geométrica del triángulo hacia abajo (ancho arriba, punta abajo) */
    border-left: 5px solid transparent !important;  /* Lado izquierdo invisible */
    border-right: 5px solid transparent !important; /* Lado derecho invisible */
    border-top: 55vh solid #ffffff !important;      /* El cuerpo del triángulo en blanco, cayendo en vertical */
    
    /* Efecto de fulgor blanco sutil en los bordes */
    filter: drop-shadow(0 0 8px rgba(255, 255, 255, 0.8)) !important;
    
    /* Comportamiento e interactividad */
    cursor: pointer !important;
    z-index: 1000000 !important;
    opacity: 0.7;
    transition: opacity 0.3s, filter 0.3s !important;
  }

  /* Animación orgánica de parpadeo suave, sin sacudidas */
  .luz-triangular {
    animation: pulsacion-sutil 3s infinite alternate !important;
  }

  .luz-triangular:hover {
    opacity: 1 !important;
    filter: drop-shadow(0 0 15px rgba(255, 255, 255, 1)) !important;
  }

  @keyframes pulsacion-sutil {
    0%, 100% { opacity: 0.6; }
    50% { opacity: 0.85; }
  }

  @media (max-width: 768px) {
    .luz-triangular { right: 20px !important; border-top-width: 50vh !important; }
  }
</style>

<div class="bunker-literario">
  
  <!-- LA NUEVA AGUJA DE LUZ TRIANGULAR HACIA ABAJO (ENLACE A LA PLAYA) -->
  <a href="la-playa.html" class="luz-triangular" title="Seguir la luz (La Playa)"></a>

  <!-- PROSA SIN TÍTULO NI SEMÁFOROS -->
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
  </div>

</div>
