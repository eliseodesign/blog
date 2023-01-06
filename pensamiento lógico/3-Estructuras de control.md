# Estructuras de control
Nos permiten tomar desciciones en nuestros algoritmos, utilizan operadores y secuencias lógicas para crear un resultado 

- Condicionales: Permiten tomar desciciones a partir de una comparación 
  1. If / else 
  2. switch 
  3. Try / Catch
- Ciclos: Realizan iteraciones o repeticiones de código de acuerdo con cierta condición
  1. For
  2. While
  3. Do-while

## **If - else**
Los operadores lógicos son muy importantes en los condicionales 

Con palabra simples if-else es: Si algo pasa entonces se ejecuta algo sino algo más
Se puede usar solamente if para validar si algo sucede 

En lenguaje natural podemos decir:

      Si 3 > 2 entonces
      "Es mayor"

Para no dejarlo asi te muestro la lógica anterior escrita es javascript

```js
    if( 3>2 ){
      console.log("Es mayor")
    }

    // se muestra "Es mayor"
```
Tal vez te preguntes que hace console.log y pues nada mas imprime un valor 

Que pasaría si la condición en if no sería verdadera

```js
    if( 3>10 ){
      console.log("Es mayor")
    }

    // No se muestra nada
```
### **Else**

```js
    if( 3>10 ){
      console.log("Es mayor")
    }else{
      console.log("Es menor")
    }

    // se muestra "Es menor"
```

- - -
 
## **Switch**

Un switch es util para validar diferentes valores mas que un if-else en el switch podrías validar multiples valores

Se compone de la siguiente manera:

```js
  comida = "manzana"

  switch(comida){
    case "manzana":
      console.log("Es manzana")

    case "pera"
      console.log("Es pera")

    
  }
```

Esto es de manera sencilla switch es javascript pero le falta la palabra break la cual no utilice para no hacer mas dificil de leer el código 

A switch le pasamos la variable y cada case sera un caso posible de esa variable 

## Ejemplo práctico 
### Validar si una persona es mayor de edad
