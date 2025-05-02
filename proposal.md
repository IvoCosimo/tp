# Propuesta TP DSW

## Grupo
### Integrantes
* 52618 - Cosimo, Ivo
* 53246 - Ulla, Lucas

### Repositorios
* [frontend app](http://hyperlinkToGihubOrGitlab)
* [backend app](http://hyperlinkToGihubOrGitlab)

## Tema
### Descripción
Este proyecto consiste en el desarrollo de una página web para una tienda de ropa en línea, donde los usuarios podrán navegar por una variedad de productos, aplicar filtros de búsqueda, realizar pedidos con opción a pagarlos y ver su historial de pedidos.

### Modelo
![imagen del modelo](https://github.com/IvoCosimo/DerTp/blob/main/DER.jpg?raw=true)


## Alcance Funcional 

### Alcance Mínimo


Regularidad:
|Req|Detalle|
|:-|:-|
|CRUD simple|1. CRUD Usuario<br>2. CRUD Pedido|
|CRUD dependiente|1. CRUD Pedidos {depende de} CRUD Articulos y CRUD Usuarios|
|Listado<br>+<br>detalle| 1. Listado de articulos filtrados por categoria, talle y precio => Muestra articulos con su precio y descripcion <br> 2. Listado de pedidos realizados por el usuario => Muestra listado de pedidos, fecha, y articulos del pedido|
|CUU/Epic|1. Registro de usuario|


Adicionales para Aprobación
|Req|Detalle|
|:-|:-|
|CRUD |1. CRUD Usuario<br>2. CRUD Pedido<br>3. CRUD Articulos|
|CUU/Epic|1. Registro de usuario<br>2. Pago|


### Alcance Adicional Voluntario


|Req|Detalle|
|:-|:-|
|Listados |1. -|
|CUU/Epic|1. Editar datos usuario|
|Otros|1. Envío de pedido realizado al mail|


