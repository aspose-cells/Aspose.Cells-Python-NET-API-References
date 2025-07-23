---
title: método get_cell_display_style
second_title: Aspose.Cells for Python via .NET API Referencias
description:
type: docs
weight: 320
url: /es/aspose.cells/cells/get_cell_display_style/
is_root: false
---
##  get_cell_display_style(self, row, column) {#int-int}
Obtener el estilo de visualización de la celda dada.


###  Devoluciones

el estilo de visualización de la celda dada.


```python

def get_cell_display_style(self, row, column):
    ...
```


| Parámetro| Tipo| Descripción|
| :- | :- | :- |
| row | int | índice de fila de la celda dada|
| column | int | columna de la celda dada|
###  Observaciones

Lo mismo con [`Cell.get_display_style`](/cells/python-net/es/aspose.cells/cell/get_display_style),
Y lo mismo con el uso de [`BorderType.SIDE_BORDERS`](/cells/python-net/es/aspose.cells/bordertype#SIDE_BORDERS)
para [`Cells.get_cell_display_style`](/cells/python-net/es/aspose.cells/cells/get_cell_display_style).

##  get_cell_display_style(self, row, column, adjacent_borders) {#int-int-aspose.cells.BorderType}
Obtener el estilo de visualización de la celda dada.


###  Devoluciones

el estilo de visualización de la celda dada.


```python

def get_cell_display_style(self, row, column, adjacent_borders):
    ...
```


| Parámetro| Tipo| Descripción|
| :- | :- | :- |
| row | int | índice de fila de la celda dada|
| column | int | columna de la celda dada|
| adjacent_borders | [`BorderType`](/cells/python-net/es/aspose.cells/bordertype) | Indica qué bordes deben comprobarse y ajustarse según los bordes de las celdas adyacentes.<br/>Consulte la descripción del mismo parámetro de<br/>[`Cell.get_display_style`](/cells/python-net/aspose.cells/cell/get_display_style). |
###  Observaciones

Si la celda también se ve afectada por otras configuraciones como formato condicional, objetos de lista, etc.,
Entonces el estilo de visualización puede ser diferente al [`Cells.get_cell_style`](/cells/python-net/es/aspose.cells/cells/get_cell_style).
Y debido a que esas configuraciones también se pueden aplicar a celdas vacías (no existentes),
El uso de este método puede evitar la creación de esas celdas vacías.
Por lo tanto, el rendimiento será mejor que obtener la instancia Cell desde Cells
y luego llamar al [`Cell.get_display_style`](/cells/python-net/es/aspose.cells/cell/get_display_style).


###  Ver también
* módulo [`aspose.cells`](../../)
* clase [`Cells`](/cells/python-net/es/aspose.cells/cells)
