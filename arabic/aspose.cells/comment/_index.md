---
title: Comment صف
second_title: Aspose.Cells for Python via .NET API المراجع
description:
type: docs
weight: 260
url: /ar/aspose.cells/comment/
is_root: false
---
##  Comment صف
يقوم بتغليف الكائن الذي يمثل تعليق الخلية.



يكشف النوع Comment عن الأعضاء التاليين:

###  ملكيات
| ملكية| وصف|
| :- | :- |
| [author](/cells/python-net/ar/aspose.cells/comment/author) | يحصل ويحدد اسم مؤلف التعليق الأصلي|
| [comment_shape](/cells/python-net/ar/aspose.cells/comment/comment_shape) | احصل على كائن الشكل الذي يمثل الشكل المرفق بالتعليق المحدد.|
| [row](/cells/python-net/ar/aspose.cells/comment/row) | يحصل على مؤشر الصف للتعليق.|
| [column](/cells/python-net/ar/aspose.cells/comment/column) | يحصل على فهرس العمود للتعليق.|
| [is_threaded_comment](/cells/python-net/ar/aspose.cells/comment/is_threaded_comment) | يشير إلى ما إذا كان هذا التعليق تعليقًا مترابطًا.|
| [threaded_comments](/cells/python-net/ar/aspose.cells/comment/threaded_comments) | يحصل على قائمة التعليقات المترابطة؛|
| [note](/cells/python-net/ar/aspose.cells/comment/note) | يمثل محتوى التعليق.|
| [html_note](/cells/python-net/ar/aspose.cells/comment/html_note) | يحصل على سلسلة HTML التي تحتوي على البيانات وبعض التنسيقات في هذا التعليق ويقوم بتعيينها.|
| [font](/cells/python-net/ar/aspose.cells/comment/font) | يحصل على خط التعليق.|
| [is_visible](/cells/python-net/ar/aspose.cells/comment/is_visible) | يمثل ما إذا كان التعليق مرئيًا أم لا.|
| [text_orientation_type](/cells/python-net/ar/aspose.cells/comment/text_orientation_type) | يحصل على نوع اتجاه النص للتعليق ويقوم بتعيينه.|
| [text_horizontal_alignment](/cells/python-net/ar/aspose.cells/comment/text_horizontal_alignment) | يحصل على نوع محاذاة النص الأفقي للتعليق ويقوم بتعيينه.|
| [text_vertical_alignment](/cells/python-net/ar/aspose.cells/comment/text_vertical_alignment) | يحصل على نوع المحاذاة الرأسية للنص الخاص بالتعليق ويقوم بتعيينه.|
| [auto_size](/cells/python-net/ar/aspose.cells/comment/auto_size) | يشير إلى ما إذا كان حجم التعليق يتم تعديله تلقائيًا وفقًا لمحتواه.<br/>ملاحظة: في بعض الحالات الخاصة (مثل بيئة ماك)، قد لا يُفعّل هذا الإعداد. إذا لم يُفعّل، يُرجى استبداله بـ FitToTextSize().|
| [height_cm](/cells/python-net/ar/aspose.cells/comment/height_cm) | يمثل ارتفاع التعليق بوحدة السنتيمتر.|
| [width_cm](/cells/python-net/ar/aspose.cells/comment/width_cm) | يمثل عرض التعليق بوحدة السنتيمتر.|
| [width](/cells/python-net/ar/aspose.cells/comment/width) | يمثل عرض التعليق بوحدة البكسل.|
| [height](/cells/python-net/ar/aspose.cells/comment/height) | يمثل ارتفاع التعليق بوحدة البكسل.|
| [width_inch](/cells/python-net/ar/aspose.cells/comment/width_inch) | يمثل عرض التعليق بوحدة البوصة.|
| [height_inch](/cells/python-net/ar/aspose.cells/comment/height_inch) | يمثل ارتفاع التعليق بوحدة البوصة.|


###  طُرق
| طريقة| وصف|
| :- | :- |
| [`format_characters(self, start_index, length, font, flag)`](/cells/python-net/ar/aspose.cells/comment/format_characters/#int-int-aspose.cells.font-aspose.cells.styleflag) | تنسيق بعض الأحرف باستخدام إعدادات الخط.|
| [`characters(self, start_index, length)`](/cells/python-net/ar/aspose.cells/comment/characters/#int-int) | يقوم بإرجاع كائن الأحرف الذي يمثل نطاقًا من الأحرف داخل نص التعليق.|
| [`get_characters(self)`](/cells/python-net/ar/aspose.cells/comment/get_characters/#) | إرجاع جميع كائنات الأحرف<br/> وهو ما يمثل مجموعة من الأحرف داخل نص التعليق.|
| [`get_rich_formattings(self)`](/cells/python-net/ar/aspose.cells/comment/get_rich_formattings/#) | إرجاع جميع كائنات الأحرف<br/> وهو ما يمثل مجموعة من الأحرف داخل نص التعليق.|



###  مثال

```python
from aspose.cells import Workbook

workbook = Workbook()
comments = workbook.worksheets[0].comments
# Add comment to cell A1
commentIndex1 = comments.add(0, 0)
comment1 = comments[commentIndex1]
comment1.note = "First note."
comment1.font.name = "Times New Roman"
# Add comment to cell B2
comments.add("B2")
comment2 = comments.get("B2")
comment2.note = "Second note."
# do your business
# Save the excel file.
workbook.save("exmaple.xlsx")

```

###  أنظر أيضا
* الوحدة [`aspose.cells`](..)
