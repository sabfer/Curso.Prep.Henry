## Variables: 
Las variables son objetos que se guardan en la memoria y conservan un valor, este valor puede ser un número, una cadena de texto, una función.

<br>

## Strings: 
Son cadenas de texto simple, es decir, una oración o frase. Ej: "Hola, soy Sabino"

<br>

## Funciones (argumentos, `return`):

Las funciones son programas que nos permiten ejecutar tareas, ejem:


  ```
  function saludar() {
      return "Hola"
    }
  ```

  La función de arriba se llama "saludar" y nos devuelve un "Hola". 

  Ahora las funciones pueden recibir argumentos, éstos son valores que sirven para ejecutar tareas más complejas, ejem:

  ```
  function suma(a, b) {  // a y b son argumentos de la funcion
    return a + b
  }
  ```

  Cuando yo llame a la función "suma" yo puedo asignarle un valor a "a" y "b" ejemplo:
  ```
       a + b
  suma(3 , 3) = 6

  ``` 
  La tarea de la función es sumar a y b.

  Nota que en las funciones de ejemplo que estoy utilizando uso **"return"** esta es una *keyword* que le dice a la función que retorne el valor que resuelve y todo lo que se coloque debajo del return no es ni siquiera visto por la función.

<br>

### Declaraciones `if`:

if son como funcionas que comprueban si un valor es true or false y dependiendo de esto ejecutan una u otra operación

```
  let a = 2
  let b = 3

  if (a === 2) {
    console.log(b)
  } else {
    console.log('no sé quien soy')
  }
```
<br>

### Valores booleanos (`true`, `false`)

Son valores de verdadero o falso, dependiendo de cuando y como se usen su valor puede ser usado para ejecutar o detener algo. Son valores de verificación o comprobación,  por ejemplo en la declaración if de arriba 

```
(a === 0)
```

Es una verificación de true or false.