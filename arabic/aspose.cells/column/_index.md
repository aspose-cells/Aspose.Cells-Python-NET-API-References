---
title: Column صف
second_title: Aspose.Cells for Python via .NET API المراجع
description:
type: docs
weight: 240
url: /ar/aspose.cells/column/
is_root: false
---
##  Column صف
يمثل عمودًا واحدًا في ورقة العمل.



يكشف النوع Column عن الأعضاء التاليين:

###  ملكيات
| ملكية| وصف|
| :- | :- |
| [index](/cells/python-net/ar/aspose.cells/column/index) | يحصل على فهرس هذا العمود.|
| [width](/cells/python-net/ar/aspose.cells/column/width) | يحصل على عرض العمود ويحدده بوحدة الأحرف.|
| [group_level](/cells/python-net/ar/aspose.cells/column/group_level) | يحصل على مستوى المجموعة للعمود.|
| [is_hidden](/cells/python-net/ar/aspose.cells/column/is_hidden) | يشير إلى ما إذا كان العمود مخفيًا.|
| [has_custom_style](/cells/python-net/ar/aspose.cells/column/has_custom_style) | يشير إلى ما إذا كان هذا العمود يحتوي على إعدادات نمط مخصصة (تختلف عن الإعدادات الافتراضية الموروثة من المصنف).|
| [style](/cells/python-net/ar/aspose.cells/column/style) | يحصل على نمط هذا العمود.|
| [is_collapsed](/cells/python-net/ar/aspose.cells/column/is_collapsed) | ما إذا كان العمود قد انهار|


###  طُرق
| طريقة| وصف|
| :- | :- |
| [`apply_style(self, style, flag)`](/cells/python-net/ar/aspose.cells/column/apply_style/#aspose.cells.style-aspose.cells.styleflag) | يتم تطبيق التنسيقات على العمود بأكمله.|
| [`get_style(self)`](/cells/python-net/ar/aspose.cells/column/get_style/#) | يحصل على نمط هذا العمود.|
| [`set_style(self, style)`](/cells/python-net/ar/aspose.cells/column/set_style/#aspose.cells.style) | تعيين نمط هذا العمود.|



###  مثال

```python
from aspose.cells import BackgroundType, StyleFlag, Workbook
from aspose.pydrawing import Color

# Instantiating a Workbook object
workbook = Workbook()
# Obtaining the reference of the first worksheet
worksheet = workbook.worksheets[0]
style = workbook.create_style()
# Setting the background color to Blue
style.background_color = Color.blue
# Setting the foreground color to Red
style.foreground_color = Color.red
# setting Background Pattern
style.pattern = BackgroundType.DIAGONAL_STRIPE
# New Style Flag
styleFlag = StyleFlag()
# Set All Styles
styleFlag.all = True
# Get first Column
column = worksheet.cells.columns[0]
# Apply Style to first Column
column.apply_style(style, styleFlag)
# Saving the Excel file
workbook.save("book1.xls")

```

###  أنظر أيضا
* الوحدة [`aspose.cells`](..)
