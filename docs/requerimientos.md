# Requerimientos — Flappy Bird

## Requerimientos Funcionales
- RF-01: El personaje (pájaro) cae constantemente debido a la fuerza de gravedad.
- RF-02: El jugador puede hacer aletear al pájaro presionando la barra espaciadora o clic izquierdo para ganar altura.
- RF-03: Los obstáculos (tuberías) se desplazan de derecha a izquierda a velocidad constante.
- RF-04: Las tuberías aparecen en pares (superior e inferior) con una apertura central de altura aleatoria.
- RF-05: Se suma 1 punto al contador cada vez que el pájaro atraviesa exitosamente un par de tuberías.
- RF-06: Si el pájaro colisiona con una tubería, el suelo o el techo de la pantalla, es Game Over.
- RF-07: Se muestra el puntaje actual en tiempo real en la parte superior de la pantalla durante la partida.
- RF-08: Al terminar la partida, se registra y guarda el puntaje en la base de datos SQLite.
- RF-09: Existe una pantalla de ranking que muestra los 5 mejores puntajes históricos.
- RF-10: El jugador puede seleccionar entre "Jugar de nuevo" o "Salir" en el menú de fin de juego.

## Requerimientos No Funcionales
- RNF-01: El juego ejecuta a 60 FPS estables garantizando fluidez en la física de movimiento.
- RNF-02: La respuesta a los controles de salto es inmediata y precisa.
- RNF-03: El código está estructurado modularmente en arquitectura orientada a objetos dentro de la carpeta `src/`.
- RNF-04: El proyecto utiliza un historial de versiones limpio mediante Git y GitHub.
- RNF-05: La ventana de juego tiene una resolución fija de 1280x720 píxeles.