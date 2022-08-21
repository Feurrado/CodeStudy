# Valores e unidades de medida

* cada propriedade possui valores 'property: value'


## Prática

* but how?
    * <color> <length>
* os termos variam entrem 'values' ou 'data types'

https://developer.mozilla.org




# Tipos numéricos

* <integer>         Número inteiro como -10 ou 223
* <number>          Número decimal como -2.4, 64 ou 0.234
* <dimension>       É um <number> com uma unidade junto: 90deg, 2s, 8px
* <percentage>      Representa a fração de outro número: 50%


## Unidades comuns

* <length>          Distância: px, em, vw
* <angle>           Ângulo: deg, rad, turn
* <time>            Tempo: s, ms
* <resolution>      Resolução tela: dpi




# Absolutas <lenght>

São fixas

cm     Centímetros     1cm = 96px/2.54
in     Inches          1in + 2.54cm = 96px
px     Pixels          1px + 1/96th of 1in

* o mais comundo é o **px**
* not use cm

# Relative distance

São relativas a algum valor, pode ser o elemento pai, root ou tamanho da tela

Se adaptam melhor aos diferentes tipos de tela

Unidade    Relativo a
em         Tamanho da font do pai
rem        Tamanho da font do root/html
vw         1% da viewport widht
vh         1% da viewport height




# Porcentagens %

 *Ex:*

<ul>
	<li>One</li>
	<li>Two</li>
	<li>Three
		<ul>
			<li>Three A</li>
			<li>Three B</li>
			<ul>
				<li>Three B 2</li>
			</ul>
		</ul>
	</li>
</ul>
li {
    font-size: 80%;
}




# Posições

<position>

Representa coordenadas 2d
- top, right, bottom, left, center.

* não confundir com 'position'




# Funções

Em programação, funções são reconhecidas por causar um reaproveitamento de código.

* rgb ()
* hsl ()
* url ()
* calc ()

# Strings and identifiers

* string: texto em aspas
* identifiers: red, black, gold












