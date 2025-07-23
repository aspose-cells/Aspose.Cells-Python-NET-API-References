---
title: Font صف
second_title: Aspose.Cells for Python via .NET API المراجع
description:
type: docs
weight: 660
url: /ar/aspose.cells/font/
is_root: false
---
##  Font صف
يقوم بتغليف كائن الخط المستخدم في جدول بيانات.



يكشف النوع Font عن الأعضاء التاليين:

###  ملكيات
| ملكية| وصف|
| :- | :- |
| [charset](/cells/python-net/ar/aspose.cells/font/charset) | تمثل مجموعة الأحرف.|
| [is_italic](/cells/python-net/ar/aspose.cells/font/is_italic) | يحصل على قيمة أو يعينها تشير إلى ما إذا كان الخط مائلًا أم لا.|
| [is_bold](/cells/python-net/ar/aspose.cells/font/is_bold) | يحصل على قيمة أو يعينها للإشارة إلى ما إذا كان الخط غامقًا أم لا.|
| [caps_type](/cells/python-net/ar/aspose.cells/font/caps_type) | يحصل على نوع أحرف النص ويقوم بتعيينه.|
| [strike_type](/cells/python-net/ar/aspose.cells/font/strike_type) | يحصل على نوع الضربة للنص.|
| [is_strikeout](/cells/python-net/ar/aspose.cells/font/is_strikeout) | يحصل على قيمة أو يعينها للإشارة إلى ما إذا كان الخط مشطوبًا بشكل فردي.|
| [script_offset](/cells/python-net/ar/aspose.cells/font/script_offset) | يحصل على إزاحة البرنامج النصي ويضبطها، بوحدة النسبة المئوية|
| [is_superscript](/cells/python-net/ar/aspose.cells/font/is_superscript) | يحصل على قيمة أو يعينها للإشارة إلى ما إذا كان الخط علويًا.|
| [is_subscript](/cells/python-net/ar/aspose.cells/font/is_subscript) | يحصل على قيمة أو يعينها للإشارة إلى ما إذا كان الخط منخفضًا أم لا.|
| [underline](/cells/python-net/ar/aspose.cells/font/underline) | يحصل على نوع الخط المسطر أو يعينه.|
| [name](/cells/python-net/ar/aspose.cells/font/name) | يحصل على اسم [`Font`](/cells/python-net/ar/aspose.cells/font) أو يعينه.|
| [double_size](/cells/python-net/ar/aspose.cells/font/double_size) | يحصل على حجم الخط المزدوج ويحدده.|
| [size](/cells/python-net/ar/aspose.cells/font/size) | يحصل على حجم الخط أو يعينه.|
| [theme_color](/cells/python-net/ar/aspose.cells/font/theme_color) | يحصل على لون السمة ويحدده.|
| [color](/cells/python-net/ar/aspose.cells/font/color) | يحصل على لون الخط أو يعينه.|
| [argb_color](/cells/python-net/ar/aspose.cells/font/argb_color) | يحصل على اللون ويضبطه بقيمة ARGB 32 بت.|
| [is_normalize_heights](/cells/python-net/ar/aspose.cells/font/is_normalize_heights) | يشير إلى ما إذا كان تطبيع الارتفاع الذي سيتم تطبيقه على النص يتم تنفيذه.|
| [scheme_type](/cells/python-net/ar/aspose.cells/font/scheme_type) |يحصل على نوع مخطط الخط ويقوم بتعيينه.|


###  طُرق
| طريقة| وصف|
| :- | :- |
| [`equals(self, font)`](/cells/python-net/ar/aspose.cells/font/equals/#aspose.cells.font) | التحقق من تساوي الخطين.|



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
