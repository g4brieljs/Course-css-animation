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

```css
.box{
    width: 500px;
    height: 300px;
    background: rgba(255, 25, 25, 0.651);

    /*First animation*/
    animation: color 2s infinite alternate;
}

@keyframes color{
    to{
        /*Va del rojo al azul, pero si lo pruebas, podras ver que muestra colores intermedios, esta parte debemos entenderla, saber si usa la gpu del equipo, si colocas el estado inicial, y final, y los intermedios que no definas, el navegador lo hara por default*/
        background: rgb(25, 151, 255);
    }
}
```

![first-animation](https://github.com/g4brieljs/Course-css-animation/blob/master/01-First-animation/first-animation.gif)

# First css triggers

![first-triggers](https://github.com/g4brieljs/Course-css-animation/blob/master/01-First-animation/first.gif)