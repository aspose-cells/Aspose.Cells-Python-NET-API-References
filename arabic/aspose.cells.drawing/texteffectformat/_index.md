---
title: TextEffectFormat صف
second_title: Aspose.Cells for Python via .NET API المراجع
description:
type: docs
weight: 680
url: /ar/aspose.cells.drawing/texteffectformat/
is_root: false
---
##  TextEffectFormat صف
يحتوي على الخصائص والأساليب التي تنطبق على كائنات WordArt.



يكشف النوع TextEffectFormat عن الأعضاء التاليين:

###  ملكيات
| ملكية| وصف|
| :- | :- |
| [text](/cells/python-net/ar/aspose.cells.drawing/texteffectformat/text) | النص في WordArt.|
| [font_name](/cells/python-net/ar/aspose.cells.drawing/texteffectformat/font_name) | اسم الخط المستخدم في WordArt.|
| [font_bold](/cells/python-net/ar/aspose.cells.drawing/texteffectformat/font_bold) | يشير إلى ما إذا كان الخط غامقًا.|
| [font_italic](/cells/python-net/ar/aspose.cells.drawing/texteffectformat/font_italic) | يشير إلى ما إذا كان الخط مائلًا.|
| [rotated_chars](/cells/python-net/ar/aspose.cells.drawing/texteffectformat/rotated_chars) | إذا كانت هذه القيمة صحيحة، فسيتم تدوير الأحرف في WordArt المحدد بمقدار 90 درجة بالنسبة لشكل حدود WordArt.|
| [font_size](/cells/python-net/ar/aspose.cells.drawing/texteffectformat/font_size) | حجم الخط (بالنقاط) المستخدم في WordArt.|
| [preset_shape](/cells/python-net/ar/aspose.cells.drawing/texteffectformat/preset_shape) | يحصل على نوع الشكل المحدد مسبقًا ويقوم بتعيينه.|


###  طُرق
| طريقة| وصف|
| :- | :- |
| [`set_text_effect(self, effect)`](/cells/python-net/ar/aspose.cells.drawing/texteffectformat/set_text_effect/#aspose.cells.drawing.msopresettexteffect) | تعيين تأثير النص المحدد مسبقًا.|



###  مثال

```python
from aspose.cells import Workbook
from aspose.cells.drawing import MsoPresetTextEffect

# Instantiating a Workbook object
workbook = Workbook()
shapes = workbook.worksheets[0].shapes
shapes.add_text_effect(MsoPresetTextEffect.TEXT_EFFECT1, "Aspose", "Arial", 30, False, False, 0, 0, 0, 0, 100, 200)
textEffectFormat = shapes[0].text_effect
textEffectFormat.set_text_effect(MsoPresetTextEffect.TEXT_EFFECT10)
workbook.save("Book1.xls")

```

###  أنظر أيضا
* الوحدة [`aspose.cells.drawing`](..)
