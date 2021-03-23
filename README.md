# Formato de Cabezeras
# Cabezera H1
## Cabezera H2
### Cabezera H3
#### Cabezera H4
##### Cabezera H5


# Formatos de titulos con underline
Soy como un titulo underline 1
------------------------------

Titulo con underline 2
======================

# Formatos de emphasis 

- Probando titulos con *italica* usando *astericos*
- Probando titulos con _italica_ usando _guiones bajos_
- Probando titulos con formatos **bold o strong usando dos astericos**
- Probando titulos con formatos __bold o strong usando doble guiones bajos__
- Probando titulos con formato de ~~tachado~~ 
- Ahora probando *italico* con **strong** y ~~tachado~~

# Tipos de listas

## Listas Ordenadas

1. Primer Item
2. Segundo Item
3. Tercer Item

## Listas Desordenadas

- Primer Item
- Tercer Item
- Cuarto Item

# Formato para Link

- [Esto es un enlance con markdown](https://www.google.com)
- [Enlace hacia el index](index.html)

# Formato para Imagenes

![alt descripcion img](https://www.ostraining.com/cdn/images/coding/github_logo_blog1.png)

# Code Snippets 
## Para pegar diferentes codigos


Codigo en JSON

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

Codigo en JavaScripts

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

# Formato para Tablas

| Head Name | Head Surname | Head DNI |
| --------- | ------------ | -------- |
| Homero    | Tompson      | 34279345 |
| Marge     | Tompson      | 33345493 |

# Formato para Citas

Esto es una prueba para hacer referencia a una cita:

> Aqui va una cita de algun autor, Libro, Pelicula, etc.

Con doble __*enter*__ se sale de la cita para continuar escribiendo.

>Probando de nuevo una cita

Probando que con doble __*enter*__ se sale de la cita

# Lineas Divisoras

Para dividir un parrafo o texto de otro se utiliza siempre un espacio de separacion del texto/parrafo con *enter* y 3 guiones medios.

---
Y luego se sigue escribiendo el siguiente texto o parrafo dividido por 3 astericos, siempre con un espacio de separacion del texto/parrafo

***
También se puede dividir por 3 guiones bajos, siempre con un espacio de separacion del texto/parrafo

___

