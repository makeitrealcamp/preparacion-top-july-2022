# Ejercicios día 2

### Ejercicio 3

Crear una función llamada isAlive que reciba dos argumentos llamados playerName y points

isAlive debe retornar verdadero si playerName es igual a "ikk" y points es mayor a 30, o si playerName es igual a "gut" y points es mayor a 10. De lo contrario, debe retornar falso.

```
isAlive("ikk", 50) //=> true
isAlive("gut", 50) //=> true
isAlive("ikk", 20) //=> false
isAlive("gut", 5) //=> false
isAlive("trek", 50) //=> false
```

### Ejercicio 4

Escribir una función llamada factorial que retorne el factorial de un número, que es la multiplicación de los números (positivos) menores o iguales a ese número.

Por ejemplo, el factorial de 5 (se escribe 5!) es 120:

```
factorial(0) // => 1
factorial(1) // => 1
factorial(3) // => 6
factorial(5) // => 120
```

### Ejercicio 5

Crear una función longitud que encuentre la longitud de una cadena (string)

```
longitud("") //=> 0
longitud("Hola") //=> 4
longitud("You Rock") //=> 8 (contando el espacio)
```

### Ejercicio 6

Crear una función getBMI que le pida al usuario su peso y su altura para calcular su BMI e imprima la frase "Tu BMI es X".
P.D BMI por sus siglas en inglés, es un valor que determina la cantidad de grasa de una persona y se calcula con `peso / altura^2`

```
getBMI(65, 1.8) // => "Tu BMI es 20.061728395061728"
```
