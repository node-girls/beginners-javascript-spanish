# Reto 5: Aguja en un pajar

¿Puedes encontrar la aguja en el pajar?

Escribe una función `encontrarAguja()` que recibe cómo parámetro un array lleno de muchos elementos. Uno de estos elementos es la "aguja" que tendrás que encontrar con un bucle 'for'.

Después de encontrar la aguja, tu función debe devolver un mensaje \(de tipo 'string'\) que dice: `"La aguja se ha encontrado en la posición x"`, siendo la `x` el índice donde se haya localizado la aguja.

Así que esto...:

```javascript
var pajar = ['hay', 'conejo', 'aguja', 'sombrero'];

encontrarAguja(pajar);
```

...debe devolver:

```javascript
'La aguja se ha encontrado en la posición 2';
```

