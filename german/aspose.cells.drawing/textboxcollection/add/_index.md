---
title: add Methode
second_title: Aspose.Cells for Python via .NET API Referenzen
description:
type: docs
weight: 20
url: /de/aspose.cells.drawing/textboxcollection/add/
is_root: false
---
##  add(self, upper_left_row, upper_left_column, height, width) {#int-int-int-int}
Fügt der Sammlung ein Textfeld hinzu.


###  Kehrt zurück

[`TextBox`](/cells/python-net/de/aspose.cells.drawing/textbox) Objektindex.


```python

def add(self, upper_left_row, upper_left_column, height, width):
    ...
```


| Parameter| Typ| Beschreibung|
| :- | :- | :- |
| upper_left_row | int | Zeilenindex oben links.|
| upper_left_column | int | Index der oberen linken Spalte.|
| height | int | Höhe des Textfelds in Pixeln.|
| width | int | Breite des Textfelds in Pixeln.|

###  Beispiel

```python

# add a TextBox
index2 = textBoxCollection.add(1, 1, 50, 100)

```



###  Siehe auch
* Modul [`aspose.cells.drawing`](../../)
* Klasse [`TextBox`](/cells/python-net/de/aspose.cells.drawing/textbox)
* Klasse [`TextBoxCollection`](/cells/python-net/de/aspose.cells.drawing/textboxcollection)
