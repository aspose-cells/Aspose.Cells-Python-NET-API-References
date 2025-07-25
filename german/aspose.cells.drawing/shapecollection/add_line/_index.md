---
title: add_line Methode
second_title: Aspose.Cells for Python via .NET API Referenzen
description:
type: docs
weight: 170
url: /de/aspose.cells.drawing/shapecollection/add_line/
is_root: false
---
##  add_line(self, upper_left_row, top, upper_left_column, left, height, width) {#int-int-int-int-int-int}
Fügt dem Arbeitsblatt eine Linienform hinzu.


###  Kehrt zurück

Ein LineShape-Objekt.


```python

def add_line(self, upper_left_row, top, upper_left_column, left, height, width):
    ...
```


| Parameter| Typ| Beschreibung|
| :- | :- | :- |
| upper_left_row | int | Zeilenindex oben links.|
| top | int | Stellt den vertikalen Versatz der Linienform von ihrer linken Zeile in Pixeleinheiten dar.|
| upper_left_column | int | Index der oberen linken Spalte.|
| left | int | Stellt den horizontalen Versatz der Linienform von ihrer linken Spalte in Pixeleinheiten dar.|
| height | int | Stellt die Höhe der Linienform in Pixeln dar.|
| width | int |Stellt die Breite der Linienform in Pixeln dar.|

###  Beispiel

```python

#  add a line object
lineShape = shapes.add_line(1, 0, 1, 0, 100, 50)

```



###  Siehe auch
* Modul [`aspose.cells.drawing`](../../)
* Klasse [`ShapeCollection`](/cells/python-net/de/aspose.cells.drawing/shapecollection)
