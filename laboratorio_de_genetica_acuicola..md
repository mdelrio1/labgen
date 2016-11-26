# Laboratorio de genética acuícola.

Markdown es un lenguaje de marcado de texto o una forma de escribir textos para páginas de internet tipo html y que se utiliza en la platforma del [GitHub] (https://github.com). Utiliza texto sencillo para poner el texto en itálicas, negritas, hacer tablas, listas, etc.

En la siguiente dirección se encuentran recomendaciones para usar el [Mark down] (https://guides.github.com/features/mastering-markdown/)

Por ejemplo para escribir una lista resaltando el encabezado y poniendo una lista con el nombre de las especies de abulón en itálicas y el nombre común en texto normal sería de la siguiente forma:
```
## Trabajamos con diferentes especies de abulón
1. *Haliotis fulgens*, abulón azul.
2. *Haliotis rufescens*, abulón rojo
3. *Haliotis corrugata*, abulón amarillo
```
con el resultado siguiente:
## Trabajamos con diferentes especies de abulón
1. *Haliotis fulgens*, abulón azul.
2. *Haliotis rufescens*, abulón rojo
3. *Haliotis corrugata*, abulón amarillo

## así como de peces
1. Marinos
  * Jurel
  * Totoaba
  * Lenguado
2. De agua dulce
  * Tilapia
  * Trucha

entre otros 

También se pueden combinar tipos de letra o efecto al texto
```
*Este texto se escribirá en itálicas*

_Este también se escribirá en itálicas_

**En negritas**

__También en negritas__

_Se **pueden** combinar_
```

*Este texto se escribirá en itálicas*

_Este también se escribirá en itálicas_

**En negritas**

__También en negritas__

_Se **pueden** combinar_

El símbolo # al inicio de la línea indica un encabezado, por ejemplo el siguiente código
```
# Encabezado 1
## Encabezado 2
### Encabezado 3
#### Encabezado 4
#### Encabezado 5
```
dará como resultado:
# Encabezado 1
## Encabezado 2
### Encabezado 3
#### Encabezado 4
#### Encabezado 5
se recomiendo dejar un espacio después del último #, porque he observado que en otros editores que usan Markdown no ponen la línea como encabezado si no hay espacio.

## Tablas

Este código 
```
Nombre columna 1| Nombre columna 2| Nombre *columna* 3| 
----------------|-----------------|-------------------|
valor 1|valor 2|valor 3|
valor 4|valor 5|valor 6|
valor 7|valor 8|valor 9|
```
generará la tabla siguiente:

Nombre columna 1| Nombre columna 2| Nombre *columna* 3| 
----------------|-----------------|-------------------|
valor 1|valor 2|valor 3|
valor 4|valor 5|valor 6|
valor 7|valor 8|valor 9|

obsérvese que columna del encabezado 3 está parcialmente en itálicas

#### Nota: se debe tener cuidado de tener un espacio antes y otro después de la tabla.

## para indicar una lista de actividades terminadas y pendientes:
```
- [x] @mdelrio1, se usa para señalar a algún usuario del github
- [x] #refs, 
- [x] los enlaces a otras páginas 
- [x] al poner 'x' se indica que se ha terminado '√'
- [ ] al no escribir 'x' la actividad está pendiente
```

- [x] @mdelrio1, se usa para señalar a algún usuario del github
- [x] #refs, 
- [x] los enlaces a otras páginas 
- [x] al poner 'x' se indica que se ha terminado '√'
- [ ] al no escribir 'x' la actividad está pendiente


Se pueden agregar emosiones usando los códigos entre :código: que se encuentran en:
[emoticons](http://www.emoji-cheat-sheet.com)
por ejemplo: 
`:smiley:` :smiley:
`:bowtie:` :bowtie:
`:+1:` :+1:

para escribir superíndices se usa 
`O(n<sup>2</sup>)`
O(n<sup>2</sup>)

para justificar texto

-> texto <-

## para escribir código o texto sin formato
```
function fancyAlert(arg) {
  if(arg) {
    $.facebox({div:'#foo'})
  }
}
```

### código simple
    function fancyAlert(arg) {
      if(arg) {
        $.facebox({div:'#foo'})
      }
    }

### Python

```
def foo():
      if not bar:
          return True
```
### más información sobre [Mark down](https://help.github.com/articles/basic-writing-and-formatting-syntax/)

