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

  /* LA PROSA INTRODUCTORIA (MORADA) SUBE AL INICIO SIN TÍTULO PREVIO */
  .bunker-contenido {
    max-width: 440px !important; 
    margin: 0 auto !important;
    padding: 140px 24px 150px 24px !important; /* Más aire arriba al no haber título */
    font-family: 'Courier New', Courier, monospace !important;
    line-height: 2.3 !important;
    letter-spacing: 0.05em;
  }
  .bunker-contenido p {
    color: #b3a7c4 !important; /* Tu morado característico */
    font-size: 17px !important;
  }

  /* LA CORTINA REUBICADA: A LA DERECHA, MÁS ANCHA Y CÓMODA */
  .cortina-abstracta {
    display: block !important;
    position: fixed !important;
    top: 0 !important;
    right: 40px !important; /* Despegada del borde derecho para que respire */
    width: 8px !important;  /* Más gruesa: ahora es fácil acertar con el mouse */
    height: 100% !important;
    background: linear-gradient(to bottom, #ffffff 20%, #e6e6e6 50%, #ffffff 80%) !important;
    border-radius: 4px !important;
    box-shadow: 0 0 15px rgba(255,255,255,0.7), 0 0 5px rgba(255,255,255,0.3) !important;
    animation: cortocircuito-lineal 2s infinite alternate !important;
    cursor: pointer;
    z-index: 1000000 !important;
  }

  /* EL SEMÁFORO CON VECTORES MATES */
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

  .contenedor-luz-vectorial {
    width: 18px !important;
    height: 18px !important;
    display: block !important;
    transition: transform 0.2s;
  }

  .contenedor-luz-vectorial:hover {
    transform: scale(1.1) !important;
  }

  .animacion-amarilla {
    animation: parpadeo-vectorial 1.5s infinite alternate !important;
  }

  @keyframes parpadeo-vectorial {
    0%, 100% { opacity: 1; }
    50% { opacity: 0.7; }
  }

  @keyframes cortocircuito-lineal {
    0%, 100% { opacity: 0.9; transform: scaleX(1); }
    7% { opacity: 0.2; transform: scaleX(0.8); }
    10% { opacity: 1; transform: scaleX(1.1); }
    14% { opacity: 0.1; transform: scaleX(0.6); }
    50% { opacity: 0.8; transform: scaleX(0.9); }
  }

  @media (max-width: 768px) {
    .cortina-abstracta { right: 15px !important; width: 6px !important; }
  }
</style>

<div class="bunker-literario">
  
  <!-- LA NUEVA CORTINA INTERACTIVA A LA DERECHA -->
  <a href="la-playa.html" class="cortina-abstracta" title="Abrir la cortina (La Playa)"></a>

  <!-- EL CONTENIDO COMIENZA DIRECTAMENTE AQUÍ -->
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

    <!-- EL SEMÁFORO BLINDADO -->
    <div class="contenedor-semaforo">
      <div class="semaforo-caja">
        
        <!-- Luz Roja Carmín Serundia -->
        <a href="index.html" class="contenedor-luz-vectorial" title="Frenar - Volver a la entrada de Serundia">
          <svg width="18" height="18" viewBox="0 0 100 100" xmlns="http://www.w3.org/2000/svg">
            <circle cx="50" cy="50" r="50" fill="#ff3366" />
          </svg>
        </a>

        <!-- Luz Amarilla -->
        <a href="el-gato-naranja.html" class="contenedor-luz-vectorial animacion-amarilla" title="Precaución - Abrir los Recuerdos">
          <svg width="18" height="18" viewBox="0 0 100 100" xmlns="http://www.w3.org/2000/svg">
            <circle cx="50" cy="50" r="50" fill="#ffcc00" />
          </svg>
        </a>

      </div>
    </div>

  </div>
</div>
