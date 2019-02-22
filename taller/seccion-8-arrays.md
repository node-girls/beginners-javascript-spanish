# Sección 8: Arrays

Antes mencionamos que hay otros tipos de datos aparte de cadenas, números y buleanos \(lógicos\). Un array es uno de ellos. Los arrays nos permiten almacenar varios valores juntos de forma sencilla.

Se ponen los valores entre corchetes, separados por comas. Aquí tienens un ejemplo de la sintaxis:

```javascript
[valor1, valor2, valor3];
```

Se puede usar un array para almacenar cualquier tipo de dato: cadenas, números, buleanos, incluso otros arrays u objetos \(veremos esto en la siguiente sección\).

### Pruébalo

Definimos un array como una variable, de esta manera:

```javascript
var animales = ['tigre', 'perro', 'serpiente', 'llama'];
```

¡Mola! Ahora tienes todos los animales juntos en un grupo y no has tenido que crear una variable para cada uno por separado. Puedes ver cuántos animales hay en tu array usando el método `.length`:

```javascript
console.log(animales.length);
```

Si quieres referirte a un elemento específico del array, puedes usar su "índice o posición" así:

```javascript
console.log(animales[1]);
```

Adivina cuál de los animales del array se imprime en la consola.

Spoiler: va a imprimir "perro". Eso te parecerá raro hasta que aprendas que JavaScript es un lenguaje de tipo "índice-0". Esto significa simplemente que JavaScript empieza a contar desde 0 los elementos de un array. Así que `animales[0]` imprimirá "tigre". Nosotras no hacemos las reglas ;\)...

{% hint style="info" %}
### Mini reto

¿Cómo harías un `console.log()` del nombre de cada animal en el array?

Si estás pensando en usar un bucle "for" has acertado. Esta es la oportunidad perfecta para usar tus nuevos conocimientos para resolver un problema.

Si te atascas, usa Google para encontrar la respuesta. Saber hacer búsquedas en Google es una parte fundamental de la vida de una desarrolladora.
{% endhint %}

