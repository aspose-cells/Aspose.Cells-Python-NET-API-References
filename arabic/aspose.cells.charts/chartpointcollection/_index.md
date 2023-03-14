---
title: ChartPointCollection الدرجة
second_title: Aspose.Cells for Python via .NET API المراجع
description:
type: docs
weight: 100
url: /ar/aspose.cells.charts/chartpointcollection/
is_root: false
---
##  ChartPointCollection الدرجة
يمثل مجموعة تحتوي على جميع النقاط في سلسلة واحدة.



يكشف نوع ChartPointCollection الأعضاء التالية:

###  ملكيات
| ملكية| وصف|
| :- | :- |
| [count](/cells/python-net/ar/aspose.cells.charts/chartpointcollection/count) | يحصل على عدد نقاط الرسم البياني.|



الحصول على عنصر [ChartPoint](/cells/python-net/ar/aspose.cells.charts/chartpoint) بالفهرس المحدد في السلسلة.
###  مفهرس
| اسم| وصف|
| :- | :- |
| [index] | مؤشر نقطة الرسم البياني في السلسلة.|


###  طُرق
| طريقة| وصف|
| :- | :- |
| [get_enumerator()](/cells/python-net/ar/aspose.cells.charts/chartpointcollection/get_enumerator/#) | إرجاع عداد لكامل [ChartPointCollection](/cells/python-net/ar/aspose.cells.charts/chartpointcollection).|
| [clear()](/cells/python-net/ar/aspose.cells.charts/chartpointcollection/clear/#) | قم بإزالة كل إعدادات نقاط الرسم البياني.|
| [remove_at(index)](/cells/python-net/ar/aspose.cells.charts/chartpointcollection/remove_at/#int) | يزيل النقطة في فهرس السلسلة ..|



###  مثال

```python
from aspose.cells import Workbook
from aspose.cells.charts import ChartType
from aspose.pydrawing import Color

# Instantiating a Workbook object
workbook = Workbook()
# Obtaining the reference of the first worksheet
worksheet = workbook.worksheets[0]
# Adding a sample value to "A1" cell
worksheet.cells.get("A1").put_value(50)
# Adding a sample value to "A2" cell
worksheet.cells.get("A2").put_value(100)
# Adding a sample value to "A3" cell
worksheet.cells.get("A3").put_value(150)
# Adding a sample value to "B1" cell
worksheet.cells.get("B1").put_value(60)
# Adding a sample value to "B2" cell
worksheet.cells.get("B2").put_value(32)
# Adding a sample value to "B3" cell
worksheet.cells.get("B3").put_value(50)
# Adding a chart to the worksheet
chartIndex = worksheet.charts.add(ChartType.PIE_EXPLODED, 5, 0, 25, 10)
# Accessing the instance of the newly added chart
chart = worksheet.charts[chartIndex]
# Adding NSeries (chart data source) to the chart ranging from "A1" cell to "B3"
chart.n_series.add("A1:B3", True)
# Show Data Labels
chart.n_series[0].data_labels.show_value = True
points = chart.n_series[0].points
for i in range(points.count):
    # Get Data Point
    point = points[i]
    # Set Pir Explosion
    point.explosion = 15
    # Set Border Color
    point.border.color = Color.red
# Saving the Excel file
workbook.save("book1.xls")

```

###  أنظر أيضا
* وحدة [aspose.cells.charts](..)
* فئة [ChartPoint](/cells/python-net/ar/aspose.cells.charts/chartpoint)
* فئة [ChartPointCollection](/cells/python-net/ar/aspose.cells.charts/chartpointcollection)
