---
title: FillFormat صف
second_title: Aspose.Cells for Python via .NET API المراجع
description:
type: docs
weight: 170
url: /ar/aspose.cells.drawing/fillformat/
is_root: false
---
##  FillFormat صف
يقوم بتغليف الكائن الذي يمثل تنسيق التعبئة لشكل ما.



يكشف النوع FillFormat عن الأعضاء التاليين:

###  ملكيات
| ملكية| وصف|
| :- | :- |
| [type](/cells/python-net/ar/aspose.cells.drawing/fillformat/type) | يحصل على نوع التعبئة ويحدده.|
| [fill_type](/cells/python-net/ar/aspose.cells.drawing/fillformat/fill_type) | يحصل على نوع التعبئة ويحدده|
| [transparency](/cells/python-net/ar/aspose.cells.drawing/fillformat/transparency) |يقوم بإرجاع أو تعيين درجة شفافية المنطقة كقيمة من 0.0 (غير شفافة) إلى 1.0 (واضحة).|
| [set_type](/cells/python-net/ar/aspose.cells.drawing/fillformat/set_type) | يحصل على نوع مجموعة تنسيق التعبئة.|
| [gradient_fill](/cells/python-net/ar/aspose.cells.drawing/fillformat/gradient_fill) | يحصل على الكائن [`FillFormat.gradient_fill`](/cells/python-net/ar/aspose.cells.drawing/fillformat#gradient_fill).|
| [texture_fill](/cells/python-net/ar/aspose.cells.drawing/fillformat/texture_fill) | يحصل على الكائن [`FillFormat.texture_fill`](/cells/python-net/ar/aspose.cells.drawing/fillformat#texture_fill).|
| [solid_fill](/cells/python-net/ar/aspose.cells.drawing/fillformat/solid_fill) | يحصل على الكائن [`FillFormat.solid_fill`](/cells/python-net/ar/aspose.cells.drawing/fillformat#solid_fill).|
| [pattern_fill](/cells/python-net/ar/aspose.cells.drawing/fillformat/pattern_fill) | يحصل على الكائن [`FillFormat.pattern_fill`](/cells/python-net/ar/aspose.cells.drawing/fillformat#pattern_fill).|
| [gradient_color_type](/cells/python-net/ar/aspose.cells.drawing/fillformat/gradient_color_type) | إرجاع نوع لون التدرج للتعبئة المحددة.|
| [gradient_style](/cells/python-net/ar/aspose.cells.drawing/fillformat/gradient_style) | إرجاع نمط التدرج للتعبئة المحددة.|
| [gradient_color1](/cells/python-net/ar/aspose.cells.drawing/fillformat/gradient_color1) | إرجاع لون التدرج 1 للتعبئة المحددة.|
| [gradient_color2](/cells/python-net/ar/aspose.cells.drawing/fillformat/gradient_color2) |إرجاع لون التدرج 2 للتعبئة المحددة.|
| [gradient_degree](/cells/python-net/ar/aspose.cells.drawing/fillformat/gradient_degree) | إرجاع درجة التدرج للتعبئة المحددة.<br/> ينطبق فقط على Excel 2007.|
| [gradient_variant](/cells/python-net/ar/aspose.cells.drawing/fillformat/gradient_variant) | إرجاع متغير التدرج للتعبئة المحددة.<br/> ينطبق فقط على Excel 2007.|
| [preset_color](/cells/python-net/ar/aspose.cells.drawing/fillformat/preset_color) | إرجاع لون التدرج المحدد مسبقًا للتعبئة المحددة.|
| [texture](/cells/python-net/ar/aspose.cells.drawing/fillformat/texture) | يمثل نوع الملمس للتعبئة المحددة.|
| [pattern](/cells/python-net/ar/aspose.cells.drawing/fillformat/pattern) | يمثل نمط عرض المنطقة.|
| [picture_format_type](/cells/python-net/ar/aspose.cells.drawing/fillformat/picture_format_type) | يحصل على نوع تنسيق الصورة ويحدده.|
| [scale](/cells/python-net/ar/aspose.cells.drawing/fillformat/scale) | يحصل على مقياس تنسيق الصورة ويضبطه.|
| [image_data](/cells/python-net/ar/aspose.cells.drawing/fillformat/image_data) | يحصل على بيانات الصورة ويقوم بتعيينها.|


###  طُرق
| طريقة| وصف|
| :- | :- |
| [`set_two_color_gradient(self, color1, color2, style, variant)`](/cells/python-net/ar/aspose.cells.drawing/fillformat/set_two_color_gradient/#aspose.pydrawing.color-aspose.pydrawing.color-aspose.cells.drawing.gradientstyletype-int) | تعيين التعبئة المحددة إلى تدرج لوني ثنائي اللون.<br/> ينطبق فقط على Excel 2007.|
| [`set_two_color_gradient(self, color1, transparency1, color2, transparency2, style, variant)`](/cells/python-net/ar/aspose.cells.drawing/fillformat/set_two_color_gradient/#aspose.pydrawing.color-float-aspose.pydrawing.color-float-aspose.cells.drawing.gradientstyletype-int) | تعيين التعبئة المحددة إلى تدرج لوني ثنائي اللون.<br/> ينطبق فقط على Excel 2007.|
| [`set_one_color_gradient(self, color, degree, style, variant)`](/cells/python-net/ar/aspose.cells.drawing/fillformat/set_one_color_gradient/#aspose.pydrawing.color-float-aspose.cells.drawing.gradientstyletype-int) | تعيين التعبئة المحددة إلى تدرج لوني أحادي اللون.<br/> ينطبق فقط على Excel 2007.|
| [`set_preset_color_gradient(self, preset_color, style, variant)`](/cells/python-net/ar/aspose.cells.drawing/fillformat/set_preset_color_gradient/#aspose.cells.drawing.gradientpresettype-aspose.cells.drawing.gradientstyletype-int) | تعيين التعبئة المحددة إلى تدرج لوني محدد مسبقًا.<br/> ينطبق فقط على Excel 2007.|



###  مثال

```python
from aspose.cells import Workbook
from aspose.cells.charts import ChartType
from aspose.cells.drawing import GradientStyleType
from aspose.pydrawing import Color

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
seriesIndex = chart.n_series.add("A1:B4", True)
# Setting the data source for the category data of NSeries
chart.n_series.category_data = "C1:C4"
# Filling the area of the 2nd NSeries with a gradient
chart.n_series[seriesIndex].area.fill_format.set_one_color_gradient(Color.lime, 1, GradientStyleType.HORIZONTAL, 1)

```

###  أنظر أيضا
* الوحدة [`aspose.cells.drawing`](..)
