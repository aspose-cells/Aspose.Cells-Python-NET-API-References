---
title: Floor صف
second_title: Aspose.Cells for Python via .NET API المراجع
description:
type: docs
weight: 170
url: /ar/aspose.cells.charts/floor/
is_root: false
---
##  Floor صف
يقوم بتغليف الكائن الذي يمثل أرضية الرسم البياني ثلاثي الأبعاد.



**الميراث:** [`Floor`](/cells/python-net/aspose.cells.charts/floor) → 
[`Area`](/cells/python-net/ar/aspose.cells.drawing/area)



يكشف النوع Floor عن الأعضاء التاليين:

###  ملكيات
| ملكية| وصف|
| :- | :- |
| [background_color](/cells/python-net/ar/aspose.cells.charts/floor/background_color) | يحصل على لون الخلفية لـ [`Area`](/cells/python-net/ar/aspose.cells.drawing/area) أو يعينه.|
| [foreground_color](/cells/python-net/ar/aspose.cells.charts/floor/foreground_color) | يحصل على لون المقدمة أو يعينه.|
| [formatting](/cells/python-net/ar/aspose.cells.charts/floor/formatting) | يمثل تنسيق المنطقة.|
| [invert_if_negative](/cells/python-net/ar/aspose.cells.charts/floor/invert_if_negative) | إذا كانت الخاصية صحيحة وكانت قيمة نقطة الرسم البياني رقمًا سلبيًا،<br/> سيتم تبادل لون المقدمة ولون الخلفية.|
| [fill_format](/cells/python-net/ar/aspose.cells.charts/floor/fill_format) | يمثل كائن [`Area.fill_format`](/cells/python-net/ar/aspose.cells.drawing/area#fill_format) يحتوي على خصائص تنسيق التعبئة للمخطط أو الشكل المحدد.|
| [transparency](/cells/python-net/ar/aspose.cells.charts/floor/transparency) |يقوم بإرجاع أو تعيين درجة شفافية المنطقة كقيمة من 0.0 (غير شفافة) إلى 1.0 (واضحة).|
| [border](/cells/python-net/ar/aspose.cells.charts/floor/border) | يحصل على الحدود [`Line`](/cells/python-net/ar/aspose.cells.drawing/line) أو يعينها.|



###  مثال

```python
from aspose.cells import License, Workbook
from aspose.cells.charts import ChartType
from aspose.cells.drawing import GradientPresetType, GradientStyleType
from aspose.pydrawing import Color

# Instantiate the License class
license = License()
# Pass only the name of the license file embedded in the assembly
license.set_license("Aspose.Cells.lic")
# Instantiate the workbook object
workbook = Workbook()
# Get cells collection
cells = workbook.worksheets[0].cells
# Put values in cells
cells.get("A1").put_value(1)
cells.get("A2").put_value(2)
cells.get("A3").put_value(3)
# get charts colletion
charts = workbook.worksheets[0].charts
# add a new chart
index = charts.add(ChartType.COLUMN_3D_STACKED, 5, 0, 15, 5)
# get the newly added chart
chart = charts[index]
# set charts nseries
chart.n_series.add("A1:A3", True)
# Show data labels
chart.n_series[0].data_labels.show_value = True
# Get chart's floor
floor = chart.floor
# set floor's border as red
floor.border.color = Color.red
# set fill format
floor.fill_format.set_preset_color_gradient(GradientPresetType.CALM_WATER, GradientStyleType.DIAGONAL_DOWN, 2)
# save the file
workbook.save(r"dest.xls")

```

###  أنظر أيضا
* الوحدة [`aspose.cells.charts`](..)
* فئة [`Area`](/cells/python-net/ar/aspose.cells.drawing/area)
* فئة [`Floor`](/cells/python-net/ar/aspose.cells.charts/floor)
* فئة [`Line`](/cells/python-net/ar/aspose.cells.drawing/line)
