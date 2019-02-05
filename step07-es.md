# Sección 7: Funciones

Hemos estado escribiendo código que ejecuta distintas acciones, pero a veces queremos agrupar código para lograr un objetivo en particular. En estos casos debemos usar una función.

Una función es un bloque de código diseñado a llevar a cabo una tarea específica y se ejecuta cuando "se invoca".

A continuación vemos la sintaxis de una función:

```js
function functionName(parámetros) {
  // código a ejecutar
}
```

Puedes dar a una función el nombre que quieras, igual que una variable. También puedes pasar a una función valores distintos cada vez que la ejecutas - estos valores son llamados "parámetros".

Para ejecutar una función, la invocamos de esta manera:

```js
functionName();
```

### Pruébalo

Vamos a escribir una función que suma dos números. Vamos a llamarla `add`. Queremos sumar dos números diferentes cada vez, así que tenemos que definir dos parámetros para representar esto, `x` y `y`.

```js
function add(x, y) {
  // código a ejecutar
}

add(2, 3);
```

Fíjate que hemos invocado la función con los parámetros `2` y `3`. Dentro de la función, intenta hacer un `console.log()` de `x` y `y` para ver qué pasa. Intenta imprimir estos parámetros en la consola desde fuera de la función también. Tendrán el valor "undefined" (sin definir) ya que solo podemos acceder a ellos desde dentro de la función.

```js
function add(x, y) {
  console.log(x);
  console.log(y);
}

add(2, 3);
```

Ahora queremos sumar estos dos números, pero no basta con escribir `x + y` puesto que no hemos dicho a la función que queremos que nos devuelva algo. Aquí entra la declaración `return`. Normalmente con `return` es como se termina una función. El `return` especifica el valor que queremos que devuelva la función.

```js
function add(x, y) {
  return x + y;
}

add(2, 3);
```

Ejecuta este código. ¡Con suerte te dará la respuesta correcta! :)

### Mini reto

Escribe una función `multiply` que multiplica dos números. Debe recibir dos números como parámetros y devolver la respuesta correcta.

### [Ir a la Sección 8 >>>>](https://github.com/node-girls/beginners-javascript/blob/master/step08.md)
