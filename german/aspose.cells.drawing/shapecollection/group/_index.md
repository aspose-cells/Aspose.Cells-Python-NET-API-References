---
title: group Methode
second_title: Aspose.Cells for Python via .NET API Referenzen
description:
type: docs
weight: 460
url: /de/aspose.cells.drawing/shapecollection/group/
is_root: false
---
##  group(self, group_items) {#list}
Gruppieren Sie die Formen.


###  Kehrt zurück

Geben Sie die Form group zurück.


```python

def group(self, group_items):
    ...
```


| Parameter| Typ| Beschreibung|
| :- | :- | :- |
| group_items | list | die Gruppenelemente.|
###  Bemerkungen

Die Form in den Gruppenelementen sollte nicht gruppiert werden.
Die Form muss in dieser Formensammlung enthalten sein.
###  Beispiel

```python

# add first shape
shapes.add_rectangle(2, 0, 2, 0, 50, 50)
# add second shape
shapes.add_rectangle(6, 0, 2, 0, 30, 30)
shapesArr = [shapes[0], shapes[1]]
groupShape = shapes.group(shapesArr)

```



###  Siehe auch
* Modul [`aspose.cells.drawing`](../../)
* Klasse [`ShapeCollection`](/cells/python-net/de/aspose.cells.drawing/shapecollection)
