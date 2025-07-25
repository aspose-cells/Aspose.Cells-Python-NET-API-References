---
title: Top10 صف
second_title: Aspose.Cells for Python via .NET API المراجع
description:
type: docs
weight: 1460
url: /ar/aspose.cells/top10/
is_root: false
---
##  Top10 صف
 وصف قاعدة التنسيق الشرطي Top10.
تسلط قاعدة التنسيق الشرطي هذه الضوء على الخلايا التي
تقع القيم في القوس العلوي N أو القوس السفلي N، كما هو محدد.



يكشف النوع Top10 عن الأعضاء التاليين:

###  البنائين
| البناء| وصف|
| :- | :- |
| [`__init__(self)`](/cells/python-net/ar/aspose.cells/top10/__init__/#) | إنشاء مثيل جديد لـ Top10|


###  ملكيات
| ملكية| وصف|
| :- | :- |
| [is_percent](/cells/python-net/ar/aspose.cells/top10/is_percent) | احصل على أو قم بتعيين ما إذا كانت قاعدة "أعلى/أسفل n" هي قاعدة "أعلى/أسفل n بالمائة".<br/> القيمة الافتراضية هي false.|
| [is_bottom](/cells/python-net/ar/aspose.cells/top10/is_bottom) | احصل على أو قم بتعيين ما إذا كانت قاعدة "أعلى/أسفل n" هي قاعدة "أسفل n".<br/> القيمة الافتراضية هي false.|
| [rank](/cells/python-net/ar/aspose.cells/top10/rank) | الحصول على قيمة "n" أو تعيينها في قاعدة التنسيق الشرطي "أعلى/أسفل n".<br/>إذا كانت IsPercent صحيحة، فيجب أن تكون القيمة بين 0 و100.<br/>وإلا فيجب أن يكون بين 0 و 1000.<br/> القيمة الافتراضية هي 10.|



###  مثال

```python
from aspose.cells import CellArea, FormatConditionType, OperatorType, Workbook
from aspose.pydrawing import Color

# Instantiating a Workbook object
workbook = Workbook()
sheet = workbook.worksheets[0]
# Adds an empty conditional formatting
index = sheet.conditional_formattings.add()
fcs = sheet.conditional_formattings[index]
# Sets the conditional format range.
ca = CellArea.create_cell_area(0, 0, 10, 10)
fcs.add_area(ca)
# Adds condition.
conditionIndex = fcs.add_condition(FormatConditionType.TOP10, OperatorType.NONE, None, None)
# Sets the background color.
fc = fcs[conditionIndex]
fc.style.background_color = Color.red
top10 = fc.top10
# Set the Top N
top10.rank = 5
# Saving the Excel file
workbook.save("output.xls")

```

###  أنظر أيضا
* الوحدة [`aspose.cells`](..)
