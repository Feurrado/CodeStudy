CSS para alterar cores.

## types

* background=color (box)
* color (text)
* border-color (box)
* outros...

## Values

Podemos definir os valores por

* keyword (blue, transparent)
* hex (#990011)
* function: rgb, rgba, hsl, hsla

'''css

elemnent 

{
    RGB

    /*keyword values*/
    color: currentcolor;

    /* <named-color> values */
    color: red;
    color: orange;
    color: tan;
    color: tebeccapurple;

    /* <hec-color> values 0-F */
    color: #090 *Red Green Blue (RGB Alpha F)

    /*<rgb()> values */
    color: rgb(34, 12, 64, 0.6) /* 0-255 */
    color: rgba(34, 12, 64, 0.6)

    HSL
    HSL → Hue - Saturation - Lightness

    color: hsl(180, 100%, 50%, 60%)
    color: hsla(180, 100%, 50%, 60%)

    /* Global values */
    color: inheritr; /* Herda a cor do elemento anterior */
    color: initial; /* Volta a sua cor inicial */
    color: unset; /* Pega a cor do contexto */

## Background
