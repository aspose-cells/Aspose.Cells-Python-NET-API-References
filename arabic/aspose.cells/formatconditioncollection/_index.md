---
title: FormatConditionCollection صف
second_title: Aspose.Cells for Python via .NET API المراجع
description:
type: docs
weight: 730
url: /ar/aspose.cells/formatconditioncollection/
is_root: false
---
##  FormatConditionCollection صف
يمثل التنسيق الشرطي.
يمكن أن تحتوي FormatConditions على ما يصل إلى ثلاثة تنسيقات شرطية.



يكشف النوع FormatConditionCollection عن الأعضاء التاليين:

###  ملكيات
| ملكية| وصف|
| :- | :- |
| [count](/cells/python-net/ar/aspose.cells/formatconditioncollection/count) | يحصل على عدد من الشروط.|
| [range_count](/cells/python-net/ar/aspose.cells/formatconditioncollection/range_count) | الحصول على عدد النطاقات المنسقة بشكل مشروط.|



يحصل على حالة التنسيق حسب الفهرس.
###  مفهرس
| اسم| وصف|
| :- | :- |
| [index] |فهرس شرط التنسيق المراد إرجاعه.|


###  طُرق
| طريقة| وصف|
| :- | :- |
| [add_condition](/cells/python-net/ar/aspose.cells/formatconditioncollection/add_condition/#aspose.cells.FormatConditionType-aspose.cells.OperatorType-str-str) | إضافة شرط التنسيق.|
| [add_condition](/cells/python-net/ar/aspose.cells/formatconditioncollection/add_condition/#aspose.cells.FormatConditionType) | إضافة شرط التنسيق.|
| [remove_area](/cells/python-net/ar/aspose.cells/formatconditioncollection/remove_area/#int) | إزالة نطاق الخلايا المنسقة الشرطية حسب الفهرس.|
| [remove_area](/cells/python-net/ar/aspose.cells/formatconditioncollection/remove_area/#int-int-int-int) | إزالة التنسيق الشرطي في النطاق.|
| [add](/cells/python-net/ar/aspose.cells/formatconditioncollection/add/#aspose.cells.CellArea-aspose.cells.FormatConditionType-aspose.cells.OperatorType-str-str) | يضيف شرط التنسيق ورن الخلية المؤثرة إلى FormatConditions<br/>يمكن أن تحتوي FormatConditions على ما يصل إلى ثلاثة تنسيقات شرطية.<br/> لا يُسمح بالمراجع إلى الأوراق الأخرى في صيغ التنسيق الشرطي.|
| [add_area](/cells/python-net/ar/aspose.cells/formatconditioncollection/add_area/#aspose.cells.CellArea) | إضافة نطاق خلايا منسقة شرطيًا.|
| [get_cell_area](/cells/python-net/ar/aspose.cells/formatconditioncollection/get_cell_area/#int) | الحصول على نطاق الخلايا المنسقة الشرطية حسب الفهرس.|
| [remove_condition](/cells/python-net/ar/aspose.cells/formatconditioncollection/remove_condition/#int) | يزيل شرط التنسيق حسب الفهرس.|



###  مثال

```python
from aspose.cells import CellArea, FormatConditionType, OperatorType, Workbook
from aspose.pydrawing import Color

# Create a new Workbook.
workbook = Workbook()
# Get the first worksheet.
sheet = workbook.worksheets[0]
# Adds an empty conditional formatting
index = sheet.conditional_formattings.add()
fcs = sheet.conditional_formattings[index]
# Sets the conditional format range.
ca = CellArea()
ca.start_row = 0
ca.end_row = 0
ca.start_column = 0
ca.end_column = 0
fcs.add_area(ca)
ca = CellArea()
ca.start_row = 1
ca.end_row = 1
ca.start_column = 1
ca.end_column = 1
fcs.add_area(ca)
# Adds condition.
conditionIndex = fcs.add_condition(FormatConditionType.CELL_VALUE, OperatorType.BETWEEN, "=A2", "100")
# Adds condition.
conditionIndex2 = fcs.add_condition(FormatConditionType.CELL_VALUE, OperatorType.BETWEEN, "50", "100")
# Sets the background color.
fc = fcs[conditionIndex]
fc.style.background_color = Color.red
# Saving the Excel file
workbook.save("output.xls")

```

###  أنظر أيضا
* الوحدة [`aspose.cells`](..)
