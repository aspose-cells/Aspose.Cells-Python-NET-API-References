---
title: método set_outline_borders
second_title: Aspose.Cells for Python via .NET API Referencias
description:
type: docs
weight: 200
url: /es/aspose.cells/range/set_outline_borders/
is_root: false
---
##  set_outline_borders {#aspose.cells.CellBorderType-aspose.cells.CellsColor}
Establece los bordes del contorno alrededor de un rango de celdas con el mismo estilo y color de borde.



```python
def set_outline_borders(self, border_style, border_color):
    ...
```


| Parámetro| Tipo| Descripción|
| :- | :- | :- |
| border_style | [`CellBorderType`](/cells/python-net/es/aspose.cells/cellbordertype) | Estilo de borde.|
| border_color | [`CellsColor`](/cells/python-net/es/aspose.cells/cellscolor) | Color del borde.|


##  set_outline_borders {#aspose.cells.CellBorderType-aspose.pydrawing.Color}
Establece los bordes del contorno alrededor de un rango de celdas con el mismo estilo y color de borde.



```python
def set_outline_borders(self, border_style, border_color):
    ...
```


| Parámetro| Tipo| Descripción|
| :- | :- | :- |
| border_style | [`CellBorderType`](/cells/python-net/es/aspose.cells/cellbordertype) | Estilo de borde.|
| border_color | aspose.pydrawing.Color | Color del borde.|


##  set_outline_borders {#list-aspose.pydrawing.Color[]}
Establece límites de línea alrededor de un rango de celdas.



```python
def set_outline_borders(self, border_styles, border_colors):
    ...
```


| Parámetro| Tipo| Descripción|
| :- | :- | :- |
| border_styles | list |Estilos de borde.|
| border_colors | aspose.pydrawing.Color[] | Colores de borde.|
###  Observaciones

Tanto la longitud de borderStyles como de borderStyles deben ser 4.
El orden de borderStyles y borderStyles debe ser arriba, abajo, izquierda, derecha.


###  Ver también
* módulo [`aspose.cells`](../../)
* clase [`Range`](/cells/python-net/es/aspose.cells/range)
