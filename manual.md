# Markdown

Markdown es un sistema desarrollado por John Gruber y Aaron Swartz  con el fin de simplificar 
formatos y hacer mas facil la escritura de textos.
Los textos en markdown pueden ser exportados a html con facilidad.
Para convertir un texto en markdown a html basta con 

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

Este es un titulo 1
=============


para el titulo 2 colocar el título y en la siguiente linea el signo "--" seguidos al mismo tamaño del título.

```titulo 2```

```---------```

titulo 2
--------

## Negritas, cursivas e italicas

**Negritas** se hace con dos signos asterisco al comienzo de la palabra y dos al final de la palabra.

__Negrita con 2 rayas al piso__

***Esto es negrita y cursiva con tres asteriscos a cada lado***

___Esto es negrita y cursiva con tres rayas al piso a cada lado.___

*Cursiva con un asterisco a cada lado*

_Cursiva con una raya al piso_

*Italicas* se hace con un asterisco a cada lado del  texto.

_Italica_ se hace también rodeando la palabra con dos raya al piso

## Listas 

Para hacer listas no numeradas podemos utilizar los signos +, -, *

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

1. Leti
2. Amparito
3. Abby

## Listas anidadas
Para hacer listas anidadas se hacen las lista y a las listas anidadas se les coloca 
dos espacios antes del asterisco.
Estas listas pueden ser numeradas o no.

### Danzadores
+ niños
  + Jolman
  + José Angel
+ niñas
  + Aura
  + Sofia
  
  ## Enlaces

**Enlace** es un texto o una imagen que al pasar el cursor por encima se forma una manita y 
al hacer clic sobre ella nos lleva a otra página o a otra parte de la misma página.

### Hay dos clases de enlaces:

**Enlace interno** es cuando nos lleva a otra parte de la misma página. 

**Enlace externo** es cuando nos lleva a otra página.
Para crear un enlace externo rodeamos el texto para mostrar el vínculo entre corchetes ({}), 
y la url del enlace entre paréntesis (()).

```[Google](https://www.google.com.co/)```

[Google](https://www.google.com.co/)

Otra manera de colocar un enlace es encerrando la url entrelos caracteres menor (<) que y mayor que (>)

```<https://www.google.com.co/>```

<https://www.google.com.co/>

## Imagenes

Para colocar imagenes en nuestra página debemos utilizar primero el signo de admiración (!) 
luego el signo parentesis cuadrado ([]) y finalmente el parentesis (()) en el cual se anota la url de la 
imagen luego se deja un espacio y entre comillas ("") el nombre o el titulo de la imagen.

```![](url "titulo opcional")```

![](https://i0.wp.com/www.dondeir.com/wp-content/uploads/2017/02/destinos-con-paisajes-escondidos-en-mexico-12.jpg?ssl=1 "paisaje")

## Imagenes también con vínculo

Primero creamos la imagen ```![]()``` luego la rodeamos como vínculo 
```[![](url de la imagen)](url del vínculo)```

[![](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQuWZKLIsftmkQsaEI1KM4t4fTgSeRi2MmRF0-8DQ0M6V-LqA1l)](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQuWZKLIsftmkQsaEI1KM4t4fTgSeRi2MmRF0-8DQ0M6V-LqA1l "gato")

## Vídeo 

Las etiquetas de imagen con una extensión de video se convierten automáticamente a un reproductor de video.
Las extensiones de vídeo válidas son .mp4, .m4v, .mov, .webm y .ogv.

![](img/Dios Te Ama.mp4)

 ## Citas en bloque 
Las citas podemos crearlas con el signo mayor que (>) al inicio de cada línea de la cita. 
Podemos crear un bloque qnnidado aumentando un signo (>).
Las citas en bloque deben comenzar y terminar con una línea en blanco.

Pablo Picasso

> El amor es la mayor frescura en la vida.  
>> este es un segundo nivel
>>> y este un tercer nivel

```> El amor es la mayor frescura en la vida.```  
```>> este es un segundo nivel```

```>>> y este un tercer nivel```

Salmo 1.1

> Bienaventurado el varón que no anduvo en consejo de malos,

> Ni estuvo en camino de pecadores,

> Ni en silla de escarnecedores se ha sentado;


## Bloques de código

Estos bloques de codigo van entre apostrofes invertidos y es textualmente como escribimos en markdown.

```
   [Google](https://www.google.com.co/)
```

y vamos a verlo asi [Google](https://www.google.com.co/) 

## Pie de página

Son comentarios y aclaraciones que se hacen y para no interrumpir 
la lectura se hacen al final de la página y se relacionan. 
Se puede agregar un texto de pie de página.```[^2]```

```[^2]:``` Este es el pie de página.

Este es un ejemplo de "codigo en línea"

| Modelo | Color   | Precio |
| ------ |---------| ------:|
| Globe  | Negro   | 99€    |
| Scala  | Azul    | 199€   |
| Palais | Granate | 399€   |


