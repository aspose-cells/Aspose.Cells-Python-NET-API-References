---
title: add_text_effect metod
second_title: Aspose.Cells for Python via .NET API Referenser
description:
type: docs
weight: 360
url: /sv/aspose.cells.drawing/shapecollection/add_text_effect/
is_root: false
---
##  add_text_effect(self, effect, text, font_name, size, font_bold, font_italic, upper_left_row, top, upper_left_column, left, height, width) {#aspose.cells.drawing.MsoPresetTextEffect-str-str-int-bool-bool-int-int-int-int-int-int}
Infogar ett WordArt-objekt.


###  Returnerar

Returnerar ett Shape-objekt som representerar det nya WordArt-objektet.


```python

def add_text_effect(self, effect, text, font_name, size, font_bold, font_italic, upper_left_row, top, upper_left_column, left, height, width):
    ...
```


| Parameter| Typ| Beskrivning|
| :- | :- | :- |
| effect | [`MsoPresetTextEffect`](/cells/python-net/sv/aspose.cells.drawing/msopresettexteffect) | Den förinställda texteffekttypen för mso.|
| text | str | WordArt-texten.|
| font_name | str | Typsnittets namn.|
| size | int | Teckenstorleken|
| font_bold | bool | Anger om teckensnittet är fetstilt.|
| font_italic | bool | Anger om teckensnittet är kursivt.|
| upper_left_row | int | Index för övre vänstra raden.|
| top | int | Representerar formens vertikala förskjutning från dess vänstra rad, i pixelenhet.|
| upper_left_column | int | Index i övre vänstra kolumnen.|
| left | int |Representerar den horisontella förskjutningen av formen från dess vänstra kolumn, i pixelenhet.|
| height | int | Representerar formens höjd, i pixelenhet.|
| width | int | Representerar formens bredd, i pixelenhet.|

###  Exempel

```python
from aspose.cells.drawing import MsoPresetTextEffect

# add a WordArt
wordArt1 = shapes.add_text_effect(MsoPresetTextEffect.TEXT_EFFECT10, "WordArt", "arial", 18, False, False, 3, 0, 3, 0, 200, 50)

```



###  Se även
* modul [`aspose.cells.drawing`](../../)
* klass [`ShapeCollection`](/cells/python-net/sv/aspose.cells.drawing/shapecollection)
