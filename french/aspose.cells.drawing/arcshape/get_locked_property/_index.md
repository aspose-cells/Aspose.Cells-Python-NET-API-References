---
title: méthode get_locked_property
second_title: Aspose.Cells for Python via .NET API Références
description:
type: docs
weight: 130
url: /fr/aspose.cells.drawing/arcshape/get_locked_property/
is_root: false
---
##  get_locked_property(self, type) {#aspose.cells.drawing.ShapeLockType}
Obtient la valeur de la propriété verrouillée.


###  Retour

Renvoie la valeur de la propriété verrouillée.


```python

def get_locked_property(self, type):
    ...
```


| Paramètre| Taper| Description|
| :- | :- | :- |
| type | [`ShapeLockType`](/cells/python-net/fr/aspose.cells.drawing/shapelocktype) | Le type de propriété de forme verrouillée.|

###  Exemple

```python
from aspose.cells.drawing import ShapeLockType

noAdjustHandles = 0
if shape.get_locked_property(ShapeLockType.ADJUST_HANDLES):
    noAdjustHandles = 1

```



###  Voir également
* module [`aspose.cells.drawing`](../../)
* classe [`ArcShape`](/cells/python-net/fr/aspose.cells.drawing/arcshape)
