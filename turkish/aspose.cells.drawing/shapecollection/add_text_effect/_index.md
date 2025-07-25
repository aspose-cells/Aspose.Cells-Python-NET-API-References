---
title: add_text_effect yöntemi
second_title: Aspose.Cells for Python via .NET API Referanslar
description:
type: docs
weight: 360
url: /tr/aspose.cells.drawing/shapecollection/add_text_effect/
is_root: false
---
##  add_text_effect(self, effect, text, font_name, size, font_bold, font_italic, upper_left_row, top, upper_left_column, left, height, width) {#aspose.cells.drawing.MsoPresetTextEffect-str-str-int-bool-bool-int-int-int-int-int-int}
Bir WordArt nesnesi ekler.


###  İadeler

Yeni WordArt nesnesini temsil eden bir Shape nesnesi döndürür.


```python

def add_text_effect(self, effect, text, font_name, size, font_bold, font_italic, upper_left_row, top, upper_left_column, left, height, width):
    ...
```


| Parametre| Tip| Tanım|
| :- | :- | :- |
| effect | [`MsoPresetTextEffect`](/cells/python-net/tr/aspose.cells.drawing/msopresettexteffect) | Mso ön ayarlı metin efekti türü.|
| text | str | WordArt metni.|
| font_name | str | Yazı tipi adı.|
| size | int | Yazı tipi boyutu|
| font_bold | bool | Yazı tipinin kalın olup olmadığını gösterir.|
| font_italic | bool | Yazı tipinin italik olup olmadığını belirtir.|
| upper_left_row | int | Sol üst sıra dizini.|
| top | int | Şeklin sol satırından dikey uzaklığını piksel cinsinden temsil eder.|
| upper_left_column | int | Sol üst sütun dizini.|
| left | int |Şeklin sol sütunundan yatay olarak uzaklığını piksel cinsinden gösterir.|
| height | int | Şeklin yüksekliğini piksel cinsinden temsil eder.|
| width | int | Şeklin genişliğini piksel cinsinden temsil eder.|

###  Örnek

```python
from aspose.cells.drawing import MsoPresetTextEffect

# add a WordArt
wordArt1 = shapes.add_text_effect(MsoPresetTextEffect.TEXT_EFFECT10, "WordArt", "arial", 18, False, False, 3, 0, 3, 0, 200, 50)

```



###  Ayrıca bakınız
* modül [`aspose.cells.drawing`](../../)
* sınıf [`ShapeCollection`](/cells/python-net/tr/aspose.cells.drawing/shapecollection)
