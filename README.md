# estrellados-videojuego-allegro
Videojuego llamado "Estrellados" realizado en C++ con la biblioteca Allegro.

El trabajo realizado fue un videojuego llamado ESTRELLADOS. El mismo consiste en pilotear una nave que será afectada por la gravedad, la cual se puede mover hacia la izquierda, derecha o arriba, con el objetivo de atrapar una estrella dibujada en el mapa.

Este fue realizado con las siguientes bibliotecas:
#include <iostream>
#include <allegro.h> (principalmente)
#include <cmath>
#include <list>

El nombre surgió de un juego de palabras, en el cual se debe atrapar la estrella. De lo contrario, la nave se estrellará. De ahí, el nombre ESTRELLADOS.

Tanto la nave como la estrella cambiarán de posición a medida que pasan los niveles, y el jugador deberá superar una serie de obstáculos sin sobrepasar los limites de la pantalla en búsqueda de alcanzar la estrella.

El juego contiene 5 niveles los cuales irán aumentando su dificultad. Primero no habrá obstáculos, luego aparecerán algunos en forma de rectángulos, después en forma de triángulos y finalmente se combinarán para hacer más difícil cada nivel.

A su vez, existe un medidor de combustible el cual, si se agota, la nave no podrá pilotearse y chocará inmediatamente, aunque se puede recargar si se atraviesa un rectángulo rojo. Este va disminuyendo a medida que se presionan las teclas que mueven la nave (si no se presionan, este no bajará).
Por cada choque, el jugador tendrá la opción de reiniciar el nivel presionando la tecla R, y en caso de querer cerrar el juego, basta con apretar la tecla ESC.
Si el jugador logra pasar todos los niveles, finalmente se pedirán algunos datos del mismo para introducirlo en una lista de ganadores que se mostrará al finalizar el juego.
