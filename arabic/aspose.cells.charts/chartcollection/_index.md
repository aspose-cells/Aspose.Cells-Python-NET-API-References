---
title: ChartCollection صف
second_title: Aspose.Cells for Python via .NET API المراجع
description:
type: docs
weight: 60
url: /ar/aspose.cells.charts/chartcollection/
is_root: false
---
##  ChartCollection صف
يقوم بتغليف مجموعة من الكائنات [`Chart`](/cells/python-net/ar/aspose.cells.charts/chart).



يكشف النوع ChartCollection عن الأعضاء التاليين:

###  ملكيات
| ملكية| وصف|
| :- | :- |
| [capacity](/cells/python-net/ar/aspose.cells.charts/chartcollection/capacity) | يحصل على عدد العناصر التي يمكن أن تحتويها قائمة المصفوفة أو يعينها.|


###  طُرق
| طريقة| وصف|
| :- | :- |
| [`add(self, type, upper_left_row, upper_left_column, lower_right_row, lower_right_column)`](/cells/python-net/ar/aspose.cells.charts/chartcollection/add/#aspose.cells.charts.charttype-int-int-int-int) | إضافة مخطط إلى المجموعة.|
| [`add(self, type, data_range, top_row, left_column, right_row, bottom_column)`](/cells/python-net/ar/aspose.cells.charts/chartcollection/add/#aspose.cells.charts.charttype-str-int-int-int-int) | إضافة مخطط إلى المجموعة.|
| [`add(self, data, data_range, is_vertical, top_row, left_column, right_row, bottom_column)`](/cells/python-net/ar/aspose.cells.charts/chartcollection/add/#bytes-str-bool-int-int-int-int) | يضيف مخططًا باستخدام قالب محدد مسبقًا.|
| [`add(self, type, data_range, is_vertical, top_row, left_column, right_row, bottom_column)`](/cells/python-net/ar/aspose.cells.charts/chartcollection/add/#aspose.cells.charts.charttype-str-bool-int-int-int-int) | إضافة مخطط إلى المجموعة.|
| [`get(self, index)`](/cells/python-net/ar/aspose.cells.charts/chartcollection/get/#int) | أضف API for Python عبر .Net. نظرًا لأن هذا [int index] غير مدعوم|
| [`get(self, name)`](/cells/python-net/ar/aspose.cells.charts/chartcollection/get/#str) | أضف API for Python عبر .Net. نظرًا لأن هذا [سلسلة الرسم البياني] غير مدعوم|
| [`copy_to(self, array)`](/cells/python-net/ar/aspose.cells.charts/chartcollection/copy_to/#list) |يقوم بنسخ قائمة المصفوفة بأكملها إلى قائمة مصفوفة أحادية البعد متوافقة، بدءًا من بداية قائمة المصفوفة المستهدفة.|
| [`copy_to(self, index, array, array_index, count)`](/cells/python-net/ar/aspose.cells.charts/chartcollection/copy_to/#int-list-int-int) | يقوم بنسخ مجموعة من العناصر من قائمة المصفوفة إلى قائمة مصفوفة أحادية البعد متوافقة، بدءًا من الفهرس المحدد لقائمة المصفوفة المستهدفة.|
| [`index_of(self, item, index)`](/cells/python-net/ar/aspose.cells.charts/chartcollection/index_of/#aspose.cells.charts.chart-int) | يبحث عن الكائن المحدد ويعيد الفهرس المبني على الصفر للظهور الأول ضمن نطاق العناصر في قائمة المصفوفة التي تمتد من الفهرس المحدد إلى العنصر الأخير.|
| [`index_of(self, item, index, count)`](/cells/python-net/ar/aspose.cells.charts/chartcollection/index_of/#aspose.cells.charts.chart-int-int) | يبحث عن الكائن المحدد ويعيد الفهرس المبني على الصفر للظهور الأول ضمن نطاق العناصر في قائمة المصفوفة التي تبدأ بالفهرس المحدد وتحتوي على العدد المحدد من العناصر.|
| [`last_index_of(self, item)`](/cells/python-net/ar/aspose.cells.charts/chartcollection/last_index_of/#aspose.cells.charts.chart) | يبحث عن الكائن المحدد ويعيد الفهرس المبني على الصفر للحدث الأخير ضمن قائمة المصفوفة بأكملها.|
| [`last_index_of(self, item, index)`](/cells/python-net/ar/aspose.cells.charts/chartcollection/last_index_of/#aspose.cells.charts.chart-int) |يبحث عن الكائن المحدد ويعيد الفهرس المبني على الصفر للحدث الأخير ضمن نطاق العناصر في قائمة المصفوفة التي تمتد من العنصر الأول إلى الفهرس المحدد.|
| [`last_index_of(self, item, index, count)`](/cells/python-net/ar/aspose.cells.charts/chartcollection/last_index_of/#aspose.cells.charts.chart-int-int) | يبحث عن الكائن المحدد ويعيد الفهرس المبدئي للصفر للحدث الأخير ضمن نطاق العناصر في قائمة المصفوفة التي تحتوي على عدد محدد من العناصر وتنتهي عند الفهرس المحدد.|
| [`add_floating_chart(self, type, left, top, width, height)`](/cells/python-net/ar/aspose.cells.charts/chartcollection/add_floating_chart/#aspose.cells.charts.charttype-int-int-int-int) | إضافة مخطط إلى المجموعة.|
| [`binary_search(self, item)`](/cells/python-net/ar/aspose.cells.charts/chartcollection/binary_search/#aspose.cells.charts.chart) | يبحث في قائمة المصفوفة المفرزة بأكملها عن عنصر باستخدام المقارن الافتراضي ويعيد الفهرس المبني على الصفر للعنصر.|



###  مثال

```python
from aspose.cells import Workbook

workbook = Workbook()
charts = workbook.worksheets[0].charts

```

###  أنظر أيضا
* الوحدة [`aspose.cells.charts`](..)
* فئة [`Chart`](/cells/python-net/ar/aspose.cells.charts/chart)
