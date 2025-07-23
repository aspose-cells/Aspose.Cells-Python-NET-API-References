---
title: TimelineCollection صف
second_title: Aspose.Cells for Python via .NET API المراجع
description:
type: docs
weight: 20
url: /ar/aspose.cells.timelines/timelinecollection/
is_root: false
---
##  TimelineCollection صف
يحدد مجموعة كل كائنات الجدول الزمني الموجودة في ورقة العمل المحددة.
بسبب MS Excel، لا يدعم Excel 2003 الجدول الزمني.



يكشف النوع TimelineCollection عن الأعضاء التاليين:

###  ملكيات
| ملكية| وصف|
| :- | :- |
| [capacity](/cells/python-net/ar/aspose.cells.timelines/timelinecollection/capacity) | يحصل على عدد العناصر التي يمكن أن تحتويها قائمة المصفوفة أو يعينها.|


###  طُرق
| طريقة| وصف|
| :- | :- |
| [`add(self, pivot, row, column, base_field_name)`](/cells/python-net/ar/aspose.cells.timelines/timelinecollection/add/#aspose.cells.pivot.pivottable-int-int-str) | إضافة جدول زمني جديد باستخدام PivotTable كمصدر للبيانات|
| [`add(self, pivot, dest_cell_name, base_field_name)`](/cells/python-net/ar/aspose.cells.timelines/timelinecollection/add/#aspose.cells.pivot.pivottable-str-str) | إضافة جدول زمني جديد باستخدام PivotTable كمصدر للبيانات|
| [`add(self, pivot, row, column, base_field_index)`](/cells/python-net/ar/aspose.cells.timelines/timelinecollection/add/#aspose.cells.pivot.pivottable-int-int-int) | إضافة جدول زمني جديد باستخدام PivotTable كمصدر للبيانات|
| [`add(self, pivot, dest_cell_name, base_field_index)`](/cells/python-net/ar/aspose.cells.timelines/timelinecollection/add/#aspose.cells.pivot.pivottable-str-int) | إضافة جدول زمني جديد باستخدام PivotTable كمصدر للبيانات|
| [`add(self, pivot, row, column, base_field)`](/cells/python-net/ar/aspose.cells.timelines/timelinecollection/add/#aspose.cells.pivot.pivottable-int-int-aspose.cells.pivot.pivotfield) | إضافة جدول زمني جديد باستخدام PivotTable كمصدر للبيانات|
| [`add(self, pivot, dest_cell_name, base_field)`](/cells/python-net/ar/aspose.cells.timelines/timelinecollection/add/#aspose.cells.pivot.pivottable-str-aspose.cells.pivot.pivotfield) | إضافة جدول زمني جديد باستخدام PivotTable كمصدر للبيانات|
| [`copy_to(self, array)`](/cells/python-net/ar/aspose.cells.timelines/timelinecollection/copy_to/#list) |يقوم بنسخ قائمة المصفوفة بأكملها إلى قائمة مصفوفة أحادية البعد متوافقة، بدءًا من بداية قائمة المصفوفة المستهدفة.|
| [`copy_to(self, index, array, array_index, count)`](/cells/python-net/ar/aspose.cells.timelines/timelinecollection/copy_to/#int-list-int-int) | يقوم بنسخ مجموعة من العناصر من قائمة المصفوفة إلى قائمة مصفوفة أحادية البعد متوافقة، بدءًا من الفهرس المحدد لقائمة المصفوفة المستهدفة.|
| [`index_of(self, item, index)`](/cells/python-net/ar/aspose.cells.timelines/timelinecollection/index_of/#aspose.cells.timelines.timeline-int) | يبحث عن الكائن المحدد ويعيد الفهرس المبني على الصفر للظهور الأول ضمن نطاق العناصر في قائمة المصفوفة التي تمتد من الفهرس المحدد إلى العنصر الأخير.|
| [`index_of(self, item, index, count)`](/cells/python-net/ar/aspose.cells.timelines/timelinecollection/index_of/#aspose.cells.timelines.timeline-int-int) | يبحث عن الكائن المحدد ويعيد الفهرس المبني على الصفر للظهور الأول ضمن نطاق العناصر في قائمة المصفوفة التي تبدأ بالفهرس المحدد وتحتوي على العدد المحدد من العناصر.|
| [`last_index_of(self, item)`](/cells/python-net/ar/aspose.cells.timelines/timelinecollection/last_index_of/#aspose.cells.timelines.timeline) | يبحث عن الكائن المحدد ويعيد الفهرس المبني على الصفر للحدث الأخير ضمن قائمة المصفوفة بأكملها.|
| [`last_index_of(self, item, index)`](/cells/python-net/ar/aspose.cells.timelines/timelinecollection/last_index_of/#aspose.cells.timelines.timeline-int) |يبحث عن الكائن المحدد ويعيد الفهرس المبني على الصفر للحدث الأخير ضمن نطاق العناصر في قائمة المصفوفة التي تمتد من العنصر الأول إلى الفهرس المحدد.|
| [`last_index_of(self, item, index, count)`](/cells/python-net/ar/aspose.cells.timelines/timelinecollection/last_index_of/#aspose.cells.timelines.timeline-int-int) | يبحث عن الكائن المحدد ويعيد الفهرس المبدئي للصفر للحدث الأخير ضمن نطاق العناصر في قائمة المصفوفة التي تحتوي على عدد محدد من العناصر وتنتهي عند الفهرس المحدد.|
| [`get(self, name)`](/cells/python-net/ar/aspose.cells.timelines/timelinecollection/get/#str) | يحصل على الجدول الزمني حسب اسم الجدول الزمني.|
| [`binary_search(self, item)`](/cells/python-net/ar/aspose.cells.timelines/timelinecollection/binary_search/#aspose.cells.timelines.timeline) | يبحث في قائمة المصفوفة المفرزة بأكملها عن عنصر باستخدام المقارن الافتراضي ويعيد الفهرس المبني على الصفر للعنصر.|



###  مثال

```python
from aspose.cells import CellsFactory, Workbook
from aspose.cells.pivot import PivotFieldType, PivotTableStyleType
from datetime import datetime

book = Workbook()
sheet = book.worksheets[0]
cells = sheet.cells
cells.get(0, 0).value = "fruit"
cells.get(1, 0).value = "grape"
cells.get(2, 0).value = "blueberry"
cells.get(3, 0).value = "kiwi"
cells.get(4, 0).value = "cherry"
# Create date style
dateStyle = CellsFactory().create_style()
dateStyle.custom = "m/d/yyyy"
cells.get(0, 1).value = "date"
cells.get(1, 1).value = datetime(2021, 2, 5)
cells.get(2, 1).value = datetime(2022, 3, 8)
cells.get(3, 1).value = datetime(2023, 4, 10)
cells.get(4, 1).value = datetime(2024, 5, 16)
# Set date style
cells.get(1, 1).set_style(dateStyle)
cells.get(2, 1).set_style(dateStyle)
cells.get(3, 1).set_style(dateStyle)
cells.get(4, 1).set_style(dateStyle)
cells.get(0, 2).value = "amount"
cells.get(1, 2).value = 50
cells.get(2, 2).value = 60
cells.get(3, 2).value = 70
cells.get(4, 2).value = 80
pivots = sheet.pivot_tables
# Add a PivotTable
pivotIndex = pivots.add("=Sheet1!A1:C5", "A12", "TestPivotTable")
pivot = pivots[pivotIndex]
pivot.add_field_to_area(PivotFieldType.ROW, "fruit")
pivot.add_field_to_area(PivotFieldType.COLUMN, "date")
pivot.add_field_to_area(PivotFieldType.DATA, "amount")
pivot.pivot_table_style_type = PivotTableStyleType.PIVOT_TABLE_STYLE_MEDIUM10
# Refresh PivotTable data
pivot.refresh_data()
pivot.calculate_data()
# do your business
book.save("out.xlsx")

```

###  أنظر أيضا
* الوحدة [`aspose.cells.timelines`](..)
