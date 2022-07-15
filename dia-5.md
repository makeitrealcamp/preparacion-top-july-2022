### Ejercicio 13

Crear una función `transformToString` que convierta un numero a cadena de texto

```
transformToString(123) // => "123"
transformToString(999) // => "999"
```

### Ejercicio 14

Escribe una funcion llamada `palindrome` que recibe una cadena de texto. Determina si la cadena es palindrome considerando sólo caracteres alphanuméricos e ignorando si es mayúscula o minúscula.

```
palindrome("Atar a la rata") // => true
palindrome("vamos makers!") // => false
```

### Ejercicio 15

Para este ejercicio vas a crear un método llamado flatten el cual va a recibir cualquier tipo de argumento (string, numero, array) y debe devolver todos los parámetros en un arreglo simple
Nota: Cualquier matriz anidada sin importar su profundidad debe ser simplificada para poder devolver un arreglo simple

```
flatten(1, [2, 3], 4, 5, [6, [7]]) // => [1, 2, 3, 4, 5, 6, 7]
flatten('a', ['b', 2], 3, null, [[4], ['c']]) // = > // returns ['a', 'b', 2, 3, null, 4, 'c']

```
