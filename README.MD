# Cabeceras 
# Cabecera H1 
## Cabecera H2
### Cabecera H3
#### Cabecera H4
##### Cabecera H5
###### Cabecera H6

# Underlines
Underline 1
-------------

Underline 2
==============

# Formatos de enfasis
-vformato *italica* de la primer forma
- formato _italica_ de la segunda forma
- formato **bold o strong** de la primer forma
- formato __bold o strong__ de la segunda forma
- formato ~~tachado~~.formato normal
- aqui podemos usar *formato italica*,pero tambien **bold** y ~~tachado~~.

#Listas
1. Esto es un intem de lista ordenada.
2. Esto es un intem de lista ordenada.
3. Esto es un intem de lista ordenada.
-  Esto es un item de lista desordenada.
-  Esto es un item de lista desordenada.
-  Esto es un item de lista desordenada.

# Links
- <a href="http//www.google.com">Esto es un link HTML<>
- [Esto es un link en Markdown](http://www.google.com)
- [Esto es un link en Index](index.html)

# Imagenes
![Logo Github](https://upload.wikimedia.org/wikipedia/commons/thumb/c/cd/Visual_Studio_2017_Logo.svg/164px-Visual_Studio_2017_Logo.svg.png)

# Code Snippets
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
Codigo en Javascript

```Javascript
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
|--------| -------- | --------- |
| Maxi   | Burgos   | 343242
| Tomas  | Tompson  | 636534

# Citas
Esto es un texto referente a un cita que pondremos debajo:
> Esto es una cita.

Esto es otro texto que no se relaciona con la cita anterior:
>Esto es otra cita.


# Lineas Divisoras
Esto es un texto que sera dividido por guiones medios.

---
Esto es otro texto dividido por astericos.

***

Esto es otro texto dividio por guiones bajos.
___
