# PROYECTO 1: JUEGOS CÁSICOS - GRUPO 1 - EL AHORCADO 🎭

Este proyecto es un juego del **Ahorcado en Python**, ambientado en el terror.  
Ha sido desarrollado en equipo como práctica de programación y uso de estructuras básicas en Python.

Proyecto elaborado por: Ana Dueñas, Ela Ruiz, Siuzanna Danielian e Irina Ostojic.

---

## 🎲 Cómo jugar

### 👩‍👩‍👧 Dos jugadoras
- El programa elige **una palabra secreta al azar** relacionada con el mundo del terror.  
- La jugadora actual introduce una letra:  
  - ✅ Si acierta, la letra aparece en la palabra.  
  - ❌ Si falla, el ahorcado avanza y el turno pasa a la otra jugadora.  
- 🏆 Gana quien complete la palabra o quien sobreviva cuando la otra se quede sin intentos.  
- 📊 El **marcador** se va actualizando entre las dos jugadoras.  

*(Actualmente el juego está diseñado para que 2 jugadoras se vayan intercalando en la misma sesión)*  

---

## 💻 Partes del código

- 📜 **terror_words**: lista de palabras de temática terrorífica.  
- 📖 **terror_phrases**: diccionario con frases aleatorias de bienvenida, acierto, fallo, victoria y derrota.  
- 🎨 **hangman**: lista con los dibujos ASCII del muñeco.  
- 🔠 **correct_letters / incorrect_letters / used_letters**: conjuntos para controlar letras jugadas.  
- 📊 **score**: marcador con los puntos de cada jugadora.  
- 🔄 **turn**: controla el turno (jugadora 1 o jugadora 2).  
- 🔁 **while True**: bucle principal que continúa hasta victoria o derrota.  

---

## 🔧 Requisitos / Herramientas necesarias

Para poder ejecutar el juego necesitas tener instalado en tu ordenador:

- 🐍 **Python 3.8 o superior**  
- 💻 Un editor o entorno para ejecutar el código, por ejemplo:  
  - [Jupyter Notebook](https://jupyter.org/)  
  - [VS Code](https://code.visualstudio.com/)  
- La propia terminal de Python  
- 🎵 (Opcional) Librería `playsound` o similar si quieres reproducir música o efectos de sonido:  pip install playsound

---

## ⤴️ Mejoras futuras
  **⚙️ Técnicas**
  - ✂️ Dividir el código en funciones para hacerlo más modular y fácil de mantener.
  - 📝 Soportar palabras con espacios (ejemplo: "casa encantada").
  - 🎮 Permitir modo 1 jugadora o 2 jugadoras, y un modo contra la máquina.
  - 💾 Guardar el marcador entre partidas en un archivo externo (.txt o .json).

  **🎭 Experiencia de juego**
  - 🔄 Permitir rejugar sin reiniciar el programa.
  - 📈 Añadir niveles de dificultad (vidas, longitud de palabras).
  - 🗣️ Ampliar la variedad de mensajes de terror para hacerlo más inmersivo.
  - ✍️ Dar la opción de que las jugadoras añadan sus propias palabras de terror durante la partida.
  - 🎶 Integrar sonidos: ya hay música, y en el futuro se añadirán gritos y risas macabras.

---

## 📑 Enlace a la presentación
https://www.canva.com/design/DAGwUsFsjXU/x3UKcjbI0JHomtTSgL1B7A/edit?utm_content=DAGwUsFsjXU&utm_campaign=designshare&utm_medium=link2&utm_source=sharebutton
