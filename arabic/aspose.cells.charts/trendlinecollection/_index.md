---
title: TrendlineCollection صف
second_title: Aspose.Cells for Python via .NET API المراجع
description:
type: docs
weight: 350
url: /ar/aspose.cells.charts/trendlinecollection/
is_root: false
---
##  TrendlineCollection صف
يمثل مجموعة من كافة الكائنات [`Trendline`](/cells/python-net/ar/aspose.cells.charts/trendline) لسلسلة البيانات المحددة.



يكشف النوع TrendlineCollection عن الأعضاء التاليين:

###  ملكيات
| ملكية| وصف|
| :- | :- |
| [capacity](/cells/python-net/ar/aspose.cells.charts/trendlinecollection/capacity) | الحصول على أو تعيين عدد العناصر التي يمكن أن تحتويها قائمة المصفوفة.|


###  طُرق
| طريقة| وصف|
| :- | :- |
| [add](/cells/python-net/ar/aspose.cells.charts/trendlinecollection/add/#aspose.cells.charts.TrendlineType) | يضيف كائن [`Trendline`](/cells/python-net/ar/aspose.cells.charts/trendline) إلى هذه المجموعة بالنوع المحدد.|
| [add](/cells/python-net/ar/aspose.cells.charts/trendlinecollection/add/#aspose.cells.charts.TrendlineType-str) | يضيف كائن [`Trendline`](/cells/python-net/ar/aspose.cells.charts/trendline) إلى هذه المجموعة بالنوع والاسم المحددين.|
| [copy_to](/cells/python-net/ar/aspose.cells.charts/trendlinecollection/copy_to/#list) | نسخ قائمة الصفيف بأكملها إلى قائمة صفيف أحادية البعد متوافقة، بدءًا من بداية قائمة الصفيف الهدف.|
| [copy_to](/cells/python-net/ar/aspose.cells.charts/trendlinecollection/copy_to/#int-list-int-int) | نسخ نطاق من العناصر من قائمة المصفوفات إلى قائمة مصفوفات متوافقة أحادية البعد، بدءًا من الفهرس المحدد لقائمة المصفوفات المستهدفة.|
| [index_of](/cells/python-net/ar/aspose.cells.charts/trendlinecollection/index_of/#aspose.cells.charts.Trendline-int) | يبحث عن الكائن المحدد ويعيد الفهرس الصفري للتواجد الأول ضمن نطاق العناصر في قائمة المصفوفة التي تمتد من الفهرس المحدد إلى العنصر الأخير.|
| [index_of](/cells/python-net/ar/aspose.cells.charts/trendlinecollection/index_of/#aspose.cells.charts.Trendline-int-int) |يبحث عن الكائن المحدد ويعيد الفهرس الصفري للتواجد الأول ضمن نطاق العناصر في قائمة المصفوفة التي تبدأ عند الفهرس المحدد وتحتوي على العدد المحدد من العناصر.|
| [last_index_of](/cells/python-net/ar/aspose.cells.charts/trendlinecollection/last_index_of/#aspose.cells.charts.Trendline) | يبحث عن الكائن المحدد ويعيد الفهرس الصفري للتواجد الأخير ضمن قائمة الصفيف بأكملها.|
| [last_index_of](/cells/python-net/ar/aspose.cells.charts/trendlinecollection/last_index_of/#aspose.cells.charts.Trendline-int) | يبحث عن الكائن المحدد ويعيد الفهرس الصفري للتواجد الأخير ضمن نطاق العناصر في قائمة المصفوفة التي تمتد من العنصر الأول إلى الفهرس المحدد.|
| [last_index_of](/cells/python-net/ar/aspose.cells.charts/trendlinecollection/last_index_of/#aspose.cells.charts.Trendline-int-int) | يبحث عن الكائن المحدد ويعيد الفهرس الصفري للتواجد الأخير ضمن نطاق العناصر في قائمة المصفوفة التي تحتوي على العدد المحدد من العناصر وينتهي عند الفهرس المحدد.|
| [binary_search](/cells/python-net/ar/aspose.cells.charts/trendlinecollection/binary_search/#aspose.cells.charts.Trendline) | يبحث في قائمة المصفوفات التي تم فرزها بالكامل عن عنصر باستخدام المقارن الافتراضي ويعيد الفهرس الصفري للعنصر.|



###  مثال

```python
from aspose.cells import Workbook
from aspose.cells.charts import ChartType, TrendlineType
from aspose.pydrawing import Color

# Instantiating a Workbook object
workbook = Workbook()
# Adding a new worksheet to the Excel object
sheetIndex = workbook.worksheets.add()
# Obtaining the reference of the newly added worksheet by passing its sheet index
worksheet = workbook.worksheets[sheetIndex]
worksheet.cells.get("A1").put_value(50)
worksheet.cells.get("A2").put_value(100)
worksheet.cells.get("A3").put_value(150)
worksheet.cells.get("A4").put_value(200)
worksheet.cells.get("B1").put_value(60)
worksheet.cells.get("B2").put_value(32)
worksheet.cells.get("B3").put_value(50)
worksheet.cells.get("B4").put_value(40)
# Adding a chart to the worksheet
chartIndex = workbook.worksheets[0].charts.add(ChartType.COLUMN, 3, 3, 15, 10)
chart = workbook.worksheets[0].charts[chartIndex]
chart.n_series.add("A1:a3", True)
chart.n_series[0].trend_lines.add(TrendlineType.LINEAR, "MyTrendLine")
line = chart.n_series[0].trend_lines[0]
line.display_equation = True
line.display_r_squared = True
line.color = Color.red

```

###  أنظر أيضا
* الوحدة [`aspose.cells.charts`](..)
* فئة [`Trendline`](/cells/python-net/ar/aspose.cells.charts/trendline)
