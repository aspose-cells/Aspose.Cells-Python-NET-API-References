---
title: add_group_box Methode
second_title: Aspose.Cells for Python via .NET API Referenzen
description:
type: docs
weight: 130
url: /de/aspose.cells.drawing/shapecollection/add_group_box/
is_root: false
---
##  add_group_box(self, upper_left_row, top, upper_left_column, left, height, width) {#int-int-int-int-int-int}
Fügt dem Arbeitsblatt eine GroupBox hinzu.


###  Kehrt zurück

Ein GroupBox-Objekt.


```python

def add_group_box(self, upper_left_row, top, upper_left_column, left, height, width):
    ...
```


| Parameter| Typ| Beschreibung|
| :- | :- | :- |
| upper_left_row | int | Zeilenindex oben links.|
| top | int | Stellt den vertikalen Versatz der GroupBox von ihrer linken Zeile in Pixeleinheiten dar.|
| upper_left_column | int | Index der oberen linken Spalte.|
| left | int | Stellt den horizontalen Versatz der GroupBox von ihrer linken Spalte in Pixeleinheiten dar.|
| height | int | Stellt die Höhe der GroupBox in Pixeln dar.|
| width | int | Stellt die Breite der GroupBox in Pixeln dar.|

###  Beispiel

```python

# add a group box
groupBox = shapes.add_group_box(1, 0, 1, 0, 100, 50)

```



###  Siehe auch
* Modul [`aspose.cells.drawing`](../../)
* Klasse [`ShapeCollection`](/cells/python-net/de/aspose.cells.drawing/shapecollection)
