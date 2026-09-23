# Dam_Entornos
Creacion de un juego:
La idea es hacer un juego de plataformas sencillo en el que el jugador controlaria al personaje, donde sus controles serian moverse a la derecha o izquierda con la mecanica de saltar y doble salto. El objetico seria llegar al final de los niveles sin perder todas las vidas. El objetivo del juego seria llegar a la pantalla final y ganar al jefe final en una carrera de plataformas.


El problema principal es hacer que el personaje se mueva correcta y fluidamente por los niveles, para resolver el problema deberiamos controlar bien el movimiento horizontal, el salto y la gravedad del nivel, las colisiones con las plataformas y los obstaculos e enemigos.
Usariamos de lenguaje javascript, junto HTML y CSS, java se encarga de la logica del juego, HTML se encargaria de la creacion de la pagina y el CSS para la apariencia del juego. Uso java porque me permitira abrir el juego desde el navegador asi nos ahorramos de descargar progranas.


De paradigma usaria  una programacion orientada a objetos: crearia alguna clase como: jugador, plataforma, enemigo, juego. El algoritmo seria un bucle de juego, el bucle lo hariamos para que se repita muchas veces y realice algunas acciones por ejemplo: actualizar posiciones y localizar colisiones o dibujar otra vez todos los elementos. Ejemplo:

function bucleJuego() {
    actualizar();
    dibujar();
    requestAnimationFrame(bucleJuego);
}

bucleJuego();


El codigo llegaria a ejecutarse muy facilmente: cuando se abre  index.html el navegador lee primero el html, despues cargaria el CSS y seguidamente se ejecuta el javascript, despues de eso empieza el bucle del juego. Todo se abriria en un navegador y usariamos las herramientas de desarrollador con la tecla F12.



Guardariamos el proyecto de GitHub en un repositorio nuevo y lo meteriamos dentro de la carpeta del juego, el comando commit guardaria los cambios en el historial local. Luego usamos el comando push que envie esos commits al repositorio de GitHub. Despues del push, estaria en la pagina del repositorio desde GitHub. Al final ya podriamos utilizar GitHub Pages para publicar el juego y en el repositorio elegir la rama main.