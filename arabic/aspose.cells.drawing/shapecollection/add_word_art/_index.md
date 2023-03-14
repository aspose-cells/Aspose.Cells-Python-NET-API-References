---
title: طريقة add_word_art
second_title: Aspose.Cells for Python via .NET API المراجع
description:
type: docs
weight: 350
url: /ar/aspose.cells.drawing/shapecollection/add_word_art/
is_root: false
---
##  add_word_art(style, text, upper_left_row, top, upper_left_column, left, height, width) {#PresetWordArtStyle-str-int-int-int-int-int-int}
يضيف WordArt المعين مسبقًا منذ Excel 2007.s


###  عائدات




```python
def add_word_art(self, style, text, upper_left_row, top, upper_left_column, left, height, width):
    ...
```


| معامل| يكتب| وصف|
| :- | :- | :- |
| style | [PresetWordArtStyle](/cells/python-net/ar/aspose.cells.drawing/presetwordartstyle) | نمط WordArt المعين مسبقًا.|
| text | str | النص.|
| upper_left_row | int | فهرس الصف العلوي الأيسر.|
| top | int | يمثل الإزاحة الرأسية للشكل من صفه الأيسر ، بوحدة البكسل.|
| upper_left_column | int | فهرس العمود الأيسر العلوي.|
| left | int |يمثل الإزاحة الأفقية للشكل من العمود الأيسر ، بوحدة البكسل.|
| height | int | يمثل ارتفاع الشكل بوحدة البكسل.|
| width | int | يمثل عرض الشكل بوحدة البكسل.|

###  مثال

```python
from aspose.cells.drawing import PresetWordArtStyle

# add a WordArt
wordArt2 = shapes.add_word_art(PresetWordArtStyle.WORD_ART_STYLE1, "WordArt", 3, 0, 3, 0, 50, 200)

```



###  أنظر أيضا
* وحدة [aspose.cells.drawing](../../)
* فئة [ShapeCollection](/cells/python-net/ar/aspose.cells.drawing/shapecollection)
