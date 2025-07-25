---
title: add_oval Methode
second_title: Aspose.Cells for Python via .NET API Referenzen
description:
type: docs
weight: 220
url: /de/aspose.cells.drawing/shapecollection/add_oval/
is_root: false
---
##  add_oval(self, upper_left_row, top, upper_left_column, left, height, width) {#int-int-int-int-int-int}
Fügt dem Arbeitsblatt ein Oval hinzu.


###  Kehrt zurück

Ein ovales Objekt.


```python

def add_oval(self, upper_left_row, top, upper_left_column, left, height, width):
    ...
```


| Parameter| Typ| Beschreibung|
| :- | :- | :- |
| upper_left_row | int | Zeilenindex oben links.|
| top | int | Stellt den vertikalen Versatz des Ovals von seiner linken Reihe in Pixeleinheiten dar.|
| upper_left_column | int | Index der oberen linken Spalte.|
| left | int | Stellt den horizontalen Versatz des Ovals von seiner linken Spalte in Pixeleinheiten dar.|
| height | int | Stellt die Höhe des Ovals in Pixeleinheiten dar.|
| width | int | Stellt die Breite des Ovals in Pixeleinheiten dar.|

###  Beispiel

```python

# add a oval
oval = shapes.add_oval(1, 0, 1, 0, 50, 50)

```



###  Siehe auch
* Modul [`aspose.cells.drawing`](../../)
* Klasse [`ShapeCollection`](/cells/python-net/de/aspose.cells.drawing/shapecollection)
