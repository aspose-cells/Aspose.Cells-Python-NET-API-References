---
title: método delete_in_range
second_title: Aspose.Cells for Python via .NET API Referencias
description:
type: docs
weight: 430
url: /es/aspose.cells.drawing/shapecollection/delete_in_range/
is_root: false
---
##  delete_in_range(self, ca) {#aspose.cells.CellArea}
Eliminar formas del rango.Las formas de comentario no se eliminarán.



```python

def delete_in_range(self, ca):
    ...
```


| Parámetro| Tipo| Descripción|
| :- | :- | :- |
| ca | [`CellArea`](/cells/python-net/es/aspose.cells/cellarea) |El rango. Si las formas están contenidas en el rango, se eliminarán.|

###  Ejemplo

```python
from aspose.cells import CellArea

# add first shape
shapes.add_rectangle(2, 0, 2, 0, 50, 50)
# add second shape
shapes.add_rectangle(6, 0, 2, 0, 30, 30)
area3 = CellArea()
area3.start_column = 0
area3.start_row = 5
area3.end_column = 5
area3.end_row = 8
# del
shapes.delete_in_range(area3)

```



###  Ver también
* módulo [`aspose.cells.drawing`](../../)
* clase [`ShapeCollection`](/cells/python-net/es/aspose.cells.drawing/shapecollection)
