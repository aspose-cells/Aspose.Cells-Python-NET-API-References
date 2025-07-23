---
title: invert_if_negative عقار
second_title: Aspose.Cells for Python via .NET API المراجع
description:
type: docs
weight: 70
url: /ar/aspose.cells.drawing/area/invert_if_negative/
is_root: false
---
##  invert_if_negative عقار

إذا كانت الخاصية صحيحة وكانت قيمة نقطة الرسم البياني رقمًا سلبيًا،
سيتم تبادل لون المقدمة ولون الخلفية.

###  مثال

```python
from aspose.cells import Workbook
from aspose.cells.charts import ChartType
from aspose.pydrawing import Color

# Instantiating a Workbook object
workbook = Workbook()
# Adding a new worksheet to the Workbook object
sheetIndex = workbook.worksheets.add()
# Obtaining the reference of the newly added worksheet by passing its sheet index
worksheet = workbook.worksheets[sheetIndex]
# Adding a sample value to "A1" cell
worksheet.cells.get("A1").put_value(50)
# Adding a sample value to "A2" cell
worksheet.cells.get("A2").put_value(-100)
# Adding a sample value to "A3" cell
worksheet.cells.get("A3").put_value(150)
# Adding a chart to the worksheet
chartIndex = worksheet.charts.add(ChartType.COLUMN, 5, 0, 15, 5)
# Accessing the instance of the newly added chart
chart = worksheet.charts[chartIndex]
# Adding NSeries (chart data source) to the chart ranging from "A1" cell to "A3"
chart.n_series.add("A1:A3", True)
chart.n_series[0].area.invert_if_negative = True
# Setting the foreground color of the 1st NSeries area
chart.n_series[0].area.foreground_color = Color.red
# Setting the background color of the 1st NSeries area.
# The displayed area color of second chart point will be the background color.
chart.n_series[0].area.background_color = Color.yellow
# Saving the Excel file
workbook.save("book1.xls")

```
###  تعريف:
```python
@property
def invert_if_negative(self):
    ...
@invert_if_negative.setter
def invert_if_negative(self, value):
    ...
```

###  أنظر أيضا
* الوحدة [`aspose.cells.drawing`](../../)
* فئة [`Area`](/cells/python-net/ar/aspose.cells.drawing/area)
