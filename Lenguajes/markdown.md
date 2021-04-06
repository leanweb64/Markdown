# Elemento de bloque

***
--- 
___

## Parrafos y saltos de linea
para generar nuevo parrafo pulsar dos veces enter.

para salto de linea pulsar dos veces barra espaciadora + enter y seguir escribiendo

*** 
*** 

## Encabezado
se utilizan # dependiendo del tamaña requerido

# titulo 1 
## titulo 2 
### titulo 3
#### titulo 4 
##### titulo 5
###### titulo 6  

--- 
--- 

## Citas

se generan con > al comienzo, de tener varios parrafos se usa el mismo simbolo una y otra ves

> Markdown es mi herramienta de estudio  
Leandro

Citas anidadas se crean con >>  

Recuerda separar los saltos de línea con >, o >> si te encuentras dentro de la cita anidada; para crear párrafos dentro del mismo bloque de cita.

>Markdown es la mejor tecnologia 
> 
>>texto anidado
>
>ejemplo de uso

--- 
--- 
## Listas

existen dos tipos, desordenadas y ordenadas 

*** 

### Listas desordenadas

Se crean con * , - , +  
Ademas podemos anidar usando cuatro espacios en blanco mas * , - , + 

* lista uno
    * lista anidada
- lista dos
    - lista anidada
    - lista anidada
+ lista tres
    + lista anidada
        + lista anidada de anidada
        - lista anidada de anidada
        * lista anidada de anidada

*** 

### Lista ordenada
~~~
para crear listas ordenadas usamos numero, tambien podemos anidar listas pero solo usando un enter y el simbolo de lista
~~~

1 lista ordenada

1 lista ordenada  
- anidando lista  
1 lista anidad

2 lista ordenada  
* anidando lista desordenada  
1 lista ordenada  
2 lista ordenada  
 
- anidando lista desordenada  
+ anidando lista desordenada
--- 
---  
## Codigo de bloque

se crea un bloque encerrandolo con tres ~~~ bloque ~~~  
Dentro del bloque no funciona la sintaxis de Markdown

~~~
Creando un bloque 
 
Este bloque puede contener la catidad de lineas que desee  
~~~

***  
*** 

## Reglas horizontales
~~~
se usan para separar secciones de forma visual  
Para crearlas se usan tres simbolos consecutivos *** --- ___
~~~

---  
---  

## Elementos de lineas

### Cursiva 
Se enfatiza con simbolos antes y despues del texto a modificar, se pueden combiar con tres simbolos iguales 
~~~
*Cursiva*  
__Cursiva__  
**Negrita**  
__Negrita__  
~~~
*Cursiva*  
__Cursiva__  
**Negrita**  
__Negrita__  
***Cursiva y Negrita***  
___Cursiva y Negrita___


--- 
--- 
## Links o enlaces  
~~~
Existen varias maneras de añadir enlaces
~~~
***
### Links o enlaces en linea
~~~  
Son los enlaces de toda la vida, se crean con [] y el link entre ()
~~~

[Link encontranos en Facebook](www.facebook.com/miempresa)

***

### Links o enlaces como referencia

~~~
en el metodo anterior si el link es largo puede dificultar su lectura  
para simpificar el uso podemos usar enlaces de referencia
~~~

En este ejemplo usamos [referencia]  
creando el nombre de referencia despues la llamares  
[referencia]: http://facebook.com/miempresa

--- 

### Links automaticos
~~~
Estos son necesarios cuando lo que quieres es mostrar una URL completa, y no un enlace enmascarado bajo una palabra o frase como ocurre con los links en línea.
Para generar links automáticos tan solo tendrás que rodearlos con los símbolos < >
~~~

<http://facebook/miempresa>

---  

### Codigo puro

debemos envolver entre `Basticks `, equivale a `<code>` en html

`function write()`

---

### Texto preformateado

Podemos comenzar el parrafo con cuatro espacios en blanco y generara un bloque

    bloque de codigo generado con cuatro espacios en blanco

---

### Imagenes

~~~
insertamos un link anteponiendo ! exclamacion y definimos un enlace con la ubicacion de la img
en texto alternativo funciona como alt en html
Ademas podemos ingresar  varias imgs
~~~

![Texto alternativo](./pics/homer.jp g "Homer Simpson")

***

### Colores con span

texto <span style="color:red"> al cual </span> diferentes
<span style="color:green"> le vamos a</span> <span style="color:yellow">poner colores </span> 
texto <span style="color:red"> al cual </span> diferentes
<span style="color:green"> le vamos a</span> <span style="color:yellow">poner colores </span>
texto <span style="color:red"> al cual </span> diferentes
<span style="color:green"> le vamos a</span> <span style="color:yellow">poner colores </span>
texto <span style="color:red"> al cual </span> diferentes
<span style="color:green"> le vamos a</span> <span style="color:yellow">poner colores </span>
texto <span style="color:red"> al cual </span> diferentes
<span style="color:green"> le vamos a</span> <span style="color:yellow">poner colores </span>
texto <span style="color:red"> al cual </span> diferentes
<span style="color:green"> le vamos a</span> <span style="color:yellow">poner colores </span>
texto <span style="color:red"> al cual </span> diferentes
<span style="color:green"> le vamos a</span> <span style="color:yellow">poner colores </span>
texto <span style="color:red"> al cual </span> diferentes
<span style="color:green"> le vamos a</span> <span style="color:yellow">poner colores </span>
texto <span style="color:red"> al cual </span> diferentes
<span style="color:green"> le vamos a</span> <span style="color:yellow">poner colores </span>