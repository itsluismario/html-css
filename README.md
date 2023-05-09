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

[========]

## Tipos de displays

### Visualización en bloque (block)
El display block **establece que un elemento ocupará todo el espacio disponible por defecto y el siguiente elemento a este se situará por debajo.

Es posible añadir medidas de anchura width y altura height a estos a elementos.

También es posible agregar todas las propiedades del modelo de caja (no te preocupes de este concepto, ya lo abordaremos).

### Visualización en línea (inline)
El display inline establece que un elemento ocupará el espacio del contenido del mismo y el siguiente elemento se situará a la derecha.

No es posible añadir medidas de anchura width y altura height a estos a elementos.

También, no es posible agregar todas las propiedades del modelo de caja, únicamente funcionará la propiedad margin en el eje horizontal (no te preocupes de este concepto, ya lo abordaremos).

### Visualización de bloque y línea (inline-block)
El display inline-block combina las ventajas de bloque de colocar medidas al elemento y propiedades del modelo de caja correctamente; con las ventajas de inline de color un elemento seguido de otro en el mismo espacio.

Si elemento excede el contenido total, se coloca en la siguiente línea por debajo.


### Qué es flexbox

*Flexbox* consiste en el **ordenamiento de elementos hijos en un solo eje**, por defecto horizontalmente. El elemento padre o contenedor deberá contener la propiedad `display` con el valor `flex`. A partir de aquí, ya puedes ordenar los hijos según sea necesario.

### Qué es grid

*Grid* consiste en el **ordenamiento de elementos hijos en dos ejes**, como si fuera una cuadrícula o tabla. El elemento padre o contenedor deberá contener la propiedad `display` con el valor `grid` y debes definir las medidas de las columnas y de las filas. A partir de aquí, ya puedes ordenar los hijos según sea necesario.

[========]

## Modelo de caja

El modelo de caja se compone de cuatro elementos: margin, border, padding y contenido.


