---
title: top_in_shape Eigentum
second_title: Aspose.Cells for Python via .NET API Referenzen
description:
type: docs
weight: 1090
url: /de/aspose.cells.drawing/shape/top_in_shape/
is_root: false
---
##  top_in_shape Eigentum

 Stellt den vertikalen Abstand der Form vom oberen Rand der übergeordneten Form dar.
in Einheiten von 1/4000 der Höhe der übergeordneten Form.

###  Bemerkungen

Gilt nur, wenn sich diese Form in der Gruppe oder im Diagramm befindet.

###  Beispiel

```python

if shape.is_in_group and shape.top_in_shape == 8000:
    shape.top_in_shape = 4000

```
###  Definition:
```python
@property
def top_in_shape(self):
    ...
@top_in_shape.setter
def top_in_shape(self, value):
    ...
```

###  Siehe auch
* Modul [`aspose.cells.drawing`](../../)
* Klasse [`Shape`](/cells/python-net/de/aspose.cells.drawing/shape)
