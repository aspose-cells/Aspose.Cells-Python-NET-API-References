---
title: TextBoxOptions صف
second_title: Aspose.Cells for Python via .NET API المراجع
description:
type: docs
weight: 80
url: /ar/aspose.cells.drawing.texts/textboxoptions/
is_root: false
---
##  TextBoxOptions صف
يمثل خيارات النص للشكل



يكشف النوع TextBoxOptions عن الأعضاء التاليين:

###  ملكيات
| ملكية| وصف|
| :- | :- |
| [shape_text_vertical_alignment](/cells/python-net/ar/aspose.cells.drawing.texts/textboxoptions/shape_text_vertical_alignment) | يتوافق مع "تنسيق الشكل - خيارات النص - مربع النص - المحاذاة الرأسية" في Excel.|
| [resize_to_fit_text](/cells/python-net/ar/aspose.cells.drawing.texts/textboxoptions/resize_to_fit_text) | يشير إلى ما إذا كان سيتم تغيير حجم الشكل ليتناسب مع النص|
| [shape_text_direction](/cells/python-net/ar/aspose.cells.drawing.texts/textboxoptions/shape_text_direction) | يحصل على اتجاه عرض النص أو يعينه داخل نص معين.<br/> يتوافق مع "تنسيق الشكل - خيارات النص - مربع النص - اتجاه النص" في Excel|
| [left_margin_pt](/cells/python-net/ar/aspose.cells.drawing.texts/textboxoptions/left_margin_pt) | يحصل على الهامش الأيسر ويضبطه بوحدة النقاط.|
| [right_margin_pt](/cells/python-net/ar/aspose.cells.drawing.texts/textboxoptions/right_margin_pt) | يحصل على الهامش الأيمن ويحدده بوحدة النقاط.|
| [top_margin_pt](/cells/python-net/ar/aspose.cells.drawing.texts/textboxoptions/top_margin_pt) | يحصل على الهامش العلوي ويحدده بوحدة النقاط.|
| [bottom_margin_pt](/cells/python-net/ar/aspose.cells.drawing.texts/textboxoptions/bottom_margin_pt) | إرجاع الهامش السفلي بوحدة النقاط|
| [allow_text_to_overflow](/cells/python-net/ar/aspose.cells.drawing.texts/textboxoptions/allow_text_to_overflow) | ما إذا كان يسمح للنص بتجاوز الشكل.|
| [wrap_text_in_shape](/cells/python-net/ar/aspose.cells.drawing.texts/textboxoptions/wrap_text_in_shape) | يحدد التفاف النص داخل الشكل.<br/> خطأ - لن يحدث التفاف على نص الجسم.<br/>صحيح - سيحدث الالتفاف على نص الجسم.|



###  مثال

```python
from aspose.cells import Workbook

# Instantiating a Workbook object
workbook = Workbook()
index = workbook.worksheets[0].text_boxes.add(0, 0, 350, 350)
shape = workbook.worksheets[0].text_boxes[index]
shape.text = "This is test."
# do your business
# Save the excel file.
workbook.save("exmaple.xlsx")

```

###  أنظر أيضا
* الوحدة [`aspose.cells.drawing.texts`](..)
