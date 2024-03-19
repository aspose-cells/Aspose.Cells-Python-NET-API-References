---
title: DataBar صف
second_title: Aspose.Cells for Python via .NET API المراجع
description:
type: docs
weight: 420
url: /ar/aspose.cells/databar/
is_root: false
---
##  DataBar صف
 وصف قاعدة التنسيق الشرطي DataBar.
تعرض قاعدة التنسيق الشرطي هذه درجة متدرجة
شريط البيانات في نطاق الخلايا.



يكشف النوع DataBar عن الأعضاء التاليين:

###  ملكيات
| ملكية| وصف|
| :- | :- |
| [axis_color](/cells/python-net/ar/aspose.cells/databar/axis_color) | الحصول على لون محور الخلايا ذات التنسيق الشرطي كأشرطة بيانات.|
| [axis_position](/cells/python-net/ar/aspose.cells/databar/axis_position) | الحصول على أو تعيين موضع محور أشرطة البيانات المحددة بواسطة قاعدة التنسيق الشرطي.|
| [bar_fill_type](/cells/python-net/ar/aspose.cells/databar/bar_fill_type) | الحصول على أو تعيين كيفية ملء شريط البيانات بالألوان.|
| [direction](/cells/python-net/ar/aspose.cells/databar/direction) |الحصول على أو تعيين اتجاه عرض شريط البيانات.|
| [bar_border](/cells/python-net/ar/aspose.cells/databar/bar_border) | الحصول على كائن يحدد حدود شريط البيانات.|
| [negative_bar_format](/cells/python-net/ar/aspose.cells/databar/negative_bar_format) | الحصول على كائن NegativeBarFormat المرتبط بقاعدة التنسيق الشرطي لشريط البيانات.|
| [min_cfvo](/cells/python-net/ar/aspose.cells/databar/min_cfvo) | احصل على كائن القيمة الدنيا لـ DataBar أو قم بتعيينه.<br/> لا يمكن تعيين قيمة فارغة أو CFValueObject بالنوع FormatConditionValueType.Max إليها.|
| [max_cfvo](/cells/python-net/ar/aspose.cells/databar/max_cfvo) | احصل على أو قم بتعيين كائن القيمة القصوى لـ DataBar.<br/> لا يمكن تعيين قيمة فارغة أو CFValueObject بالنوع FormatConditionValueType.Min إليها.|
| [color](/cells/python-net/ar/aspose.cells/databar/color) | احصل على أو قم بتعيين لون DataBar هذا.|
| [min_length](/cells/python-net/ar/aspose.cells/databar/min_length) | يمثل الحد الأدنى لطول شريط البيانات.|
| [max_length](/cells/python-net/ar/aspose.cells/databar/max_length) | يمثل الحد الأقصى لطول شريط البيانات.|
| [show_value](/cells/python-net/ar/aspose.cells/databar/show_value) | احصل على أو قم بتعيين العلامة التي تشير إلى ما إذا كان سيتم إظهار قيم الخلايا التي تم تطبيق شريط البيانات عليها أم لا.<br/> القيمة الافتراضية صحيحة.|


###  طُرق
| طريقة| وصف|
| :- | :- |
| [to_image](/cells/python-net/ar/aspose.cells/databar/to_image/#aspose.cells.Cell-aspose.cells.rendering.ImageOrPrintOptions) | تقديم شريط البيانات في الخلية إلى صفيف بايت الصورة.|



###  مثال

```python
from aspose.cells import CellArea, DataBarAxisPosition, DataBarBorderType, DataBarFillType, DataBarNegativeColorType, FormatConditionType, FormatConditionValueType, Workbook
from aspose.pydrawing import Color

# Instantiating a Workbook object
workbook = Workbook()
sheet = workbook.worksheets[0]
# Adds an empty conditional formatting
index = sheet.conditional_formattings.add()
fcs = sheet.conditional_formattings[index]
# Sets the conditional format range.
ca = CellArea()
ca.start_row = 0
ca.end_row = 2
ca.start_column = 0
ca.end_column = 0
fcs.add_area(ca)
# Adds condition.
idx = fcs.add_condition(FormatConditionType.DATA_BAR)
fcs.add_area(ca)
cond = fcs[idx]
# Get Databar
dataBar = cond.data_bar
dataBar.color = Color.orange
# Set Databar properties
dataBar.min_cfvo.type = FormatConditionValueType.PERCENTILE
dataBar.min_cfvo.value = 30
dataBar.show_value = False
dataBar.bar_border.type = DataBarBorderType.SOLID
dataBar.bar_border.color = Color.plum
dataBar.bar_fill_type = DataBarFillType.SOLID
dataBar.axis_color = Color.red
dataBar.axis_position = DataBarAxisPosition.MIDPOINT
dataBar.negative_bar_format.color_type = DataBarNegativeColorType.COLOR
dataBar.negative_bar_format.color = Color.white
dataBar.negative_bar_format.border_color_type = DataBarNegativeColorType.COLOR
dataBar.negative_bar_format.border_color = Color.yellow
# Put Cell Values
cell1 = sheet.cells.get("A1")
cell1.put_value(10)
cell2 = sheet.cells.get("A2")
cell2.put_value(120)
cell3 = sheet.cells.get("A3")
cell3.put_value(260)
# Saving the Excel file
workbook.save("book1.xlsx")

```

###  أنظر أيضا
* الوحدة [`aspose.cells`](..)
