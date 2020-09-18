# Uso y propiedades de las etiquetas CSS
trabajaremos de una en una para poder ver sus propiedades sobre como funcionan cada un en sintaxis de html y css
## Sintaxis para cambiar colores de texto.
Primero trabajamos mediante una pagina de html 5 donde la primera etiqueta utilizada en el body sera con un parrafo que se representa de esta manera
```
<p>Hello World!</p>
<p>These paragraphs are styled with CSS.</p>
```
Desde este apartado el texto se mostrara de forma normal, pero si creamos un archivo de css, y llamamos la propiedad de "P" entre llaves podemos cambiar sus propiedades, no sin antes en el archivo html, usar la siguiente linea de codigo:
  ```  <link rel="stylesheet" href="css/style.css">```
  El cual hara un llamado al archivo css y podemos manipular todas las propiedades.
  en este caso modifique la etiqueta P y use los siguientes valores:
  ```
p {
    color: red;
    text-align: center;
  } 
  ```
  De esta manera podemos cambiar los colores del texto, que esta en todas las etiquetas de P.

# Uso de los selectores
cuando hablamos de selectores hablamos de los elementos que estan en html que querems seleccionar para aplicarles estilo. ya lo pusimos en practica en el aparado interior cuando selecionamos la etiqueta p para darle color y centrarla, ahora lo haremos de otra manera la cual es:
### Selector de id en css
 
 Primero debemos crear la etiqueta con ese identificador a utilizar en este caso sera de esta forma en conjunto con la etiqueta P:
```
 <p id="para1"> hola como estas</p>
 ```
 en el html, ahora proseguimos a realizar la declaracion y asignacion de propiedades en el css:
 ```
  #para1 {
    color: brown;
    text-align: center;
  }
 ```
 ### selector de clases CSS
 De forma anterior al Id, que selecciona elementos especificos el selector class, lo podemos usar para seleccionar un atributo de clase especifico.

 Para trabajarlo debemos de igual form trabajar en html y en css, primeramente en html crearemos la etiqueta, en mi caso usare un enunciado, donde dentro de la llave de apertura podemos colocar el nombre de la clase.
 ```
<h1 class="ejemplo">Ejemplo de la clase</h1>
 ```
 Donde ahora poder asignarles los valores en sus propiedades vamos al css y aplicamos lo siguiente:
 ```
 .ejemplo
  {
    color: darkblue;
    text-align: center;
  }
 ```
 # Comentarios
 Como sabemos que para poder dar o hacer una explicacion del codigo existen, los comentarios los cuales son para documentar el codigo, para realizar comentarios en css usamos la siguiente estructura:
 ```

 ```