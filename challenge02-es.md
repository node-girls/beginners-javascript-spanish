# Reto 2: escritoras famosos

¿Sabías que también se puede crear un array de objetos? Hemos creado uno para ti a continuación. Itera el array asignado a la varibale 'escritoras' y para cada objeto escribe a la consola (`console.log()`) la siguiente frase:

```js
'Hola, mi nombre es {nombre} {apellido}. Tengo {edad} años y trabajo como {profesion}.';
```

Ignora las llaves. Solo sirven para marcar las palabras que hay que reemplazar con otros valores. La frase que logueas a la consola debe ser como ésta:

```js
'Hola, mi nombre es Virginia Woolf. Tengo 59 años, y trabajo como escritora.';
```

Aquí tienes el array:

```js
var escritoras = [
  {
    nobre: 'Virginia',
    apellido: 'Woolf',
    profesion: 'escritora',
    edad: 59,
    viva: false
  },
  {
    nobre: 'Zadie',
    apellido: 'Smith',
    profesion: 'escritora',
    edad: 41,
    viva: true
  },
  {
    nobre: 'Jane',
    apellido: 'Austen',
    profesion: 'escritora',
    edad: 41,
    viva: false
  },
  {
    nobre: 'Bell',
    apellido: 'Hooks',
    profesion: 'escritora',
    edad: 64,
    viva: true
  }
];
```

Si quieres otro reto, solo haz el `console.log()` de los escritoras que siguen vivos.

### [Ir al Reto 3 >>>>](https://github.com/node-girls/beginners-javascript/blob/master/challenge03.md)
