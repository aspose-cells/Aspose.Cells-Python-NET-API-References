---
title: méthode ungroup
second_title: Aspose.Cells for Python via .NET API Références
description:
type: docs
weight: 500
url: /fr/aspose.cells.drawing/shapecollection/ungroup/
is_root: false
---
##  ungroup(self, group) {#aspose.cells.drawing.GroupShape}
Dissocie les éléments de forme.



```python

def ungroup(self, group):
    ...
```


| Paramètre| Taper| Description|
| :- | :- | :- |
| group | [`GroupShape`](/cells/python-net/fr/aspose.cells.drawing/groupshape) | La forme du groupe.|
###  Remarques

Si la forme du groupe est regroupée par une autre forme de groupe, rien ne sera fait.
###  Exemple


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



###  Voir également
* module [`aspose.cells.drawing`](../../)
* classe [`ShapeCollection`](/cells/python-net/fr/aspose.cells.drawing/shapecollection)
