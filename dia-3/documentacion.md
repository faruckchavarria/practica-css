# Documentacion dia 3

## Propiedades de borde CSS
la propiedad border nos permite en css especificar  al estilo , el ancho  y el color  de un elemento para ser mas exacto es la propiedad border-style q ue dentro de ella existen muchos estilos de bordes que se pueden utilizar como lo son:
* dotted - Define un borde punteado
* dashed - Define un borde punteado
* solid - Define un borde sólido
* double - Define un borde doble
* groove- Define un borde acanalado en 3D. El efecto depende del valor del color del borde.
* ridge- Define un borde estriado en 3D. El efecto depende del valor del color del borde.
* inset- Define un borde insertado en 3D. El efecto depende del valor del color del borde.
* outset- Define un borde inicial 3D. El efecto depende del valor del color del borde.
* none - No define ningún borde
* hidden - Define un borde oculto
Un ejemplo mas claro sobre ellos de como utilizarlos se pmostrara a continuacion.
```
<p class="dotted">Este es un borde punteado.</p>
<p class="dashed">Este es otro borde punteado.</p>
<p class="solid">Este es un borde solido.</p>
<p class="double">Este es un borde doble.</p>
<p class="groove">Este es un borde de ranura.</p>
<p class="ridge">Este es un borde de cresta.</p>
<p class="inset">Este es un borde de insertado.</p>
<p class="outset">Este es un borde inicial.</p>
<p class="none">sin borde.</p>
<p class="hidden">Este es un borde oculto.</p>
<p class="mix">Este es un borde mixto.</p>
```
esta lineas de etiqueta vamos a colocarlas en el Body de nuestro documento html en esta ocasion usando clases para que se hagan asignaciones a cada una y no utilzar todo el body mezclando bordes y poder representarlo 1 a 1.
Ahora dentro del css colocaremos el llamado de cada de las clases para que se generen los bordes en los textos mencionados
```
p.dotted {border-style: dotted;}
p.dashed {border-style: dashed;}
p.solid {border-style: solid;}
p.double {border-style: double;}
p.groove {border-style: groove;}
p.ridge {border-style: ridge;}
p.inset {border-style: inset;}
p.outset {border-style: outset;}
p.none {border-style: none;}
p.hidden {border-style: hidden;}
p.mix {border-style: dotted dashed solid double;}
```
una ves hecho eso podemos mostrarlo en la pagina con cada una de los bordes ejemplificados.

# Ancho del borde CSS
con esta propiedad podemos especificar el ancho de cada uno de los bordes que vayamos a utilizar.