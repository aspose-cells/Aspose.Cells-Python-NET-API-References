---
title: Line صف
second_title: Aspose.Cells for Python via .NET API المراجع
description:
type: docs
weight: 270
url: /ar/aspose.cells.drawing/line/
is_root: false
---
##  Line صف
يقوم بتغليف الكائن الذي يمثل تنسيق الخط.



يكشف النوع Line عن الأعضاء التاليين:

###  ملكيات
| ملكية| وصف|
| :- | :- |
| [compound_type](/cells/python-net/ar/aspose.cells.drawing/line/compound_type) | يحدد نوع الخط المركب|
| [dash_type](/cells/python-net/ar/aspose.cells.drawing/line/dash_type) | يحدد نوع خط الشرطة|
| [cap_type](/cells/python-net/ar/aspose.cells.drawing/line/cap_type) | يحدد الأحرف الكبيرة النهائية.|
| [join_type](/cells/python-net/ar/aspose.cells.drawing/line/join_type) | يحدد حدود الانضمام.|
| [begin_type](/cells/python-net/ar/aspose.cells.drawing/line/begin_type) | يحدد رأس السهم لبداية الخط.|
| [end_type](/cells/python-net/ar/aspose.cells.drawing/line/end_type) | يحدد رأس السهم لنهاية السطر.|
| [begin_arrow_length](/cells/python-net/ar/aspose.cells.drawing/line/begin_arrow_length) | يقوم بتحديد طول رأس السهم لبداية الخط.|
| [end_arrow_length](/cells/python-net/ar/aspose.cells.drawing/line/end_arrow_length) | يحدد طول رأس السهم لنهاية الخط.|
| [begin_arrow_width](/cells/python-net/ar/aspose.cells.drawing/line/begin_arrow_width) | يقوم بتحديد عرض رأس السهم لبداية الخط.|
| [end_arrow_width](/cells/python-net/ar/aspose.cells.drawing/line/end_arrow_width) | يحدد عرض رأس السهم لنهاية الخط.|
| [theme_color](/cells/python-net/ar/aspose.cells.drawing/line/theme_color) | يحصل على لون السمة ويحدده.|
| [color](/cells/python-net/ar/aspose.cells.drawing/line/color) | يمثل لون الخط.|
| [transparency](/cells/python-net/ar/aspose.cells.drawing/line/transparency) | يقوم بإرجاع أو تعيين درجة شفافية الخط كقيمة من 0.0 (غير شفاف) إلى 1.0 (واضح).|
| [style](/cells/python-net/ar/aspose.cells.drawing/line/style) | يمثل أسلوب الخط.|
| [weight](/cells/python-net/ar/aspose.cells.drawing/line/weight) | يحصل على أو يعين [`WeightType`](/cells/python-net/ar/aspose.cells.drawing/weighttype) من السطر.|
| [weight_pt](/cells/python-net/ar/aspose.cells.drawing/line/weight_pt) |يحصل على أو يحدد وزن الخط بوحدة النقاط.|
| [weight_px](/cells/python-net/ar/aspose.cells.drawing/line/weight_px) | يحصل على أو يضبط وزن الخط بوحدة البكسل.|
| [formatting_type](/cells/python-net/ar/aspose.cells.drawing/line/formatting_type) | يحصل على نوع التنسيق أو يعينه.|
| [is_automatic_color](/cells/python-net/ar/aspose.cells.drawing/line/is_automatic_color) | يشير إلى ما إذا كان لون الخط يتم تعيينه تلقائيًا.|
| [is_visible](/cells/python-net/ar/aspose.cells.drawing/line/is_visible) | يمثل ما إذا كان الخط مرئيًا أم لا.|
| [is_auto](/cells/python-net/ar/aspose.cells.drawing/line/is_auto) | يشير إلى ما إذا كان نمط الخط هذا يتم تعيينه تلقائيًا.|
| [gradient_fill](/cells/python-net/ar/aspose.cells.drawing/line/gradient_fill) | يمثل تعبئة التدرج.|



###  مثال

```python
from aspose.cells import Workbook
from aspose.cells.charts import ChartMarkerType, ChartType
from aspose.cells.drawing import LineType, WeightType
from aspose.pydrawing import Color

workbook = Workbook()
sheet = workbook.worksheets[0]
cells = sheet.cells
cells.get(0, 1).put_value("Income")
cells.get(1, 0).put_value("Company A")
cells.get(2, 0).put_value("Company B")
cells.get(3, 0).put_value("Company C")
cells.get(1, 1).put_value(10000)
cells.get(2, 1).put_value(20000)
cells.get(3, 1).put_value(30000)
chartIndex = sheet.charts.add(ChartType.LINE, 9, 9, 21, 15)
chart = sheet.charts[chartIndex]
# Add series
chart.n_series.add("A2:B4", True)
# Set category data
chart.n_series.category_data = "=Sheet1!$A$2:$A$4"
# Applying a dotted line style on the lines of an NSeries
chart.n_series[0].border.style = LineType.DOT
chart.n_series[0].border.color = Color.red
# Applying a triangular marker style on the data markers of an NSeries
chart.n_series[0].marker.marker_style = ChartMarkerType.TRIANGLE
# Setting the weight of all lines in an NSeries to medium
chart.n_series[0].border.weight = WeightType.MEDIUM_LINE

```

###  أنظر أيضا
* الوحدة [`aspose.cells.drawing`](..)
* فئة [`WeightType`](/cells/python-net/ar/aspose.cells.drawing/weighttype)
