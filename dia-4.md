### Ejercicio 10

Crear una función llamada order que reciba dos argumentos, el primero será un arreglo de números y el segundo un booleano que llamaremos reverse que es opcional.

Si el valor de reverse es verdadero la función debe retornar el arreglo de mayor a menor, de lo contrario lo deberá organizar de menor a mayor

```
order([1, 2, 3], true) //=> [3, 2, 1]
order([5, 2, 1, 3, 4]) //=> [1, 2, 3, 4, 5]
```

### Ejercicio 11

Crea una función llamada max que reciba un arreglo de números como argumento y retorne el número mayor.

**Nota:** No utilices el método Math.max de JavaScript.

```
max([1, 2, 3, 4]) // => 4
max([63, 85, 39, 24, 3]) // => 85
```

### Ejercicio 12

Escribir una función pattern que genere el siguiente patron hasta n numero de filas. Si el argumento es 0 o es un numero negativo entonces debe devolver un string vacío e.g ""

**pattern(4)**

```
1234
234
34
4
```

**pattern(6)**

```
123456
23456
3456
456
56
6
```

**Nota:** no hay espacios en blanco y puedes usar \n en la cadena de texto para saltar a la siguiente linea
