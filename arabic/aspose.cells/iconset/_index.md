---
title: IconSet صف
second_title: Aspose.Cells for Python via .NET API المراجع
description:
type: docs
weight: 850
url: /ar/aspose.cells/iconset/
is_root: false
---
##  IconSet صف
 وصف قاعدة التنسيق الشرطي IconSet.
تطبق قاعدة التنسيق الشرطي هذه الرموز على الخلايا
وفقا لقيمهم.



يكشف النوع IconSet عن الأعضاء التاليين:

###  ملكيات
| ملكية| وصف|
| :- | :- |
| [cf_icons](/cells/python-net/ar/aspose.cells/iconset/cf_icons) | احصل على [`ConditionalFormattingIcon`](/cells/python-net/ar/aspose.cells/conditionalformattingicon) من المجموعة|
| [cfvos](/cells/python-net/ar/aspose.cells/iconset/cfvos) | احصل على مثيل CFValueObjects.|
| [type](/cells/python-net/ar/aspose.cells/iconset/type) | احصل على نوع مجموعة الأيقونات التي تريد عرضها أو قم بتعيينها.<br/>سيؤدي ضبط النوع إلى التحقق تلقائيًا مما إذا كان عدد Cfvos الحالي هو<br/> متوافق مع النوع الجديد. إذا لم يكن متوافقًا، فسيتم تنظيف Cfvos القديم و<br/> سيتم إضافة Cfvos الافتراضي.|
| [is_custom](/cells/python-net/ar/aspose.cells/iconset/is_custom) | يشير إلى ما إذا كانت مجموعة الرموز مخصصة.<br/> القيمة الافتراضية هي false.|
| [show_value](/cells/python-net/ar/aspose.cells/iconset/show_value) | احصل على العلم الذي يشير إلى ما إذا كان سيتم عرض قيم الخلايا التي يتم تطبيق مجموعة الرموز هذه عليها أم لا.<br/> القيمة الافتراضية هي true.|
| [reverse](/cells/python-net/ar/aspose.cells/iconset/reverse) |احصل على العلم الذي يشير إلى ما إذا كان سيتم عكس الترتيب الافتراضي للرموز في مجموعة الرموز هذه أم لا.<br/> القيمة الافتراضية هي false.|



###  مثال

```python
from aspose.cells import CellArea, FormatConditionType, IconSetType, Workbook

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
idx = fcs.add_condition(FormatConditionType.ICON_SET)
fcs.add_area(ca)
cond = fcs[idx]
# Get Icon Set
iconSet = cond.icon_set
# Set Icon Type
iconSet.type = IconSetType.ARROWS3
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
* فئة [`ConditionalFormattingIcon`](/cells/python-net/ar/aspose.cells/conditionalformattingicon)
