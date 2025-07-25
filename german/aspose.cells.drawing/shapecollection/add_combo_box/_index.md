---
title: add_combo_box Methode
second_title: Aspose.Cells for Python via .NET API Referenzen
description:
type: docs
weight: 80
url: /de/aspose.cells.drawing/shapecollection/add_combo_box/
is_root: false
---
##  add_combo_box(self, upper_left_row, top, upper_left_column, left, height, width) {#int-int-int-int-int-int}
Fügt dem Arbeitsblatt eine ComboBox hinzu.


###  Kehrt zurück

Ein ComboBox-Objekt.


```python

def add_combo_box(self, upper_left_row, top, upper_left_column, left, height, width):
    ...
```


| Parameter| Typ| Beschreibung|
| :- | :- | :- |
| upper_left_row | int | Zeilenindex oben links.|
| top | int | Stellt den vertikalen Versatz der ComboBox von ihrer linken Zeile in Pixeleinheiten dar.|
| upper_left_column | int | Index der oberen linken Spalte.|
| left | int | Stellt den horizontalen Versatz der ComboBox von ihrer linken Spalte in Pixeleinheiten dar.|
| height | int | Stellt die Höhe der ComboBox in Pixeln dar.|
| width | int | Stellt die Breite der ComboBox in Pixeln dar.|

###  Beispiel

```python

# add a combo box
comboBox = shapes.add_combo_box(1, 0, 1, 0, 100, 50)

```



###  Siehe auch
* Modul [`aspose.cells.drawing`](../../)
* Klasse [`ShapeCollection`](/cells/python-net/de/aspose.cells.drawing/shapecollection)
