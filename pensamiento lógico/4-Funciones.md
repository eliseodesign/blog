# Funciones

Bloque de instrucciones con una funcionalidad especifica, para reutilizar dichas instrucciones, reorganiza la funcionalidad del código y cambia el flujo de trabajo.

Puedes escribir funciones con utilidades especificas como una función que pregunte algo esta dentro puede conteneder estructuras de control y de esta función se regresara una respuesta 

## ¿Por qué debemos usar funciones?

Si bien podrías tener tu lógica, tus instrucciones en un solo bloque es decir como códgio un simple estructura es mucho mejor ordenedar las instrucciones en funciones que pueden o no recibir valores y al final devolver un resultado luego de haber pasado por el flujo de instrucciones dentro de la función 

La estructura en la mayoría de lenguajes tendra la siguiente sintaxis:

```js

function preguntar(x){
  // x es la entrada
  // Acá va la logica

  return x 
  // return x es la salida
}
```


ahora el bloque anterior de instrucciones no se ejecuta con tan solo existir hay que **"invocarlo"** y para esto simplemente llamamos a esa función con su nombre:

```js
preguntar("eliseo")

// "eliseo" es x en el cuerpo de la función, es lo que le pasamos a la función al invocarla 
```