---
title: Font صف
second_title: Aspose.Cells for Python via .NET API المراجع
description:
type: docs
weight: 680
url: /ar/aspose.cells/font/
is_root: false
---
##  Font صف
يقوم بتغليف كائن الخط المستخدم في جدول البيانات.



يكشف النوع Font عن الأعضاء التاليين:

###  ملكيات
| ملكية| وصف|
| :- | :- |
| [charset](/cells/python-net/ar/aspose.cells/font/charset) | تمثيل مجموعة الأحرف.|
| [is_italic](/cells/python-net/ar/aspose.cells/font/is_italic) | الحصول على قيمة أو تعيينها تشير إلى ما إذا كان الخط مائلًا.|
| [is_bold](/cells/python-net/ar/aspose.cells/font/is_bold) | الحصول على قيمة تشير إلى ما إذا كان الخط غامقًا أو تعيينها.|
| [caps_type](/cells/python-net/ar/aspose.cells/font/caps_type) | الحصول على نوع الحروف الكبيرة للنص وتعيينه.|
| [strike_type](/cells/python-net/ar/aspose.cells/font/strike_type) | يحصل على نوع المخالفة للنص.|
| [is_strikeout](/cells/python-net/ar/aspose.cells/font/is_strikeout) | الحصول على قيمة أو تعيينها تشير إلى ما إذا كان الخط يتوسطه خط واحد.|
| [script_offset](/cells/python-net/ar/aspose.cells/font/script_offset) | الحصول على إزاحة البرنامج النصي وتعيينها بوحدة النسبة المئوية|
| [is_superscript](/cells/python-net/ar/aspose.cells/font/is_superscript) | الحصول على قيمة أو تعيينها تشير إلى ما إذا كان الخط نصًا فائقًا.|
| [is_subscript](/cells/python-net/ar/aspose.cells/font/is_subscript) | الحصول على قيمة تشير إلى ما إذا كان الخط منخفضًا أو تعيينها.|
| [underline](/cells/python-net/ar/aspose.cells/font/underline) | الحصول على نوع التسطير أو تعيينه.|
| [name](/cells/python-net/ar/aspose.cells/font/name) | الحصول على أو تعيين اسم [`Font`](/cells/python-net/ar/aspose.cells/font).|
| [double_size](/cells/python-net/ar/aspose.cells/font/double_size) | الحصول على الحجم المزدوج للخط وتعيينه.|
| [size](/cells/python-net/ar/aspose.cells/font/size) | الحصول على حجم الخط أو تعيينه.|
| [theme_color](/cells/python-net/ar/aspose.cells/font/theme_color) | الحصول على لون السمة وتعيينه.|
| [color](/cells/python-net/ar/aspose.cells/font/color) | الحصول على أو تعيين لون الخط.|
| [argb_color](/cells/python-net/ar/aspose.cells/font/argb_color) | الحصول على اللون وتعيينه بقيمة ARGB 32 بت.|
| [is_normalize_heights](/cells/python-net/ar/aspose.cells/font/is_normalize_heights) | يشير إلى ما إذا كان سيتم تطبيق تسوية الارتفاع على تشغيل النص.|
| [scheme_type](/cells/python-net/ar/aspose.cells/font/scheme_type) |الحصول على نوع مخطط الخط وتعيينه.|


###  طُرق
| طريقة| وصف|
| :- | :- |
| [equals](/cells/python-net/ar/aspose.cells/font/equals/#aspose.cells.Font) | يتحقق مما إذا كان الخطان متساويان.|



###  مثال

```python
from aspose.cells import Workbook
from aspose.pydrawing import Color

# Instantiating a Workbook object
workbook = Workbook()
# Obtaining the reference of the newly added worksheet by passing its sheet index
worksheet = workbook.worksheets[0]
# Accessing the "A1" cell from the worksheet
cell = worksheet.cells.get("A1")
# Adding some value to the "A1" cell
cell.put_value("Hello Aspose!")
font = cell.get_style().font
# Setting the font name to "Times New Roman"
font.name = "Times New Roman"
# Setting font size to 14
font.size = 14
# setting font color as Red
font.color = Color.red
# Saving the Excel file
workbook.save(r"dest.xls")

```

###  أنظر أيضا
* الوحدة [`aspose.cells`](..)
* فئة [`Font`](/cells/python-net/ar/aspose.cells/font)
