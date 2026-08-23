# Diagrama de Flujo — Flappy Bird

## Descripción
Este diagrama muestra las pantallas del juego Flappy Bird y las transiciones entre ellas durante el ciclo de vida de la aplicación.

## Pantallas
| Pantalla | Descripción | Cómo se llega |
|---|---|---|
| Inicio | Muestra el título del juego y la opción para iniciar la partida | Al abrir la aplicación |
| Juego | Pantalla principal donde transcurre la partida (control del pájaro y esquive de tuberías) | Al presionar el botón de inicio o barra espaciadora |
| Game Over | Muestra el puntaje final obtenido y registra automáticamente el resultado en la base de datos SQLite | Cuando el pájaro colisiona con una tubería, el suelo o el techo |
| Ranking | Muestra la tabla de los 5 mejores puntajes históricos registrados | Transición automática desde la pantalla de Game Over |

## Transiciones
| Desde | Evento | Hacia |
|---|---|---|
| Inicio | Clic en "Jugar" / Barra Espaciadora | Juego |
| Juego | Colisión (El jugador pierde) | Game Over |
| Game Over | Guardado automático en SQLite | Ranking |
| Ranking | Clic en "Jugar de nuevo" | Juego |
| Ranking | Clic en "Salir" | Fin del programa |

## Diagrama visual
(proximamente)