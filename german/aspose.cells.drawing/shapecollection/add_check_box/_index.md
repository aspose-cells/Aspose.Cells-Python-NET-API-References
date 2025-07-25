---
title: add_check_box Methode
second_title: Aspose.Cells for Python via .NET API Referenzen
description:
type: docs
weight: 70
url: /de/aspose.cells.drawing/shapecollection/add_check_box/
is_root: false
---
##  add_check_box(self, upper_left_row, top, upper_left_column, left, height, width) {#int-int-int-int-int-int}
Fügt dem Arbeitsblatt ein Kontrollkästchen hinzu.


###  Kehrt zurück

Der neue CheckBox-Objektindex.


```python

def add_check_box(self, upper_left_row, top, upper_left_column, left, height, width):
    ...
```


| Parameter| Typ| Beschreibung|
| :- | :- | :- |
| upper_left_row | int | Zeilenindex oben links.|
| top | int | Stellt den vertikalen Versatz des Kontrollkästchens von seiner obersten Zeile in Pixeleinheiten dar.|
| upper_left_column | int | Index der oberen linken Spalte.|
| left | int | Stellt den horizontalen Versatz des Textfelds von seiner linken Spalte in Pixeleinheiten dar.|
| height | int | Höhe des Textfelds in Pixeln.|
| width | int | Breite des Textfelds in Pixeln.|

###  Beispiel

```python

# add a CheckBox
checkBox = shapes.add_check_box(1, 0, 1, 0, 100, 50)

```



###  Siehe auch
* Modul [`aspose.cells.drawing`](../../)
* Klasse [`ShapeCollection`](/cells/python-net/de/aspose.cells.drawing/shapecollection)
