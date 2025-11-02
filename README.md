# PROYECTO 1: JUEGOS CÁSICOS - GRUPO 1 - EL AHORCADO 🎭

Juego del ahorcado desarrollado en lenguaje Python, ambientado en Ingeniería Civil. Proyecto elaborado por Ana Pilar Dueñas Agudo en el Bootcamp de Análisis de Datos de Adalab (presentado en Agosto de 2024).


---

## Cómo jugar

### Dos jugadoras
- El programa elige **una palabra secreta al azar** relacionada con el mundo de la ingeniería civil.  
- El/la jugador/a actual introduce una letra:  
  - Si acierta, la letra aparece en la palabra.  
  - Si falla, el ahorcado avanza y el turno pasa al otro jugador.  
- Gana quien complete la palabra o quien sobreviva cuando el otro se quede sin intentos.  
- El **marcador** se va actualizando entre los dos jugadores.  

*(Actualmente el juego está diseñado para que 2 jugadores se vayan intercalando en la misma sesión)*  

---

## Partes del código

- **words**: lista de palabras de temática ingenieril.  
- **phrases**: diccionario con frases aleatorias de bienvenida, acierto, fallo, victoria y derrota.  
- **hangman**: lista con los dibujos ASCII del muñeco.  
- **correct_letters / incorrect_letters / used_letters**: conjuntos para controlar letras jugadas.  
- **score**: marcador con los puntos de cada jugador.  
- **turn**: controla el turno (jugador 1 o jugador 2).  
- **while True**: bucle principal que continúa hasta victoria o derrota.  

---

## Requisitos / Herramientas necesarias

Para poder ejecutar el juego necesitas tener instalado en tu ordenador:

- **Python 3.8 o superior**  
- Un editor o entorno para ejecutar el código, por ejemplo:  
  - [Jupyter Notebook](https://jupyter.org/)  
  - [VS Code](https://code.visualstudio.com/)  
- La propia terminal de Python  

---

## Mejoras futuras
  **Técnicas**
  - Dividir el código en funciones para hacerlo más modular y fácil de mantener.
  - Soportar palabras con espacios.
  - Permitir modo 1 jugador o 2 jugadores, y un modo contra la máquina.
  - Guardar el marcador entre partidas en un archivo externo (.txt o .json).

  **Experiencia de juego**
  - Permitir rejugar sin reiniciar el programa.
  - Añadir niveles de dificultad (vidas, longitud de palabras).

---

