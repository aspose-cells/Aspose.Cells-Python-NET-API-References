---
title: height_in_shape Eigentum
second_title: Aspose.Cells for Python via .NET API Referenzen
description:
type: docs
weight: 460
url: /de/aspose.cells.drawing/groupshape/height_in_shape/
is_root: false
---
##  height_in_shape Eigentum

Stellt den vertikalen Versatz der Form vom oberen Rand der übergeordneten Form in Einheiten von 1/4000 der Höhe der übergeordneten Form dar.

###  Bemerkungen

Gilt nur, wenn sich diese Form in der Gruppe oder im Diagramm befindet.

###  Beispiel

```python

if shape.is_in_group and shape.height_in_shape == 4000:
    shape.height_in_shape = 2000

```
###  Definition:
```python
@property
def height_in_shape(self):
    ...
@height_in_shape.setter
def height_in_shape(self, value):
    ...
```

###  Siehe auch
* Modul [`aspose.cells.drawing`](../../)
* Klasse [`GroupShape`](/cells/python-net/de/aspose.cells.drawing/groupshape)
