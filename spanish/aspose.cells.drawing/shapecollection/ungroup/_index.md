---
title: método ungroup
second_title: Aspose.Cells for Python via .NET API Referencias
description:
type: docs
weight: 500
url: /es/aspose.cells.drawing/shapecollection/ungroup/
is_root: false
---
##  ungroup(self, group) {#aspose.cells.drawing.GroupShape}
Desagrupa los elementos de forma.



```python

def ungroup(self, group):
    ...
```


| Parámetro| Tipo| Descripción|
| :- | :- | :- |
| group | [`GroupShape`](/cells/python-net/es/aspose.cells.drawing/groupshape) | La forma del grupo.|
###  Observaciones

Si la forma del grupo está agrupada por otra forma de grupo, no se hará nada.
###  Ejemplo


```python

# add first shape
shapes.add_rectangle(2, 0, 2, 0, 50, 50)
# add second shape
shapes.add_rectangle(6, 0, 2, 0, 30, 30)
# group
shapesArr = [shapes[0], shapes[1]]
groupShape = shapes.group(shapesArr)
# ungroup
shapes.ungroup(groupShape)

```



###  Ver también
* módulo [`aspose.cells.drawing`](../../)
* clase [`ShapeCollection`](/cells/python-net/es/aspose.cells.drawing/shapecollection)
