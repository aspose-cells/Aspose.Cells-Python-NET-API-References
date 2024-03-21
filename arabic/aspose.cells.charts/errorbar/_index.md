---
title: ErrorBar صف
second_title: Aspose.Cells for Python via .NET API المراجع
description:
type: docs
weight: 160
url: /ar/aspose.cells.charts/errorbar/
is_root: false
---
##  ErrorBar صف
يمثل شريط الخطأ لسلسلة البيانات.



**ميراث:** [`ErrorBar`](/cells/python-net/aspose.cells.charts/errorbar) → 
[`Line`](/cells/python-net/ar/aspose.cells.drawing/line)



يكشف النوع ErrorBar عن الأعضاء التاليين:

###  ملكيات
| ملكية| وصف|
| :- | :- |
| [compound_type](/cells/python-net/ar/aspose.cells.charts/errorbar/compound_type) | يحدد نوع الخط المركب|
| [dash_type](/cells/python-net/ar/aspose.cells.charts/errorbar/dash_type) | يحدد نوع الخط المتقطع|
| [cap_type](/cells/python-net/ar/aspose.cells.charts/errorbar/cap_type) |يحدد قبعات النهاية.|
| [join_type](/cells/python-net/ar/aspose.cells.charts/errorbar/join_type) | يحدد قبعات الانضمام.|
| [begin_type](/cells/python-net/ar/aspose.cells.charts/errorbar/begin_type) | يحدد رأس سهم لبداية السطر.|
| [end_type](/cells/python-net/ar/aspose.cells.charts/errorbar/end_type) | يحدد رأس سهم لنهاية السطر.|
| [begin_arrow_length](/cells/python-net/ar/aspose.cells.charts/errorbar/begin_arrow_length) | يحدد طول رأس السهم لبداية السطر.|
| [end_arrow_length](/cells/python-net/ar/aspose.cells.charts/errorbar/end_arrow_length) | يحدد طول رأس السهم لنهاية السطر.|
| [begin_arrow_width](/cells/python-net/ar/aspose.cells.charts/errorbar/begin_arrow_width) | يحدد عرض رأس السهم لبداية السطر.|
| [end_arrow_width](/cells/python-net/ar/aspose.cells.charts/errorbar/end_arrow_width) | يحدد عرض رأس السهم لنهاية السطر.|
| [theme_color](/cells/python-net/ar/aspose.cells.charts/errorbar/theme_color) | الحصول على لون السمة وتعيينه.|
| [color](/cells/python-net/ar/aspose.cells.charts/errorbar/color) | يمثل لون الخط.|
| [transparency](/cells/python-net/ar/aspose.cells.charts/errorbar/transparency) | إرجاع أو تعيين درجة شفافية الخط كقيمة تتراوح من 0.0 (معتم) إلى 1.0 (واضح).|
| [style](/cells/python-net/ar/aspose.cells.charts/errorbar/style) | يمثل نمط الخط.|
| [weight](/cells/python-net/ar/aspose.cells.charts/errorbar/weight) | الحصول على أو تعيين [`WeightType`](/cells/python-net/ar/aspose.cells.drawing/weighttype) من السطر.|
| [weight_pt](/cells/python-net/ar/aspose.cells.charts/errorbar/weight_pt) | الحصول على أو تعيين وزن الخط بوحدة النقاط.|
| [weight_px](/cells/python-net/ar/aspose.cells.charts/errorbar/weight_px) | الحصول على أو تعيين وزن الخط بوحدة البكسل.|
| [formatting_type](/cells/python-net/ar/aspose.cells.charts/errorbar/formatting_type) | الحصول على نوع التنسيق أو تحديده.|
| [is_automatic_color](/cells/python-net/ar/aspose.cells.charts/errorbar/is_automatic_color) | يشير إلى ما إذا كان لون الخط قد تم تعيينه تلقائيًا.|
| [is_visible](/cells/python-net/ar/aspose.cells.charts/errorbar/is_visible) | يمثل ما إذا كان الخط مرئيًا.|
| [is_auto](/cells/python-net/ar/aspose.cells.charts/errorbar/is_auto) |يشير إلى ما إذا كان نمط الخط هذا قد تم تعيينه تلقائيًا.|
| [gradient_fill](/cells/python-net/ar/aspose.cells.charts/errorbar/gradient_fill) | يمثل تعبئة متدرجة.|
| [type](/cells/python-net/ar/aspose.cells.charts/errorbar/type) | يمثل نوع مبلغ شريط الخطأ.|
| [display_type](/cells/python-net/ar/aspose.cells.charts/errorbar/display_type) | يمثل نوع عرض شريط الخطأ.|
| [amount](/cells/python-net/ar/aspose.cells.charts/errorbar/amount) | يمثل مقدار شريط الخطأ.<br/> يجب أن يكون المبلغ أكبر من أو يساوي الصفر.|
| [show_marker_t_top](/cells/python-net/ar/aspose.cells.charts/errorbar/show_marker_t_top) | يشير إلى ما إذا كانت هناك أشرطة خطأ في التنسيق باستخدام T-top.|
| [plus_value](/cells/python-net/ar/aspose.cells.charts/errorbar/plus_value) | يمثل مقدار خطأ موجبًا عندما يكون نوع شريط الخطأ مخصصًا.|
| [minus_value](/cells/python-net/ar/aspose.cells.charts/errorbar/minus_value) | يمثل مقدار خطأ سالبًا عندما يكون نوع شريط الخطأ مخصصًا.|



###  مثال

```python
from aspose.cells import Workbook
from aspose.cells.charts import ChartType, ErrorBarDisplayType, ErrorBarType

workbook = Workbook()
cells = workbook.worksheets[0].cells
cells.get("a1").put_value(2)
cells.get("a2").put_value(5)
cells.get("a3").put_value(3)
cells.get("a4").put_value(6)
cells.get("b1").put_value(4)
cells.get("b2").put_value(3)
cells.get("b3").put_value(6)
cells.get("b4").put_value(7)
cells.get("C1").put_value("Q1")
cells.get("C2").put_value("Q2")
cells.get("C3").put_value("Y1")
cells.get("C4").put_value("Y2")
chartIndex = workbook.worksheets[0].charts.add(ChartType.COLUMN, 11, 0, 27, 10)
chart = workbook.worksheets[0].charts[chartIndex]
chart.n_series.add("A1:B4", True)
chart.n_series.category_data = "C1:C4"
for i in range(len(chart.n_series)):
    aseries = chart.n_series[i]
    aseries.y_error_bar.display_type = ErrorBarDisplayType.MINUS
    aseries.y_error_bar.type = ErrorBarType.FIXED_VALUE
    aseries.y_error_bar.amount = 5.0

```

###  أنظر أيضا
* الوحدة [`aspose.cells.charts`](..)
* فئة [`ErrorBar`](/cells/python-net/ar/aspose.cells.charts/errorbar)
* فئة [`Line`](/cells/python-net/ar/aspose.cells.drawing/line)
* فئة [`WeightType`](/cells/python-net/ar/aspose.cells.drawing/weighttype)
