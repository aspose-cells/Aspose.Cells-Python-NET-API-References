---
title: add_label Methode
second_title: Aspose.Cells for Python via .NET API Referenzen
description:
type: docs
weight: 150
url: /de/aspose.cells.drawing/shapecollection/add_label/
is_root: false
---
##  add_label(self, upper_left_row, top, upper_left_column, left, height, width) {#int-int-int-int-int-int}
Fügt dem Arbeitsblatt eine Beschriftung hinzu.


###  Kehrt zurück

Ein Label-Objekt.


```python

def add_label(self, upper_left_row, top, upper_left_column, left, height, width):
    ...
```


| Parameter| Typ| Beschreibung|
| :- | :- | :- |
| upper_left_row | int | Zeilenindex oben links.|
| top | int |Stellt den vertikalen Versatz des Etiketts von seiner linken Zeile in Pixeleinheiten dar.|
| upper_left_column | int | Index der oberen linken Spalte.|
| left | int | Stellt den horizontalen Versatz des Etiketts von seiner linken Spalte in Pixeleinheiten dar.|
| height | int | Stellt die Höhe des Etiketts in Pixeln dar.|
| width | int | Stellt die Breite des Etiketts in Pixeln dar.|

###  Beispiel

```python

# add a label
label = shapes.add_label(1, 0, 1, 0, 100, 50)

```



###  Siehe auch
* Modul [`aspose.cells.drawing`](../../)
* Klasse [`ShapeCollection`](/cells/python-net/de/aspose.cells.drawing/shapecollection)
