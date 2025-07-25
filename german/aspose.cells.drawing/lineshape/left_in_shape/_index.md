---
title: left_in_shape Eigentum
second_title: Aspose.Cells for Python via .NET API Referenzen
description:
type: docs
weight: 760
url: /de/aspose.cells.drawing/lineshape/left_in_shape/
is_root: false
---
##  left_in_shape Eigentum

 Stellt den horizontalen Abstand der Form vom linken Rand der übergeordneten Form dar.
in Einheiten von 1/4000 der Breite der übergeordneten Form.

###  Bemerkungen

Gilt nur, wenn sich diese Form in der Gruppe oder im Diagramm befindet.

###  Beispiel

```python

if shape.is_in_group and shape.left_in_shape == 2000:
    shape.left_in_shape = 4000

```
###  Definition:
```python
@property
def left_in_shape(self):
    ...
@left_in_shape.setter
def left_in_shape(self, value):
    ...
```

###  Siehe auch
* Modul [`aspose.cells.drawing`](../../)
* Klasse [`LineShape`](/cells/python-net/de/aspose.cells.drawing/lineshape)
