# Course-css-animation

In this repository, i create a little summary about my progress learning Css animation, for the course Ed.team, css advanced.

# Triggers CSS

Un triggers son los cambios de una propiedad de css.

[Csstriggers.com](https://csstriggers.com/)

Cuando se cambia una propiedad CSS, el navegador necesita reaccionar a ese cambio. Los tipos de cambios son (de mayor a menor costo de recursos).

- Layout (geometría y posición de los elmentos)
- Paint (Pintar los pixeles de los elementos)
- Composite (combina y dibuja las capas en pantalla)
- - Solo opacity y transform desencadenan composición
- - Se crea una capa que almacena al objeto.

Extension for css Triggers **css triggers**

**Importante** en las animaciones hay cambios intermedios, si creamos una animacion de 1s, debemos tener en cuenta los proceso que hara el navegador para cargar esos cambios, en cambio los layouts solo carga una vez.

# First animation

![first-animation](https://github.com/g4brieljs/Course-css-animation/blob/master/01-First-animation/first-animation.gif)

# First css triggers

Como pueden ver el primero usa las propiedades height y width, esto carga mas procesos en el navegador.

El segundo utiliza **Stransform** con un **scale** y un will `change: transform;`, y el no modifica el layout, esto permite mejor perfomance.

![first-triggers](https://github.com/g4brieljs/Course-css-animation/blob/master/02-First-css-triggers/first.gif)

# Property animables y no animables


# First project animation 

![first-project](https://github.com/g4brieljs/Course-css-animation/blob/master/03-First-Project/quickcards.gif)

