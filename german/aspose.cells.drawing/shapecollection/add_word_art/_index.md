---
title: add_word_art Methode
second_title: Aspose.Cells for Python via .NET API Referenzen
description:
type: docs
weight: 380
url: /de/aspose.cells.drawing/shapecollection/add_word_art/
is_root: false
---
##  add_word_art(self, style, text, upper_left_row, top, upper_left_column, left, height, width) {#aspose.cells.drawing.PresetWordArtStyle-str-int-int-int-int-int-int}
Fügt seit Excel 2007 voreingestellte WordArt hinzu.


###  Kehrt zurück




```python

def add_word_art(self, style, text, upper_left_row, top, upper_left_column, left, height, width):
    ...
```


| Parameter| Typ| Beschreibung|
| :- | :- | :- |
| style | [`PresetWordArtStyle`](/cells/python-net/de/aspose.cells.drawing/presetwordartstyle) | Der voreingestellte WordArt-Stil.|
| text | str | Der Text.|
| upper_left_row | int | Zeilenindex oben links.|
| top | int | Stellt den vertikalen Versatz der Form von ihrer linken Reihe in Pixeleinheiten dar.|
| upper_left_column | int | Index der oberen linken Spalte.|
| left | int |Stellt den horizontalen Versatz der Form von ihrer linken Spalte in Pixeleinheiten dar.|
| height | int | Stellt die Höhe der Form in Pixeleinheiten dar.|
| width | int | Stellt die Breite der Form in Pixeleinheiten dar.|

###  Beispiel

```python
from aspose.cells.drawing import PresetWordArtStyle

# add a WordArt
wordArt2 = shapes.add_word_art(PresetWordArtStyle.WORD_ART_STYLE1, "WordArt", 3, 0, 3, 0, 50, 200)

```



###  Siehe auch
* Modul [`aspose.cells.drawing`](../../)
* Klasse [`ShapeCollection`](/cells/python-net/de/aspose.cells.drawing/shapecollection)
