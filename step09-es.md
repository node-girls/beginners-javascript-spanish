# Sección 9: Objetos

Ahora veremos el último tipo de datos: los objetos. Como los arrays, los objetos pueden almacenar varios trozos de información. La diferencia es que los objetos almacenan esta información en propiedades ("claves"). 
Por ejemplo, tal vez quieres guardar el nombre, modelo y color de un coche, o el nombre, hora y lugar de una película que se va a estrenar.

La sintaxis de un objeto es así:

```js
{
  propiedad1: "valor1",
  propiedad2: "valor2",
  propiedad3: "valor3"
}
```

Los nombres a mano izquierda ("propiedad1") son las propiedades o "claves" ("keys"). Puedes ponerles cualquier nombre y asignarles cualquier valor: cadenas, buleanos, números o funciones.

## Pruébalo

Vamos a definir un objeto que representa una persona:

```js
var persona = {
  nombre: 'Virginia',
  apellido: 'Woolf',
  profesion: 'escritora',
  edad: 59,
  viva: false
};
```

Podemos hacer un `console.log()` del objeto entero, pero tmabién podemos sacar solo una de sus propiedades. Ejecuta este código:

```js
console.log(persona.nombre);
```

## Mini reto

Usando el objeto que representa a una persona, hacemos un `console.log()` de una frase que represente a esa persona. Tienes que imprimir lo siguiente en la consola:

```js
'Hola, mi nombre es {nombre} {apellido}. Tengo {edad} años, y trabajo como {profesion}.';
```

Una pista: puedes construir una cadena como la anterior añadiendo varias cadenas de texto junto con las claves y valores del objeto con el operador de <strong>concatenación</strong>: `+`. Por ejemplo:

```js
var animal = {
  especie: 'gato',
  nombre: 'Tabitha'
};
console.log('Mi ' + animal.especie + 'se llama ' + animal.nombre + '.');
```

No te olvides incluir espacios donde hagan falta.

### [Ir a la Sección 1 >>>>](https://github.com/node-girls/beginners-javascript/blob/master/challenge01.md)
