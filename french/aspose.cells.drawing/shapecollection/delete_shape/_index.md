---
title: méthode delete_shape
second_title: Aspose.Cells for Python via .NET API Références
description:
type: docs
weight: 440
url: /fr/aspose.cells.drawing/shapecollection/delete_shape/
is_root: false
---
##  delete_shape(self, shape) {#aspose.cells.drawing.Shape}
Supprimer une forme. Si la forme fait partie du groupe ou est une forme de commentaire, elle ne sera pas supprimée.



```python

def delete_shape(self, shape):
    ...
```


| Paramètre| Taper| Description|
| :- | :- | :- |
| shape | [`Shape`](/cells/python-net/fr/aspose.cells.drawing/shape) |  |

###  Exemple

```python

# add first shape
firstShape = shapes.add_rectangle(2, 0, 2, 0, 50, 50)
# add second shape
secondShape = shapes.add_rectangle(6, 0, 2, 0, 30, 30)
# del
shapes.delete_shape(firstShape)

```



###  Voir également
* module [`aspose.cells.drawing`](../../)
* classe [`ShapeCollection`](/cells/python-net/fr/aspose.cells.drawing/shapecollection)
