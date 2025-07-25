---
title: add_radio_button Methode
second_title: Aspose.Cells for Python via .NET API Referenzen
description:
type: docs
weight: 250
url: /de/aspose.cells.drawing/shapecollection/add_radio_button/
is_root: false
---
##  add_radio_button(self, upper_left_row, top, upper_left_column, left, height, width) {#int-int-int-int-int-int}
Fügt dem Arbeitsblatt einen RadioButton hinzu.


###  Kehrt zurück

Ein RadioButton-Objekt.


```python

def add_radio_button(self, upper_left_row, top, upper_left_column, left, height, width):
    ...
```


| Parameter| Typ| Beschreibung|
| :- | :- | :- |
| upper_left_row | int | Zeilenindex oben links.|
| top | int | Stellt den vertikalen Versatz des RadioButtons von seiner linken Zeile in Pixeleinheiten dar.|
| upper_left_column | int | Index der oberen linken Spalte.|
| left | int | Stellt den horizontalen Versatz des RadioButtons von seiner linken Spalte in Pixeleinheiten dar.|
| height | int | Stellt die Höhe des RadioButtons in Pixeln dar.|
| width | int | Stellt die Breite des RadioButtons in Pixeln dar.|

###  Beispiel

```python

# add a radio button
radioButton = shapes.add_radio_button(1, 0, 1, 0, 100, 50)

```



###  Siehe auch
* Modul [`aspose.cells.drawing`](../../)
* Klasse [`ShapeCollection`](/cells/python-net/de/aspose.cells.drawing/shapecollection)
