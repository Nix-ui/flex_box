# Flexbox

- [Flexbox](#flexbox)
  - [Uso del Flexbox](#uso-del-flexbox)
    - [Contenedor flexible](#contenedor-flexible)
    - [Elementos flexibles](#elementos-flexibles)


##  Uso del Flexbox
> El uso del Flexbox es muy sencillo, solo se debe de tener en cuenta que las propiedades que se van a utilizar son:
### Contenedor flexible
La propiedad **display:fles** o **display:inline-flex** nos permite crear un contenedor flexible. cuyos elementos hijos se llaman elementos flexibles.
- Eje Principal: Horizontal
- Eje Transversal:  Vertical
### Elementos flexibles
- Definicion la direccion del eje principal
  - **flex-direction: row | row-reverse | column | column-reverse**
  - por defecto: row
- Pocisionamiento de los elementos flexibles 
  - **justify-content: flex-start | flex-end | center | space-between | space-around | space-evenly**
  - por defecto: flex-start
- Wrap de los elementos flexibles
  - **flex-wrap: nowrap | wrap | wrap-reverse**
  - por defecto: nowrap
- Pocicionamiento de los elementos flexibles en el eje transversal
  - **align-items: flex-start | flex-end | center | baseline | stretch**
  - por defecto: flex-start
- Pocicionamiento de las lineas de los elementos flexibles en el eje transversal
  - **align-content: flex-start | flex-end | center | space-between | space-around | stretch**
  - por defecto: flex-start
- Orden de los elementos flexibles
  - **order: number**
  - por defecto: 0
- Tamaño inicial de los elementos flexibles
  - **flex-basis: auto | number**
- Tamaño Final de los elementos flexibles(Factor de crecimiento)
  - **flex-grow: number**