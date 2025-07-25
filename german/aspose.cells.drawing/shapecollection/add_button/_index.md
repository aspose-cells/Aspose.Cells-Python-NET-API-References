---
title: add_button Methode
second_title: Aspose.Cells for Python via .NET API Referenzen
description:
type: docs
weight: 60
url: /de/aspose.cells.drawing/shapecollection/add_button/
is_root: false
---
##  add_button(self, upper_left_row, top, upper_left_column, left, height, width) {#int-int-int-int-int-int}
Fügt dem Arbeitsblatt eine Schaltfläche hinzu.


###  Kehrt zurück

Ein Button-Objekt.


```python

def add_button(self, upper_left_row, top, upper_left_column, left, height, width):
    ...
```


| Parameter| Typ| Beschreibung|
| :- | :- | :- |
| upper_left_row | int | Zeilenindex oben links.|
| top | int | Stellt den vertikalen Versatz der Schaltfläche von ihrer linken Reihe in Pixeleinheiten dar.|
| upper_left_column | int | Index der oberen linken Spalte.|
| left | int |Stellt den horizontalen Versatz der Schaltfläche von ihrer linken Spalte in Pixeleinheiten dar.|
| height | int | Stellt die Höhe der Schaltfläche in Pixeln dar.|
| width | int | Stellt die Breite der Schaltfläche in Pixeln dar.|

###  Beispiel

```python

# add a button
button = shapes.add_button(1, 0, 1, 0, 100, 50)

```



###  Siehe auch
* Modul [`aspose.cells.drawing`](../../)
* Klasse [`ShapeCollection`](/cells/python-net/de/aspose.cells.drawing/shapecollection)
