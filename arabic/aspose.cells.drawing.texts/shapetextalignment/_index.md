---
title: ShapeTextAlignment صف
second_title: Aspose.Cells for Python via .NET API المراجع
description:
type: docs
weight: 70
url: /ar/aspose.cells.drawing.texts/shapetextalignment/
is_root: false
---
##  ShapeTextAlignment صف
يمثل إعداد محاذاة نص الشكل؛



يكشف النوع ShapeTextAlignment عن الأعضاء التاليين:

###  ملكيات
| ملكية| وصف|
| :- | :- |
| [is_text_wrapped](/cells/python-net/ar/aspose.cells.drawing.texts/shapetextalignment/is_text_wrapped) | يحصل على نوع النص المغلف للشكل الذي يحتوي على نص أو يعينه.|
| [rotate_text_with_shape](/cells/python-net/ar/aspose.cells.drawing.texts/shapetextalignment/rotate_text_with_shape) | يشير إلى ما إذا كان يتم تدوير النص مع الشكل.|
| [text_vertical_overflow](/cells/python-net/ar/aspose.cells.drawing.texts/shapetextalignment/text_vertical_overflow) | يحصل على نوع تجاوز النص العمودي لمربع النص ويقوم بتعيينه.|
| [text_horizontal_overflow](/cells/python-net/ar/aspose.cells.drawing.texts/shapetextalignment/text_horizontal_overflow) | يحصل على نوع تجاوز النص الأفقي لمربع النص ويقوم بتعيينه.|
| [rotation_angle](/cells/python-net/ar/aspose.cells.drawing.texts/shapetextalignment/rotation_angle) | يحصل على دوران الشكل ويحدده.|
| [text_vertical_type](/cells/python-net/ar/aspose.cells.drawing.texts/shapetextalignment/text_vertical_type) | يحصل على اتجاه النص ويحدده.|
| [is_locked_text](/cells/python-net/ar/aspose.cells.drawing.texts/shapetextalignment/is_locked_text) | يشير إلى ما إذا كان الشكل مقفلاً عند حماية ورقة العمل.|
| [auto_size](/cells/python-net/ar/aspose.cells.drawing.texts/shapetextalignment/auto_size) | يشير إلى ما إذا كان حجم الشكل يتم تعديله تلقائيًا وفقًا لمحتواه.|
| [text_shape_type](/cells/python-net/ar/aspose.cells.drawing.texts/shapetextalignment/text_shape_type) | يحصل على نوع تحويل النص ويقوم بتعيينه.|
| [top_margin_pt](/cells/python-net/ar/aspose.cells.drawing.texts/shapetextalignment/top_margin_pt) | إرجاع الهامش العلوي بوحدة النقاط|
| [bottom_margin_pt](/cells/python-net/ar/aspose.cells.drawing.texts/shapetextalignment/bottom_margin_pt) | إرجاع الهامش السفلي بوحدة النقاط|
| [left_margin_pt](/cells/python-net/ar/aspose.cells.drawing.texts/shapetextalignment/left_margin_pt) | إرجاع الهامش الأيسر بوحدة النقاط|
| [right_margin_pt](/cells/python-net/ar/aspose.cells.drawing.texts/shapetextalignment/right_margin_pt) | إرجاع الهامش الأيمن بوحدة النقاط|
| [is_auto_margin](/cells/python-net/ar/aspose.cells.drawing.texts/shapetextalignment/is_auto_margin) |يشير إلى ما إذا كان هامش إطار النص تلقائياً.|
| [number_of_columns](/cells/python-net/ar/aspose.cells.drawing.texts/shapetextalignment/number_of_columns) | يحصل على عدد أعمدة النص في المستطيل المحيط ويحدده.|



###  مثال

```python
from aspose.cells import Workbook

# Instantiating a Workbook object
workbook = Workbook()
shape = workbook.worksheets[0].shapes.add_rectangle(1, 0, 1, 0, 50, 100)
shapeTextAlignment = shape.text_body.text_alignment

```

###  أنظر أيضا
* الوحدة [`aspose.cells.drawing.texts`](..)
