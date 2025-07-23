---
title: método group
second_title: Aspose.Cells for Python via .NET API Referencias
description:
type: docs
weight: 460
url: /es/aspose.cells.drawing/shapecollection/group/
is_root: false
---
##  group(self, group_items) {#list}
Agrupa las formas.


###  Devoluciones

Devuelve la forma group.


```python

def group(self, group_items):
    ...
```


| Parámetro| Tipo| Descripción|
| :- | :- | :- |
| group_items | list | los elementos del grupo.|
###  Observaciones

Las formas en el grupoItems no deben agruparse.
La forma debe estar en esta colección de formas.
###  Ejemplo

```python

# add first shape
shapes.add_rectangle(2, 0, 2, 0, 50, 50)
# add second shape
shapes.add_rectangle(6, 0, 2, 0, 30, 30)
shapesArr = [shapes[0], shapes[1]]
groupShape = shapes.group(shapesArr)

```



###  Ver también
* módulo [`aspose.cells.drawing`](../../)
* clase [`ShapeCollection`](/cells/python-net/es/aspose.cells.drawing/shapecollection)
