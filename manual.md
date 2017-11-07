# Markdown

Markdown es un sistema desarrollado por John Gruber y Aaron Swartz  con el fin de simplificar 
formatos y hacer mas facil la escritura de textos.
Los textos en markdown pueden ser exportados a html con facilidad.

## Titulos
Los titulos se hacen de varios tamaños 
el tamaño mas grande es con un signo numeral antes del texto, con dos signos es mas pequeño y 
asi sucesivamente hasta seis signos numeral.

```#titulo 1```
# titulo 1
## titulo 2
### titulo 3
#### tituo 4
##### titulo 5
###### titulo 6

Otra forma de hacer un título es:

colocar el título y en la siguiente linea el signo "=" seguidos al mismo tamaño del título.

```titulo 1```

```========```

titulo 1
========


para el titulo 2 colocar el título y en la siguiente linea el signo "--" seguidos al mismo tamaño del título.

```titulo 2```

```---------```

titulo 2
--------

## Negritas, cursivas e italicas

`**Negritas**`

**Negritas** se hace con dos signos asterisco al comienzo de la palabra y dos al final.

`__Negrita__`

__Negrita__ se hace con 2 raya al piso al comienzo de la palabra y dos al final.

`***Negrita y cursiva***`

***Negrita y cursiva*** se hace con tres asteriscos al comienzo de la palabra y tres al final.

`___Negrita y cursiva___`

___Negrita y cursiva___ se hace con tres rayas al piso al comienzo de la palabra y tres al final.

`*Cursiva*`

*Cursiva* se hace con un asterisco al comienzo de la palabra y uno al final.

`_Cursiva_`

_Cursiva_ se hace con una raya al piso al comienzo de la palabra y una al final.

`*Italicas*`

*Italicas* se hace con un asterisco al comienzo de la palabra y uno al final.

`_Italica_`

_Italica_ se hace con dos raya al piso al comienzo de la palabra y dos al final.

## Listas

Para hacer listas debemos tener en cuenta que cada linea de la lista 
debe ir separada de la otra por una linea en blanco.

## Listas no numeradas 

Para hacer listas no numeradas podemos utilizar los signos +, -, *.

Se coloca el signo y un espacio antes de la palabra a listar.

Asi se escribe:

`+ Jose Angel`

`- Aura`

`* Ruth`

Y se leeran asi:

## niños
+ Jose Angel 
+ Kevin

## niñas
- Aura
- Sofia

## maestros
* Ruth
* Vladimir

## Listas numeradas
Para las listas numeradas se coloca el numero, un punto y un espacio.

`1. Leti`

1. Leti
2. Amparito
3. Abby

## Listas anidadas
Listas anidadas es cuando entre una lista se hace otra lista.
podemos llamar una lista de primer nivel, la primera lista 
y la otra lista, lista de segundo nivel o sublista.
Para hacer la lista ya sabemos con los signos +, -, * o numeros  y para la lista de 
segundo nivel utilizamos los mismos signos o numeros con 4 espacios antes del signo
o del numero.
Estas listas pueden ser numeradas o no.

`+ niños`

      `+ Jolman`
      
### Danzadores
+ niños
  + Jolman
  + José Angel
+ niñas
  + Aura
  + Sofia
  
  ## Enlaces

**Enlace** es un texto o una imagen que al pasar el cursor por encima se forma una manita y 
al hacer click sobre ella nos lleva a otra página o a otra parte de la misma página.

**Enlace externo** es cuando nos lleva a otra página.
Para crear un enlace externo escribimos parentesis cuadrados [] y en medio de ellos la palabra
que veremos en nuestra página y que al hacer click nos llevara a la otra página. 
Luego colocamos parentesis () y la url del enlace va entre los paréntesis.
La URL es la ruta que se encuentra en la caja de texto ubicada en la barra de navegación del navegador, 
sirve para ubicar de manera precisa en un servidor, cualquier recurso: una imagen, un video o una página web.

`[texto o imagen donde haremos click](url de la página del enlace)`

```[Google](https://www.google.com.co/)```

[Google](https://www.google.com.co/)

Otra manera de colocar un enlace es escribir la url entre los caracteres menor que (<) y mayor que (>).

```<https://www.google.com.co/>```

<https://www.google.com.co/>

## Imagenes

Para colocar imagenes en nuestra página debemos utilizar primero el signo de admiración (!) 
luego el signo parentesis cuadrado ([]) y finalmente el parentesis (()) en el cual se anota la url de la 
imagen luego se deja un espacio y entre comillas ("") el nombre o el titulo de la imagen y este titulo es opcional.
Cuando nosotros pasamos el cursor por encima de la imagen vemos el titulo.

```![](url "titulo opcional")```

![](https://i0.wp.com/www.dondeir.com/wp-content/uploads/2017/02/destinos-con-paisajes-escondidos-en-mexico-12.jpg?ssl=1 "paisaje")

## Imagenes también con Enlace
Como ya dijimos podemos usar una imagen como enlace.
Tenemos que tener la imagen `![](url de la imagen)`

y el enlace `[](url del enlace)`

Para que la imagen nos sirva de enlace tenemos que unirlas.
Entre los parentesis cuadrados del enlace va la imagen asi:

```[![](url de la imagen)](url del enlace)```

[![](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQuWZKLIsftmkQsaEI1KM4t4fTgSeRi2MmRF0-8DQ0M6V-LqA1l)](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQuWZKLIsftmkQsaEI1KM4t4fTgSeRi2MmRF0-8DQ0M6V-LqA1l "gato")

 ## Citas en bloque 
Las citas podemos crearlas con el signo mayor que (>) al inicio de cada línea de la cita. 
Podemos crear un bloque qnnidado aumentando un signo (>).

Las citas en bloque deben comenzar y terminar con una línea en blanco.
asi se escribe:

```> El amor es la mayor frescura en la vida.```  
```>> este es un segundo nivel```

```>>> y este un tercer nivel```

Pablo Picasso

> El amor es la mayor frescura en la vida.  
>> este es un segundo nivel
>>> y este un tercer nivel


Salmo 1.1

> Bienaventurado el varón que no anduvo en consejo de malos,

> Ni estuvo en camino de pecadores,

> Ni en silla de escarnecedores se ha sentado;


## Bloques de código

Estos bloques de codigo van entre apostrofes invertidos ``código`` y es 
textualmente como escribimos en markdown.
Código es una serie de símbolos que por separado no representan nada, pero al 
combinarlos pueden generar un lenguaje comprensible.

```
   [Google](https://www.google.com.co/)
```

y vamos a verlo asi [Google](https://www.google.com.co/) 

## Pie de página

Son comentarios y aclaraciones que se hacen y para no interrumpir 
la lectura, se hacen al final de la página y se relacionan con el texto. 
Se puede agregar un texto de pie de página.

Markdown es un lenguaje de marcado ligero ```[^2]```Este está en alguna parte de la página

```[^2]:``` Marcado ligero es un tipo de formateo de texto más o menos estandarizado, 
   que ocupa poco espacio y es fácil de editar con un editor de texto.
   Este está en el final de la página.

## Fuentes
[arturogoga.com](https://www.arturogoga.com/tutorial-markdown-manera-simple-de-crear-texto-con-formato-especiales/)

[support](https://support.zendesk.com/hc/es/articles/203691016-Uso-de-Markdown-para-el-formato-de-texto)

[](https://spines.me/es/help/markdown/syntax/)

http://programminghistorian.github.io/ph-submissions/es/traducciones/introduccion-a-markdown







