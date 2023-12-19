# GRID

Se utiliza para dimensiones grandes, el layout de una pagina. Se utiliza en complemento con flexbox, este ultimo se utiliza para el contenido de lo que esta en grid.

## Partes
1. Grid container: contenedor padre
2. Grid items: contenedor hijo
3. Grid lines: son todas las lineas verticales u horizontales, incluye las lineas de borde. 4 lineas horizontales y 5 verticales
4. Grid tracks: 4 columnas y 3 filas. 
5. Grid area: es cualquier rectangulo limitado por grid lines
6. Grid cell: cada rectangulo entre dos tracks. (intersección) en este ejemplo grid cell es el primer rectangulo.


## Display
display: grid;

## grid-template-columns
grid-template-columns: 100px 200px 100px 100px;
grid-template-columns: 1fr 1fr 1fr 1fr;
grid-template-columns: repeat(4, 1fr);


## grid-template-rows
grid-template-rows: 50px 150px 200px;