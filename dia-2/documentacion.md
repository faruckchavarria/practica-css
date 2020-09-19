# Colores Css
Para nosotros poder hacer uso de los colores que nos presenta css debemos especificar su nombre, en donde css y html abmite 140 nombres de colores standar. estaremos trabajando estos colores en llamados css, internos.
```
<h1 style="background-color:DodgerBlue;">Hello World</h1>
<p style="background-color:Tomato;">Hola Mundo en spanish xdxd</p>
```
Pero tambien podemos hacerlo desde un archivo css para que vean que siempre estams haciendo uso de estilos css.
```
<h1 id="encabeza"> Hello World</h1>
<p id="parrafo"> Hola Mundo en spanish xdxd</p>
```
Estas lineas de codigo son utilizadas en el documento de html y en el archivo de css utilizamos el siguiente
```
#encabezado
{
    background-color: tomato;
}
#parrafo
{
    background-color: tomato;
}
```
Esta manera logramos el mismo resultado, no hay problema.
# Color de texto CSS
El color de texto es algo muy facil de aplicar donde simplemente damos los colores dentro de las etiquetas con "style" como se mostrara a continuación.
```
<h1 style="color:red;">Hello World</h1>
<p style="color:Blue;">Hola mundo en spanish </p>
<p style="color: green;">Pongame 100 teacher xdxd</p>

```
De esta manera sera capaz de darle color al texto que deseemos todo sea dentro de la etiqueta.
#Color del borde CSS
De la misma forma que se puede aplicar colores en el texto podemos aplicar colores en los bordes para que este sea mucho mas atractivo y dinamico.
```
<h1 style="border:2px solid Tomato;">Hola mundo en un color</h1>
<h1 style="border:2px solid DodgerBlue;">Hola mundo en otro color xdxdx</h1>
<h1 style="border:2px solid Violet;">Hola mundo en otro pinche color no mames.</h1>
```
Nos referimos a border:2px, cuando queremos el grueso del borde, de esta manera podemos hacer mas grueso o mas delgado el grueso de el borde.
# Colores de css en RGB
Se puede aplicar este efecto de color a las etiquetas de html, utilizando una formula que ponga en juego los 3 colores para llegar a un color final, la cual se compone de RGB (rojo,verde,azul) dentro de esta formula donde corresponda cada color podemos modificarlos desde 0 hasta 255 donde a medida que cambia se va logrando todos estos colores.
```
<h1 style="background-color:rgb(255, 0, 0);">rgb(255, 0, 0) Este es rojito</h1>
<h1 style="background-color:rgb(0, 0, 255);">rgb(0, 0, 255) este es azulito</h1>
<h1 style="background-color:rgb(60, 179, 113);">rgb(60, 179, 113) este como verdesito</h1>
<h1 style="background-color:rgb(238, 130, 238);">rgb(238, 130, 238)este como rosadito</h1>
<h1 style="background-color:rgb(255, 165, 0);">rgb(255, 165, 0)este como amarillito</h1>
<h1 style="background-color:rgb(106, 90, 205);">rgb(106, 90, 205)este tirando a moradito</h1>

<p>Ta chingon veda.</p>
```
De esta forma podemos trabajar colores en RGB en las etiquetas de html.
# Colores de saturacion  o colores css hsl

Estos colores se pueden especificar usando tonos, saturacion y luminosidad, casi de una forma muy similar al de los colores RGB que se maneja atraves de una formula, a cual la podemos representar de la siguiente manera hsl ( tono , saturación , luminosidad ) bien una ves se haya mostrado la formula cabe resaltar que por cada una de las propiedades a modificar se debera usar % para modificar los valoresque van desde un 0% hasta un 100%
```
<h1 style="background-color:hsl(0, 100%, 50%);">hsl(0, 100%, 50%) Es como rojito</h1>
<h1 style="background-color:hsl(240, 100%, 50%);">hsl(240, 100%, 50%) es como azulito</h1>
<h1 style="background-color:hsl(147, 50%, 47%);">hsl(147, 50%, 47%) Es como verde menta</h1>
<h1 style="background-color:hsl(300, 76%, 72%);">hsl(300, 76%, 72%) Es como rosa</h1>
<h1 style="background-color:hsl(39, 100%, 50%);">hsl(39, 100%, 50%) Es como amarillo</h1>
<h1 style="background-color:hsl(248, 53%, 58%);">hsl(248, 53%, 58%) Es como moradito</h1>
```
Si vamos colocando diferentes porcentaje en cada una de las lineas podemos ir modificando los colores.
si queremos una explicacion y prueba de colores podemos visitar la siguente pagina:
 <a href="https://www.w3schools.com/Css/css_colors_hsl.asp">Acceder a la página web</a>

 # Fondos css
Ya hemos trabajado con esta propiedad o esta etiqueta donde podemos mostrar ejemplos sencillos sobrela utilidad de esta etiqueta. podemos trabajar los colores de muchas foras incluso de las formas que habiamos practicado anteriormente como lo es en hexadecimal, con el nombre del color y con RGB

En la siguiente etiqueta hare que todo el body donde he estado trabajando tenga un fondo en general:
```
body {
  background-color: lightblue;
}
```
de esta forma le doy un fondo muy diferente a la pagina en el fondo, de lo mas comun como lo es un fondo blanco, ahora puedo modificarlo de la manera que desee.

 de igual forma podemos poner un fondo a cualquiera de las de las etiquetas que contiene nuestro HTML, use como referencia a el Body, pero funciona con cualquiera.

 # Opacidad / Transparencia
 Tambien podemos aplicar transparencia a dichos fondos utilizando los mismos argumentos y añadiendo la propiedad opacity. Como se ve acontinuacion:
 ```
body {
  background-color: lightblue;
  opacity: 0.3;
}
 ```
 ¿Pero que es ese 0.3 que despues de la propiedad?, sencillo podemos trabajar en un rango de 0.1 hasta 1 donde el numero 1 sera la pureza del fondo y mientras mas se acerce al cero, esta sera mas opaca.

 # Imagen de fondo CSS

 Al igual que una fondo de color, podemos colocar una imagen, la que nosotros deseemos de  fondo en nuestra pagina lo podemos realizar mandando a llamar una imagen de nuesto ordenador o servidor local.
 ```
body {
  background-image: url("1384063.png");
}
 ```

 # Repetición de fondo CSS
 En muchas ocasiones al colocar una imagen de fondo, por defecto en navegador al notar que los valores de el tamaño de la imagen se acaban, entonces comienza a repetir los valores o la misma imagen una y otra ves haciendo que no sea lo mas atractivo posible y es cuando se usa la siguiente propiedad para liberarnos de esta problematica.
 ```
body {
  background-image: url("gradient_bg.png");
  background-repeat: repeat-x;
}
 ```