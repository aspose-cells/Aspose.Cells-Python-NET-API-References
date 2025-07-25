---
title: SeriesCollection صف
second_title: Aspose.Cells for Python via .NET API المراجع
description:
type: docs
weight: 250
url: /ar/aspose.cells.charts/seriescollection/
is_root: false
---
##  SeriesCollection صف
يقوم بتغليف مجموعة من الكائنات [`Series`](/cells/python-net/ar/aspose.cells.charts/series).



يكشف النوع SeriesCollection عن الأعضاء التاليين:

###  ملكيات
| ملكية| وصف|
| :- | :- |
| [category_data](/cells/python-net/ar/aspose.cells.charts/seriescollection/category_data) | يحصل على نطاق قيم محور الفئة أو يعينها.<br/> يمكن أن يكون نطاقًا من الخلايا (مثل "d1:e10")،<br/> أو سلسلة من القيم (مثل، "{2،6،8،10}").|
| [second_category_data](/cells/python-net/ar/aspose.cells.charts/seriescollection/second_category_data) | يحصل على نطاق قيم المحور للفئة الثانية أو يعينها.<br/> يمكن أن يكون نطاقًا من الخلايا (مثل "d1:e10")،<br/> أو سلسلة من القيم (مثل، "{2،6،8،10}").<br/> التأثيرات فقط عندما يتم رسم بعض ASeries على المحور الثاني.|
| [is_color_varied](/cells/python-net/ar/aspose.cells.charts/seriescollection/is_color_varied) | يمثل ما إذا كان لون النقاط متنوعًا.|
| [capacity](/cells/python-net/ar/aspose.cells.charts/seriescollection/capacity) | يحصل على عدد العناصر التي يمكن أن تحتويها قائمة المصفوفة أو يعينها.|


###  طُرق
| طريقة| وصف|
| :- | :- |
| [`add(self, area, is_vertical)`](/cells/python-net/ar/aspose.cells.charts/seriescollection/add/#str-bool) | إضافة المجموعة [`Series`](/cells/python-net/ar/aspose.cells.charts/series) إلى الرسم البياني.|
| [`add(self, area, is_vertical, check_labels)`](/cells/python-net/ar/aspose.cells.charts/seriescollection/add/#str-bool-bool) | إضافة المجموعة [`Series`](/cells/python-net/ar/aspose.cells.charts/series) إلى الرسم البياني.|
| [`copy_to(self, array)`](/cells/python-net/ar/aspose.cells.charts/seriescollection/copy_to/#list) |يقوم بنسخ قائمة المصفوفة بأكملها إلى قائمة مصفوفة أحادية البعد متوافقة، بدءًا من بداية قائمة المصفوفة المستهدفة.|
| [`copy_to(self, index, array, array_index, count)`](/cells/python-net/ar/aspose.cells.charts/seriescollection/copy_to/#int-list-int-int) | يقوم بنسخ مجموعة من العناصر من قائمة المصفوفة إلى قائمة مصفوفة أحادية البعد متوافقة، بدءًا من الفهرس المحدد لقائمة المصفوفة المستهدفة.|
| [`index_of(self, item, index)`](/cells/python-net/ar/aspose.cells.charts/seriescollection/index_of/#aspose.cells.charts.series-int) | يبحث عن الكائن المحدد ويعيد الفهرس المبني على الصفر للظهور الأول ضمن نطاق العناصر في قائمة المصفوفة التي تمتد من الفهرس المحدد إلى العنصر الأخير.|
| [`index_of(self, item, index, count)`](/cells/python-net/ar/aspose.cells.charts/seriescollection/index_of/#aspose.cells.charts.series-int-int) | يبحث عن الكائن المحدد ويعيد الفهرس المبني على الصفر للظهور الأول ضمن نطاق العناصر في قائمة المصفوفة التي تبدأ بالفهرس المحدد وتحتوي على العدد المحدد من العناصر.|
| [`last_index_of(self, item)`](/cells/python-net/ar/aspose.cells.charts/seriescollection/last_index_of/#aspose.cells.charts.series) | يبحث عن الكائن المحدد ويعيد الفهرس المبني على الصفر للحدث الأخير ضمن قائمة المصفوفة بأكملها.|
| [`last_index_of(self, item, index)`](/cells/python-net/ar/aspose.cells.charts/seriescollection/last_index_of/#aspose.cells.charts.series-int) |يبحث عن الكائن المحدد ويعيد الفهرس المبني على الصفر للحدث الأخير ضمن نطاق العناصر في قائمة المصفوفة التي تمتد من العنصر الأول إلى الفهرس المحدد.|
| [`last_index_of(self, item, index, count)`](/cells/python-net/ar/aspose.cells.charts/seriescollection/last_index_of/#aspose.cells.charts.series-int-int) | يبحث عن الكائن المحدد ويعيد الفهرس المبدئي للصفر للحدث الأخير ضمن نطاق العناصر في قائمة المصفوفة التي تحتوي على عدد محدد من العناصر وتنتهي عند الفهرس المحدد.|
| [`get_series_by_order(self, order)`](/cells/python-net/ar/aspose.cells.charts/seriescollection/get_series_by_order/#int) | يحصل على العنصر [`Series`](/cells/python-net/ar/aspose.cells.charts/series) حسب الطلب.|
| [`change_series_order(self, source_index, dest_index)`](/cells/python-net/ar/aspose.cells.charts/seriescollection/change_series_order/#int-int) | يغير ترتيب السلسلتين بشكل مباشر.|
| [`swap_series(self, source_index, dest_index)`](/cells/python-net/ar/aspose.cells.charts/seriescollection/swap_series/#int-int) | يغير ترتيب السلسلتين بشكل مباشر.|
| [`set_series_names(self, start_index, area, is_vertical)`](/cells/python-net/ar/aspose.cells.charts/seriescollection/set_series_names/#int-str-bool) | تعيين اسم جميع السلاسل في الرسم البياني.|
| [`add_r1c1(self, area, is_vertical)`](/cells/python-net/ar/aspose.cells.charts/seriescollection/add_r1c1/#str-bool) | إضافة المجموعة [`Series`](/cells/python-net/ar/aspose.cells.charts/series) إلى الرسم البياني.|
| [`binary_search(self, item)`](/cells/python-net/ar/aspose.cells.charts/seriescollection/binary_search/#aspose.cells.charts.series) | يبحث في قائمة المصفوفة المفرزة بأكملها عن عنصر باستخدام المقارن الافتراضي ويعيد الفهرس المبني على الصفر للعنصر.|



###  مثال

```python
from aspose.cells import Workbook
from aspose.cells.charts import ChartType

# Instantiating a Workbook object
workbook = Workbook()
# Adding a new worksheet to the Excel object
sheetIndex = workbook.worksheets.add()
# Obtaining the reference of the newly added worksheet by passing its sheet index
worksheet = workbook.worksheets[sheetIndex]
# Adding a sample value to "A1" cell
worksheet.cells.get("A1").put_value(50)
# Adding a sample value to "A2" cell
worksheet.cells.get("A2").put_value(100)
# Adding a sample value to "A3" cell
worksheet.cells.get("A3").put_value(150)
# Adding a sample value to "A4" cell
worksheet.cells.get("A4").put_value(200)
# Adding a sample value to "B1" cell
worksheet.cells.get("B1").put_value(60)
# Adding a sample value to "B2" cell
worksheet.cells.get("B2").put_value(32)
# Adding a sample value to "B3" cell
worksheet.cells.get("B3").put_value(50)
# Adding a sample value to "B4" cell
worksheet.cells.get("B4").put_value(40)
# Adding a sample value to "C1" cell as category data
worksheet.cells.get("C1").put_value("Q1")
# Adding a sample value to "C2" cell as category data
worksheet.cells.get("C2").put_value("Q2")
# Adding a sample value to "C3" cell as category data
worksheet.cells.get("C3").put_value("Y1")
# Adding a sample value to "C4" cell as category data
worksheet.cells.get("C4").put_value("Y2")
# Adding a chart to the worksheet
chartIndex = worksheet.charts.add(ChartType.COLUMN, 5, 0, 15, 5)
# Accessing the instance of the newly added chart
chart = worksheet.charts[chartIndex]
# Adding NSeries (chart data source) to the chart ranging from "A1" cell to "B4"
chart.n_series.add("A1:B4", True)
# Setting the data source for the category data of NSeries
chart.n_series.category_data = "C1:C4"
# Saving the Excel file
workbook.save("book1.xls")

```

###  أنظر أيضا
* الوحدة [`aspose.cells.charts`](..)
* فئة [`Series`](/cells/python-net/ar/aspose.cells.charts/series)
