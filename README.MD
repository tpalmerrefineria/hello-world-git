# Cabecera H1
## Cabecera H2

# Underlines
Underline 1
-----------

Underline 2
===========

# Formatos de enfasis
- letra *italica* de la primera forma
- letra _italica_ de la segunda forma
- formato **bold o strong** de la primera forma.
- formato __bold o strong__ de la primera forma.
- formato ~~tachado~~, formato normal.
- aqui podemos usar *formato italico*, pero tambien **bold** y ~~tachado~~

# Listas
1. Esto es un item de lista ordenada
2. Esto es un item de lista ordenada
3. Esto es un item de lista ordenada
- Esto es un item de lista desordenada
- Esto es un item de lista desordenada
- Esto es un item de lista desordenada

# Links 
- <a href="http://www.google.com">Esto es un link HTML</a>
- [Esto es un link en Markdown](http://www.google.com)
- [Esto es un link al index](index.html)

# Imagenes
![Logo Github](https://cdn-icons-png.flaticon.com/512/25/25231.png)

# Code Snippets
Código en JSON
```JSON
{
    "glossary": {
        "title": "example glossary",
		"GlossDiv": {
            "title": "S",
			"GlossList": {
                "GlossEntry": {
                    "ID": "SGML",
					"SortAs": "SGML",
					"GlossTerm": "Standard Generalized Markup Language",
					"Acronym": "SGML",
					"Abbrev": "ISO 8879:1986",
					"GlossDef": {
                        "para": "A meta-markup language, used to create markup languages such as DocBook.",
						"GlossSeeAlso": ["GML", "XML"]
                    },
					"GlossSee": "markup"
                }
            }
        }
    }
}
```
Código en Javascript
```Javascript
{
const animals = ['pigs', 'goats', 'sheep'];

const count = animals.push('cows');
console.log(count);
// Expected output: 4
console.log(animals);
// Expected output: Array ["pigs", "goats", "sheep", "cows"]

animals.push('chickens', 'cats', 'dogs');
console.log(animals);
// Expected output: Array ["pigs", "goats", "sheep", "cows", "chickens", "cats", "dogs"]
}
```

# Tablas
| Nombre | Apellido | Documento | 
| ------ | -------- | --------- |
| Maxi   | Burgos   | 354681
| Tomas  | Tompson  | 324324

# Citas 
Esto es un texto referente a una cita que pondremos debajo:
> Esto es una cita

Esto es otro texto que no se relaciona con la cita anterior:
> Esto e sotra cita

# Lineas Divisoras
Esto es un texto que sera dividido por guiones medios.

---
Esto es otro texto dividido por asteriscos
***
Esto es otro texto dividido por guiones bajos.
___

# Saltos de linea
Esto es nuestro primer parrafo.

Esto es nuestro segundo parrafo.

Este es nuestro tercer parrafo.
- Lista 