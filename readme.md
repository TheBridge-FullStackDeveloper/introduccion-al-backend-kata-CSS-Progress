![logotipo de The Bridge](https://user-images.githubusercontent.com/27650532/77754601-e8365180-702b-11ea-8bed-5bc14a43f869.png "logotipo de The Bridge")

# :shinto_shrine: - CSS Progress #

## Introducción ##

Una barra de progreso suele indicarnos cuánto resta para terminar una tarea. A diferencia de una pantalla de carga, nos indica el progreso.

![pic4]

## Requisitos ##

- Precurso Web

## Iteraciones ##

Tu objetivo será crear una barra de progreso, a la que puedes dar varios niveles de complejidad o capas.

![pic2]

Existen varias maneras de abordar la construcción de una barra de progreso: la etiqueta `<progress></progress>` y un simple y perverso `<div></div>`. Con la etiqueta, al pertenecer al estándar posee mucha funcionalidad por defecto ya agregada, que nos ayudará en cosas como la accesibilidad; si es importante para ti la personalización y la estética, con el `div` tendremos mayor opción de personalización, pero tendrás mucho más trabajo.

Para saber más sobre el estándar y su personalización tienes a tu alcance la archiconocida y bien documentada [MDN] y para mayor profundidad a la hora de dar estilo, la guía de [CSS Tricks progress element]

Si en tu caso prefieres pintar arcoíris y enfrentarte a la [ONCE] tienes la opción de otro artículo [CSS Tricks progress bar]

![pic1]

1. Crea una barra de progreso en HTML y dótala de un color de fondo distinto al que viene por defecto.

2. Establece un color distinto para cada tramo siguiente:
    - 0% - 30%
    - 30% - 60%
    - 60% - 90%
    - 90% - 100%

3. Establece una animación, para cambiar el valor de la barra de progreso y así poder ver cómo cambian los colores de manera automática.

4. Cambia los colores de los tramos por entramados, imágenes o degradados de color.

_premium_

5. Haz que un texto externo a la barra de progreso cambie dependiendo del valor de la barra de progreso. Por ejemplo:

    - 0% - 30%: Iniciando
    - 30% - 60%: carga baja
    - 60% - 90%: carga media
    - 90% - 100%: ¡A tope con la cope!

![pic3]

[MDN]: https://developer.mozilla.org/en-US/docs/Web/HTML/Element/progress "MDN"
[CSS Tricks progress element]: https://css-tricks.com/html5-progress-element "CSS Tricks progress element"
[CSS Tricks progress bar]: https://css-tricks.com/css3-progress-bars "CSS Tricks progress bar"
[ONCE]: https://www.once.es "ONCE"

[pic1]: https://media.giphy.com/media/jowDayTpFmZ6O9uxO5/giphy.gif
[pic2]: https://media.giphy.com/media/7OX6i6JHS645Ui31Dr/giphy.gif
[pic3]: https://media.giphy.com/media/11ASZtb7vdJagM/giphy.gif
[pic4]: https://media.giphy.com/media/SuIHOAKjBhfvrahdcv/giphy.gif
