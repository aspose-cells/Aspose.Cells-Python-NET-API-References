---
title: add_list_box Methode
second_title: Aspose.Cells for Python via .NET API Referenzen
description:
type: docs
weight: 190
url: /de/aspose.cells.drawing/shapecollection/add_list_box/
is_root: false
---
##  add_list_box(self, upper_left_row, top, upper_left_column, left, height, width) {#int-int-int-int-int-int}
Fügt dem Arbeitsblatt eine ListBox hinzu.


###  Kehrt zurück

Ein ListBox-Objekt.


```python

def add_list_box(self, upper_left_row, top, upper_left_column, left, height, width):
    ...
```


| Parameter| Typ| Beschreibung|
| :- | :- | :- |
| upper_left_row | int | Zeilenindex oben links.|
| top | int | Stellt den vertikalen Versatz der ListBox von ihrer linken Zeile in Pixeleinheiten dar.|
| upper_left_column | int | Index der oberen linken Spalte.|
| left | int | Stellt den horizontalen Versatz der ListBox von ihrer linken Spalte in Pixeleinheiten dar.|
| height | int | Stellt die Höhe der ListBox in Pixeln dar.|
| width | int | Stellt die Breite der ListBox in Pixeln dar.|

###  Beispiel

```python

# add a list box
listBox = shapes.add_list_box(1, 0, 1, 0, 100, 50)

```



###  Siehe auch
* Modul [`aspose.cells.drawing`](../../)
* Klasse [`ShapeCollection`](/cells/python-net/de/aspose.cells.drawing/shapecollection)
