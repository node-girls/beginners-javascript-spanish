# Sección 4: Variables

Cuando estás programando, vas a querer crear unos "atajos" para poder referirte a/referenciar elementos de tu código sin tener que escribir los mismos valores cada vez. En JavaScript tenemos las "variables" que nos permite almacenar valores que usaremos después en otras partes de nuestro código.

## Pruébalo

Puedes crear una variable usando el 'keyword' ('palabra reservada') `var` que indica a la aplicación que vas a almacenar un valor. También tienes que darle un nombre a la variable. Este nombre puede ser cualquier cosa siempre y cuando no incluya espacios.

Aquí hay un ejemplo de cómo crear una variable "artista" que almacena la cadena ('string') "Beyoncé Knowles".

```js
var artista = 'Beyoncé Knowles';

console.log(artista);
```

Fíjate en que una vez que has creado la variable puedes simplemente escribir el nombre de la variable donde sea que quieras hacer referencia a ella, en vez de escribir el nombre de Beyoncé cada vez. El nombre de una variable no se envuelve en comillas ya que no queremos que se confunda con una cadena.

Ejecuta el código de ejemplo. Debes ver 'Beyoncé Knowles' en la consola.

### Mini reto

Tu código de la sección será algo parecido a esto (tal vez incluyendo unos comentarios):

```js
console.log(typeof 'node girls');
console.log(typeof 1234);
console.log(typeof false);
```

Ahora que sabes cómo crear variables, vuelve a escribir este código. Esta vez, define los valores como variables al princípio del fichero. Después, refiérete a ellas/hazles referencia por sus nombres dentro de las declaraciones de `console.log()` en vez de escribir los valores.

¿Devuelve lo mismo el código refactorizado?

### [Ir a la Sección 5 >>>>](https://github.com/node-girls/beginners-javascript-spanish/blob/master/step05-es.md)
