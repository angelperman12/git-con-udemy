# CABECERAS
- CABECERAS: Igual que en HTML los # representan los (H#) encabezados.
# Cabecera H1
## Cabecera H2
### Cabecera H3
#### Cabecera H4
##### Cabecera H5
###### Cabecera H6

# UNDERLINES

- Los Underlines son alternativas a las cabeceras, se usa --- para Underline1 y === para Underline 2

Underline 1
------------

Underline 2
====

# EMPHASIS
- Para EMPHASIS que es el formato de texto se usa: encerar en * o _ para italica ** o __ para bold/strong y ~~ para tachado.
- *Formato en Italica*
- __Formato Strong__
- ~~Formato Tachado~~

# LISTAS
1. Lista ordenada
2. Lista ordenada
3. Lista ordenada
- Lista no ordenada
- Lista no ordenada
- Lista no ordenada

# LINKS
[Links en MARKDOWN](http://www.google.com)

# IMAGENES
![GitHub](https://bitemycoin.com/wp-content/uploads/2018/06/GitHub-Logo.png)

# Snippets
Snippet de Markdown
``` GO
package main

import "fmt"

func main() {
    ch := make(chan float64)
    ch <- 1.0e10    // magic number
    x, ok := <- ch
    defer fmt.Println(`exitting now\`)
    go println(len("hello world!"))
    return
}
export $initHighlight;
```

# Tablas
|COLUMNA 1 | COLUMNA 2 | COLUMNA 3 |
|----------|-----------|-----------|
|R1 |R2 |R3|
