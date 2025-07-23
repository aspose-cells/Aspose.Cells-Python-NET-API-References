---
title: Sparkline صف
second_title: Aspose.Cells for Python via .NET API المراجع
description:
type: docs
weight: 270
url: /ar/aspose.cells.charts/sparkline/
is_root: false
---
##  Sparkline صف
يمثل الشريط الشريطي مخططًا أو رسمًا صغيرًا في خلية ورقة العمل التي توفر تمثيلًا مرئيًا للبيانات.



يكشف النوع Sparkline عن الأعضاء التاليين:

###  ملكيات
| ملكية| وصف|
| :- | :- |
| [data_range](/cells/python-net/ar/aspose.cells.charts/sparkline/data_range) | يمثل نطاق البيانات للمخطط الشريطي.|
| [row](/cells/python-net/ar/aspose.cells.charts/sparkline/row) | يحصل على مؤشر الصف للمخطط الشريطي.|
| [column](/cells/python-net/ar/aspose.cells.charts/sparkline/column) | يحصل على فهرس العمود للمخطط الشريطي.|


###  طُرق
| طريقة| وصف|
| :- | :- |
| [`to_image(self, file_name, options)`](/cells/python-net/ar/aspose.cells.charts/sparkline/to_image/#str-aspose.cells.rendering.imageorprintoptions) | يقوم بتحويل الرسم البياني الشريطي إلى صورة.|
| [`to_image(self, stream, options)`](/cells/python-net/ar/aspose.cells.charts/sparkline/to_image/#io.rawiobase-aspose.cells.rendering.imageorprintoptions) | يقوم بتحويل الرسم البياني الشريطي إلى صورة.|



###  مثال

```python
from aspose.cells import CellArea, Workbook
from aspose.cells.charts import SparklineType
from aspose.cells.rendering import ImageOrPrintOptions

book = Workbook()
sheet = book.worksheets[0]
sheet.cells.get("A1").put_value(5)
sheet.cells.get("B1").put_value(2)
sheet.cells.get("C1").put_value(1)
sheet.cells.get("D1").put_value(3)
#  Define the CellArea
ca = CellArea()
ca.start_column = 4
ca.end_column = 4
ca.start_row = 0
ca.end_row = 0
idx = sheet.sparkline_groups.add(SparklineType.LINE, sheet.name + "!A1:D1", False, ca)
group = sheet.sparkline_groups[idx]
idx = group.sparklines.add(sheet.name + "!A1:D1", 0, 4)
line = group.sparklines[idx]
print("Saprkline data range: "  + line.data_range + ", row: "  + str(line.row) + ", column: "  + str(line.column))
line.to_image("output.png", ImageOrPrintOptions())

```

###  أنظر أيضا
* الوحدة [`aspose.cells.charts`](..)
