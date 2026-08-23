# 🐦 Flappy Bird Game

## Descripción
Recreación del clásico juego Flappy Bird desarrollado en Python utilizando la librería Pygame. 
El jugador controla un ave que debe aletear para mantenerse en el aire y esquivar los obstáculos (tuberías) que aparecen progresivamente. 

Proyecto individual para la materia **Software Factory II**.

## Cómo jugar
1. Al abrir el juego, presionar **Espacio** o hacer clic para iniciar.
2. Presionar **Espacio** o **Clic Izquierdo** para que el pájaro aletee y gane altura.
3. Esquivar las tuberías pasando a través de las aberturas.
4. Cada par de tuberías superado suma **1 punto**.
5. Evitar colisionar con las tuberías, el suelo o el techo.
6. Al perder, se guardará tu puntaje y podrás ver el **Top 5** del ranking.

## Funcionalidades
- [x] Documentación y estructura base del proyecto
- [ ] Pantalla de inicio
- [ ] Mecánica principal (físicas de gravedad y salto)
- [ ] Generación aleatoria de tuberías
- [ ] Sistema de puntaje (HUD)
- [ ] Pantalla de Game Over
- [ ] Persistencia de datos y Ranking con SQLite (Top 5)
- [ ] Menú para volver a jugar o salir

## Capturas de pantalla
*(Se agregarán capturas del juego cuando el módulo gráfico esté implementado)*

## Cómo ejecutar

### Requisitos previos
- Python 3.8 o superior
- Pygame instalado

### Instalar Pygame
```bash
pip install pygame

Ejecutar el juego

Bash

cd src
python main.py

Estructura del proyecto

flappy-bird/
├── .gitignore
├── README.md
├── docs/
│   ├── requerimientos.md
│   └── diagrama_flujo.md
├── assets/
│   ├── images/
│   ├── sounds/
│   └── fonts/
├── src/
│   ├── main.py
│   ├── game.py
│   ├── player.py
│   ├── pipe.py
│   └── database.py
└── database/

Tecnologías

-Python 3

-Pygame

-SQLite

-Git / GitHub

Documentación

-Requerimientos del sistema

-Diagrama de flujo

Estado del proyecto

🔨 En desarrollo

Autor

Marco Paz Martínez — @MarcoPazMartinez

Proyecto para Software Factory II — ITES 2026