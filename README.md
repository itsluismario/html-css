# HTML and CSS Summary

## Tipos de selectores

### Combinador de hijo directo

Selecciona todos los elementos del selector de la derecha que son **hijos directos** del selector de la izquierda. Estos selectores están separados por `>`.

### Combinador de elemento adyacente

Selecciona todos los elementos del selector de la derecha que están **adyacente** al selector de la izquierda. Estos selectores están separados por `+`.

### Combinador general de hermanos

Selecciona todos los elementos del selector de la derecha que son **hermanos** del selector de la izquierda. Estos selectores están separados por `~`.

[========]

## Pseudoclases y pseudoelementos
Una pseudoclase define el estilo de un estado especial de un elemento.

````html
selector :pseudoclase {
    propiedad: valor;
}
````

Un pseudoelemento define el estilo de una parte específica de un elemento. 

```html
selector ::pseudo-elemento {
    propiedad: valor;
}
```