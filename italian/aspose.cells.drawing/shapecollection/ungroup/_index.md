---
title: Metodo ungroup
second_title: Aspose.Cells for Python via .NET API Riferimenti
description:
type: docs
weight: 500
url: /it/aspose.cells.drawing/shapecollection/ungroup/
is_root: false
---
##  ungroup(self, group) {#aspose.cells.drawing.GroupShape}
Separa gli elementi della forma.



```python

def ungroup(self, group):
    ...
```


| Parametro| Tipo| Descrizione|
| :- | :- | :- |
| group | [`GroupShape`](/cells/python-net/it/aspose.cells.drawing/groupshape) | La forma del gruppo.|
###  Osservazioni

Se la forma del gruppo è raggruppata da un'altra forma del gruppo, non verrà fatto nulla.
###  Esempio


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



###  Guarda anche
* modulo [`aspose.cells.drawing`](../../)
* classe [`ShapeCollection`](/cells/python-net/it/aspose.cells.drawing/shapecollection)
