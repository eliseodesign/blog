# Tipos de datos

[siguiente](./2-Tipos%20de%20datos%20complejos.md)

## Qué es un dato 
Básicamente información con la cual traves de operaciones podemos tomar desciciones dentro de una estructura más grande llamada algoritmo 

Los datos son la base de todo, componen estructuras y operaciones 

## Tipos de datos 

- String (Texto): estan compuesto por letras las llamamos cadenas de caracteres de caracteres **"string"**. Ejemplo: "Ana estudia".

  *Observa que se encuentra entre comillas, y los espacios también cuentan como caracteres*

  ### **Concatenación** 
  Significa unir cadenas de caracteres. En muchos leguajes se usa el operador suma (+) 

  *"Ana estudia"* + *"2 lenguajes"*
  
  El resultado sería *"Ana estudia2 lenguajes"*

  ### **¿Por qué esta junto "estudia2"?**
  Porque el primer string termina en "a" y el segundo empieza por "l" en ningun momento hay un espcio entre estos 

<br>

- Number (Número):
  - Entero: un número simple sin adicion ni nada mas *(int)* en muchos lenguajes: 1 2 -4 12 100
  - Flotante: un número con decimales *(float)*: 1.12 8.21 -80.20
    ### **Operaciones**
    Simplemente es como en matematicas usamos operadores, suma, resta, multiplicación y división ( + - * / ) existen más operadores.

    ### **Concatenación string y numero**
    En muchos lenguajes de programación esto dara error pero en algunos de tipado debil los concatenara como strings

    | Tipado | "Hola" + 2 | "10" + 1
    | ---| ---| --- |
    |fuerte| *error* | *error*
    |débil| "Hola2" |

<br>

- Bolean (Boleano): básicamente solo hay dos resultados, y se usa normalmente para tomar desciciones en el algoritmo 
    | True | False| 
    | :---: | :---: |
    | 1 | 0 |
    