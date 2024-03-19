---
title: width_in_shape Eigentum
second_title: Aspose.Cells for Python via .NET API Referenzen
description:
type: docs
weight: 1240
url: /de/aspose.cells.drawing/lineshape/width_in_shape/
is_root: false
---
##  width_in_shape Eigentum

Stellt die Breite der Form in Einheiten von 1/4000 der übergeordneten Form dar.

###  Bemerkungen

Gilt nur, wenn diese Form in der Gruppe oder im Diagramm enthalten ist.

###  Beispiel

```python

if shape.is_in_group and shape.width_in_shape == 2000:
    shape.width_in_shape = 4000

```
###  Definition:
```python
@property
def width_in_shape(self):
    ...
@width_in_shape.setter
def width_in_shape(self, value):
    ...
```

###  Siehe auch
* Modul [`aspose.cells.drawing`](../../)
* Klasse [`LineShape`](/cells/python-net/de/aspose.cells.drawing/lineshape)
