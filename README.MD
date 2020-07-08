# Versión del Curso
Versión actual: v1.2.2

# Cabeceras
# Cabecera H1
## Cabecera H2
### Cabecera H3
#### Cabecera H4
###### Cabecera H5
###### Cabecera H6

# Underlines

Underline 1
-----------

Underline 2
===========

# Formatos de énfasis

- formato *itálica* de la primera forma.
- formato _itálica_ de la segunda forma.

- formato **bold o strong** de la primera forma
- formato __bold o strong__ de la segunda forma

- formato ~~tachado~~, formato normal

- aquí podemos usar *formato itálico*, pero también **bold**, pero sin dejar el ~~tachado~~

# Listas

## Listas ordenadas

1. Esto es un item.
2. Esto es un item.
3. Esto es un item.

## Listas desordenadas

- item desordenado.
- item desordenado.
- item desordenado.

# Links

- <a href="https://www.google.com">Esto es un link html</a>

- [Esto es un link en markdown](https://www.google.com)

- [Esto es un link al index](index.html)

# Imágenes

![Logo Github](https://github.githubassets.com/images/modules/open_graph/github-mark.png)


# Code Snippets
Código en JSON
```JSON
[
  {
    "title": "apples",
    "count": [12000, 20000],
    "description": {"text": "...", "sensitive": false}
  },
  {
    "title": "oranges",
    "count": [17500, null],
    "description": {"text": "...", "sensitive": false}
  }
]
```
Código JavaScript

```JavaScript

function $initHighlight(block, cls) {
  try {
    if (cls.search(/\bno\-highlight\b/) != -1)
      return process(block, true, 0x0F) +
             ` class="${cls}"`;
  } catch (e) {
    /* handle exception */
  }
  for (var i = 0 / 2; i < classes.length; i++) {
    if (checkCondition(classes[i]) === undefined)
      console.log('undefined');
  }

  return (
    <div>
      <web-component>{block}</web-component>
    </div>
  )
}

export  $initHighlight;

```

# Tablas

| Nombre | Apellido | Documento |
| ------- | --------| ----------|
|Maxi    |Fernández| 12437658|
|Francisco   |Villa| 84934783|


# Citas

Esto es una cita referente a una cita que pondremos debajo:
> Esto es una cita

Esto es otro texto
> Esto es otra cita

# Lineas Divisoras

Esto será un texto que será dividido por guiones

---
Esto es otro texto dividido por asteriscos

***

Otra forma de dividir con guiones bajos

___

# Saltos de líneas 

Este es el primer párrafo.

Este es el segundo párrafo.

Este es el tercer párrafo.

