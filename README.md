# CSS Grid Básico
Con motivo del #PlatziDay estube realizando este curso de CSS Grid básico.

### Contenedor
Es el elemento que va a tener mas elementos dentro

### items 
Elementos que estan dentro del contenedor y son los que van a tener propiedades de grid

### Lineas
Son las que dividen y limitan los elementos de la grilla por filas y columnas, inciando a contar las columnas de izquierda a derecha y las filas de arrbia hacia abajo.

### Rows
Filas

### Columns
Columnas

### Celda
Unidad minima que tenemos dentro de la grilla, esta delimita por 4 lineas y ocupa una fila y una columna

### Grupos de celdas (Track/Area)
Tracks o áreas, un track ocupa una sola fila o una sola columna, mientras que un área puede ocupar varias filas y columnas.


## Propiedades del contenedor
- Display grid
- Grid-template
- Gaps
- Grid-auto

## Propiedades de aliniación de los Items
Ayudan a alinear todos los items

- Justify-items : aliena de manera horizaontal
- Align-items: alinea de manera vertical
- Place-items: alinea horizontal y verticalmente

<br>

Propiedades que alinean la grilla completa

<br>

- Justify-content
- Align-content
- Place-content

<br>

propiedades para,los hijos de la grilla

- Justify-self
- Align-self
- Place-self

<br>

## Propiedades de ubicacion
- grid-colum
        - grid-column-start
        - grid-column-end

- grid-row
        - grid-row-start
        - grid-row-end

- grid-area

## Grid template areas

## Funciones especiales de Grid
- minmax: minimo y maximo de una celda
- repeat

## Keyword especiales
 - fr: una fraccion de la grilla, se ajusta al ancho que tiene la grilla
 - min-content
 - max-content
 - auto-fill/auto-fit