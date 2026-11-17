# English Fun Time · para los más chicos

Página web con actividades y minijuegos de inglés para niños pequeños.
Funciona en el navegador (pensada para **tablet**, también anda en computadora y celular). No necesita instalar nada.

## Qué incluye
1. **Bienvenida:** el alumno escribe su nombre y elige su color favorito (la página cambia a ese color).
2. **Activity 1:** unir cada color con su nombre en inglés (red, blue, yellow, green, orange, pink, purple, brown). → *Mini-game 1:* "Click on the rabbit 3 times": cada vez que tocan al conejo aparecen más animales.
3. **Activity 2:** *True or false* de emociones ("She feels happy."): sleepy, hungry, nervous, angry, happy, excited, thirsty, sad. → *Mini-game 2:* ahorcado con emociones (la cara funciona de pista).
4. **Activity 3:** preguntas con *can / can't* y animales ("Can the elephant fly?"): sleep, fly, swim, run, crawl, climb. → *Mini-game 3:* "Tap on the monkey": 10 toques para que el mono suba al árbol.
5. **Activity 4:** ver el dibujo (animal o comida) y escribir el nombre en inglés. Si hay un error de ortografía, la página avisa y marca en rojo las letras que faltan o sobran. Tiene hasta 3 intentos por palabra.
6. **Final:** resumen de notas y felicitaciones.

Después de cada actividad (y su minijuego) aparece un **aviso en inglés y en español** para que anoten la nota en el cuaderno de inglés.

## Privacidad
La página no envía ningún dato. El nombre solo se muestra en pantalla mientras el alumno juega.
Para que no se pierda el avance si la página se recarga sin querer, guarda el progreso (nombre, color y notas) en la memoria temporal de esa pestaña del navegador (`sessionStorage`). Se borra solo al cerrar la pestaña, no sale del dispositivo y no se comparte.
No usa servicios externos, cookies ni anuncios.
El botón 🔊 usa la voz que ya trae el dispositivo para leer la palabra en inglés.

## Notas para la docente
- Las caras de las emociones son dibujos generados por la página, así la respuesta siempre coincide con la imagen. Los animales y comidas usan emojis del dispositivo (pueden verse un poco distintos en cada tablet).
- La nota de cada actividad es la cantidad de respuestas correctas a la primera (por ejemplo `5/6`).
- En la Activity 4 se acepta *rabbit* o *bunny*, mayúsculas o minúsculas, y con "a/an/the" adelante.
- Los botones y las zonas de toque son grandes para dedos pequeños. Funciona en tablet vertical y horizontal.

## Pantallas táctiles
La página bloquea el gesto de "deslizar hacia abajo para recargar" (`overscroll-behavior`) y los minijuegos no scrollean al arrastrar el dedo. Si igual se recarga, el alumno vuelve a la misma actividad con sus notas.

## Cómo editarla
Todo está en un solo archivo, `index.html`. Para cambiar palabras, preguntas o animales se edita ese archivo:
`EMO` (emociones), `CAN` (preguntas can/can't), `WORDS` (animales y comidas de la Activity 4), `COL8` (colores).
