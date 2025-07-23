---
title: add_word_art yöntemi
second_title: Aspose.Cells for Python via .NET API Referanslar
description:
type: docs
weight: 380
url: /tr/aspose.cells.drawing/shapecollection/add_word_art/
is_root: false
---
##  add_word_art(self, style, text, upper_left_row, top, upper_left_column, left, height, width) {#aspose.cells.drawing.PresetWordArtStyle-str-int-int-int-int-int-int}
Excel 2007'den bu yana önceden ayarlanmış WordArt ekler


###  İadeler




```python

def add_word_art(self, style, text, upper_left_row, top, upper_left_column, left, height, width):
    ...
```


| Parametre| Tip| Tanım|
| :- | :- | :- |
| style | [`PresetWordArtStyle`](/cells/python-net/tr/aspose.cells.drawing/presetwordartstyle) | Önceden ayarlanmış WordArt Stili.|
| text | str | Metin.|
| upper_left_row | int | Sol üst sıra dizini.|
| top | int | Şeklin sol satırından dikey uzaklığını piksel cinsinden temsil eder.|
| upper_left_column | int | Sol üst sütun dizini.|
| left | int |Şeklin sol sütunundan yatay olarak uzaklığını piksel cinsinden gösterir.|
| height | int | Şeklin yüksekliğini piksel cinsinden temsil eder.|
| width | int | Şeklin genişliğini piksel cinsinden temsil eder.|

###  Örnek

```python
from aspose.cells.drawing import PresetWordArtStyle

# add a WordArt
wordArt2 = shapes.add_word_art(PresetWordArtStyle.WORD_ART_STYLE1, "WordArt", 3, 0, 3, 0, 50, 200)

```



###  Ayrıca bakınız
* modül [`aspose.cells.drawing`](../../)
* sınıf [`ShapeCollection`](/cells/python-net/tr/aspose.cells.drawing/shapecollection)
