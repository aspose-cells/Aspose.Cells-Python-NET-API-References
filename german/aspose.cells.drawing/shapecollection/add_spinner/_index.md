---
title: add_spinner Methode
second_title: Aspose.Cells for Python via .NET API Referenzen
description:
type: docs
weight: 320
url: /de/aspose.cells.drawing/shapecollection/add_spinner/
is_root: false
---
##  add_spinner(self, upper_left_row, top, upper_left_column, left, height, width) {#int-int-int-int-int-int}
Fügt dem Arbeitsblatt einen Spinner hinzu.


###  Kehrt zurück

Ein Spinner-Objekt.


```python

def add_spinner(self, upper_left_row, top, upper_left_column, left, height, width):
    ...
```


| Parameter| Typ| Beschreibung|
| :- | :- | :- |
| upper_left_row | int | Zeilenindex oben links.|
| top | int |Stellt den vertikalen Versatz des Spinners von seiner linken Reihe in Pixeleinheiten dar.|
| upper_left_column | int | Index der oberen linken Spalte.|
| left | int | Stellt den horizontalen Versatz des Spinners von seiner linken Spalte in Pixeleinheiten dar.|
| height | int | Stellt die Höhe des Spinners in Pixeleinheiten dar.|
| width | int | Stellt die Breite des Spinners in Pixeleinheiten dar.|

###  Beispiel

```python

# add a spinner
spinner = shapes.add_spinner(1, 0, 1, 0, 100, 50)

```



###  Siehe auch
* Modul [`aspose.cells.drawing`](../../)
* Klasse [`ShapeCollection`](/cells/python-net/de/aspose.cells.drawing/shapecollection)
