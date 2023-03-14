---
title: set_locked_property méthode
second_title: Aspose.Cells for Python via .NET API Références
description:
type: docs
weight: 200
url: /fr/aspose.cells.drawing/oleobject/set_locked_property/
is_root: false
---
##  set_locked_property(type, value) {#ShapeLockType-bool}
Définissez la propriété verrouillée.



```python
def set_locked_property(self, type, value):
    ...
```


| Paramètre| Taper| Description|
| :- | :- | :- |
| type | [ShapeLockType](/cells/python-net/fr/aspose.cells.drawing/shapelocktype) | Le type verrouillé.|
| value | bool | La valeur de la propriété.|

###  Exemple

```python
from aspose.cells.drawing import ShapeLockType

shape.set_locked_property(ShapeLockType.ADJUST_HANDLES, True)

```



###  Voir également
* module [aspose.cells.drawing](../../)
* classe [OleObject](/cells/python-net/fr/aspose.cells.drawing/oleobject)
