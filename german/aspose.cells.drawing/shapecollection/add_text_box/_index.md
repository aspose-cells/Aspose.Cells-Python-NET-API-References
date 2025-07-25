---
title: add_text_box Methode
second_title: Aspose.Cells for Python via .NET API Referenzen
description:
type: docs
weight: 340
url: /de/aspose.cells.drawing/shapecollection/add_text_box/
is_root: false
---
##  add_text_box(self, upper_left_row, top, upper_left_column, left, height, width) {#int-int-int-int-int-int}
Fügt dem Arbeitsblatt ein Textfeld hinzu.


###  Kehrt zurück

Ein [`TextBox`](/cells/python-net/de/aspose.cells.drawing/textbox)-Objekt.


```python

def add_text_box(self, upper_left_row, top, upper_left_column, left, height, width):
    ...
```


| Parameter| Typ| Beschreibung|
| :- | :- | :- |
| upper_left_row | int | Zeilenindex oben links.|
| top | int | Stellt den vertikalen Versatz des Textfelds von seiner obersten Zeile in Pixeleinheiten dar.|
| upper_left_column | int | Index der oberen linken Spalte.|
| left | int | Stellt den horizontalen Versatz des Textfelds von seiner linken Spalte in Pixeleinheiten dar.|
| height | int | Stellt die Höhe des Textfelds in Pixeln dar.|
| width | int | Stellt die Breite des Textfelds in Pixeln dar.|

###  Beispiel

```python

# add a TextBox
textBox = shapes.add_text_box(1, 0, 1, 0, 100, 50)

```



###  Siehe auch
* Modul [`aspose.cells.drawing`](../../)
* Klasse [`ShapeCollection`](/cells/python-net/de/aspose.cells.drawing/shapecollection)
* Klasse [`TextBox`](/cells/python-net/de/aspose.cells.drawing/textbox)
