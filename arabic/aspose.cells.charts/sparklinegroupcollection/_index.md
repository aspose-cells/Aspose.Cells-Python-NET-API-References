---
title: SparklineGroupCollection صف
second_title: Aspose.Cells for Python via .NET API المراجع
description:
type: docs
weight: 300
url: /ar/aspose.cells.charts/sparklinegroupcollection/
is_root: false
---
##  SparklineGroupCollection صف
يقوم بتغليف مجموعة من الكائنات [`SparklineGroup`](/cells/python-net/ar/aspose.cells.charts/sparklinegroup).



يكشف النوع SparklineGroupCollection عن الأعضاء التاليين:

###  ملكيات
| ملكية| وصف|
| :- | :- |
| [capacity](/cells/python-net/ar/aspose.cells.charts/sparklinegroupcollection/capacity) | يحصل على عدد العناصر التي يمكن أن تحتويها قائمة المصفوفة أو يعينها.|


###  طُرق
| طريقة| وصف|
| :- | :- |
| [`add(self, type)`](/cells/python-net/ar/aspose.cells.charts/sparklinegroupcollection/add/#aspose.cells.charts.sparklinetype) | يضيف [`SparklineGroup`](/cells/python-net/ar/aspose.cells.charts/sparklinegroup) مع [`Sparkline`](/cells/python-net/ar/aspose.cells.charts/sparkline) إلى المجموعة.|
| [`add(self, type, data_range, is_vertical, location_range)`](/cells/python-net/ar/aspose.cells.charts/sparklinegroupcollection/add/#aspose.cells.charts.sparklinetype-str-bool-aspose.cells.cellarea) | يضيف [`SparklineGroup`](/cells/python-net/ar/aspose.cells.charts/sparklinegroup) مع [`Sparkline`](/cells/python-net/ar/aspose.cells.charts/sparkline) إلى المجموعة.|
| [`copy_to(self, array)`](/cells/python-net/ar/aspose.cells.charts/sparklinegroupcollection/copy_to/#list) |يقوم بنسخ قائمة المصفوفة بأكملها إلى قائمة مصفوفة أحادية البعد متوافقة، بدءًا من بداية قائمة المصفوفة المستهدفة.|
| [`copy_to(self, index, array, array_index, count)`](/cells/python-net/ar/aspose.cells.charts/sparklinegroupcollection/copy_to/#int-list-int-int) | يقوم بنسخ مجموعة من العناصر من قائمة المصفوفة إلى قائمة مصفوفة أحادية البعد متوافقة، بدءًا من الفهرس المحدد لقائمة المصفوفة المستهدفة.|
| [`index_of(self, item, index)`](/cells/python-net/ar/aspose.cells.charts/sparklinegroupcollection/index_of/#aspose.cells.charts.sparklinegroup-int) | يبحث عن الكائن المحدد ويعيد الفهرس المبني على الصفر للظهور الأول ضمن نطاق العناصر في قائمة المصفوفة التي تمتد من الفهرس المحدد إلى العنصر الأخير.|
| [`index_of(self, item, index, count)`](/cells/python-net/ar/aspose.cells.charts/sparklinegroupcollection/index_of/#aspose.cells.charts.sparklinegroup-int-int) | يبحث عن الكائن المحدد ويعيد الفهرس المبني على الصفر للظهور الأول ضمن نطاق العناصر في قائمة المصفوفة التي تبدأ بالفهرس المحدد وتحتوي على العدد المحدد من العناصر.|
| [`last_index_of(self, item)`](/cells/python-net/ar/aspose.cells.charts/sparklinegroupcollection/last_index_of/#aspose.cells.charts.sparklinegroup) | يبحث عن الكائن المحدد ويعيد الفهرس المبني على الصفر للحدث الأخير ضمن قائمة المصفوفة بأكملها.|
| [`last_index_of(self, item, index)`](/cells/python-net/ar/aspose.cells.charts/sparklinegroupcollection/last_index_of/#aspose.cells.charts.sparklinegroup-int) |يبحث عن الكائن المحدد ويعيد الفهرس المبني على الصفر للحدث الأخير ضمن نطاق العناصر في قائمة المصفوفة التي تمتد من العنصر الأول إلى الفهرس المحدد.|
| [`last_index_of(self, item, index, count)`](/cells/python-net/ar/aspose.cells.charts/sparklinegroupcollection/last_index_of/#aspose.cells.charts.sparklinegroup-int-int) | يبحث عن الكائن المحدد ويعيد الفهرس المبدئي للصفر للحدث الأخير ضمن نطاق العناصر في قائمة المصفوفة التي تحتوي على عدد محدد من العناصر وتنتهي عند الفهرس المحدد.|
| [`clear_sparklines(self, cell_area)`](/cells/python-net/ar/aspose.cells.charts/sparklinegroupcollection/clear_sparklines/#aspose.cells.cellarea) | يقوم بمسح الخطوط الشريطية الموجودة داخل منطقة الخلايا.|
| [`clear_sparkline_groups(self, cell_area)`](/cells/python-net/ar/aspose.cells.charts/sparklinegroupcollection/clear_sparkline_groups/#aspose.cells.cellarea) | يقوم بمسح مجموعات الخطوط الشريطية التي تتداخل مع منطقة من الخلايا.|
| [`binary_search(self, item)`](/cells/python-net/ar/aspose.cells.charts/sparklinegroupcollection/binary_search/#aspose.cells.charts.sparklinegroup) | يبحث في قائمة المصفوفة المفرزة بأكملها عن عنصر باستخدام المقارن الافتراضي ويعيد الفهرس المبني على الصفر للعنصر.|



###  مثال

```python
from aspose.cells import CellArea, SaveFormat, Workbook
from aspose.cells.charts import SparklineType

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
idx = sheet.sparkline_groups.add(SparklineType.LINE, "A1:D1", False, ca)
group = sheet.sparkline_groups[idx]
group.sparklines.add(sheet.name + "!A1:D1", 0, 4)
book.save("output.xlsx", SaveFormat.XLSX)

```

###  أنظر أيضا
* الوحدة [`aspose.cells.charts`](..)
* فئة [`Sparkline`](/cells/python-net/ar/aspose.cells.charts/sparkline)
* فئة [`SparklineGroup`](/cells/python-net/ar/aspose.cells.charts/sparklinegroup)
