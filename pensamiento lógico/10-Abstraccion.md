# Abstracción 
Principio básico de la programación, la abstracción 

## ¿QUÉ ES LA ABSTRACCIÓN?
Es aislar un elemento de su contexto o de los elementos que lo rodean, es quitar cualquier detalle o atributo a un objeto o sistema para así enfocarnos en los detalles mas importantes.

Así podemos simplificar problema abstrayendo componentes, abstrayendo funcionalidades etc...
Podemos tener varías capas de abstracción para simplificar así mucho más un problema 

## ABSTRACIÓN EN INFORMATICA

La base de la comunicación de información el como funciona por ejemplo youtube o cualquier medio de información (entender informción como cualquier dato en forma de bits), el modelo de osi define siete capas  de red, cada capa simplifica los detalles de las anteriores para concentrarse en los detalles nuevos de esa capa 

## COMO APLICARLA 
Una forma de verlo es mover la complejida a otra capa de abstracción para verlo de otra forma mas sencilla y dejar de lado el anterior contexto para enfocarse en el despues.

## EJEMPLO PRÁCTICO 

Ejercicio: solución que convierta numero decimal a binario
```js
/* No hay problema si no entiendes todo el código, simplemente es una función que convierte decimal a binario usando un ciclo 
- - - - - - - - -
Abstraemos la funcionalidad de división entera que devuelve residuo */
const divInt = (a, b) => ([~~(a/b), a%b]) 

function toBinary(number:number):string{
  if(number === 0) return "0"

  let binary:number[] = [] 

  while(number > 0){ 
    const [int, rem] = divInt(number, 2) //usamos divInt
    binary = [...binary, rem]
    number = int
  }
  return binary.reverse().join("")
}


```

Este es un ejemplo muy pequeño de una función pero se pueden llegar abstraer sistemas completos 


## PELIGROS EN LA ABSTRACCIÓN

El unico problema que no te resuelven las capas de abstracción es tener demasiadas capas de abstracción, puede ser que alguna capa superior duplique funcionalidad, esto conlleva ineficiencia, o crear complejidad innecesaria

¿Cuántas capas de abstracción necesito?
R/ Las necesarías