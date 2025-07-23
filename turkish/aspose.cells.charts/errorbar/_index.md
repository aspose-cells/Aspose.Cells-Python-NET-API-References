---
title: ErrorBar sınıfı
second_title: Aspose.Cells for Python via .NET API Referanslar
description:
type: docs
weight: 160
url: /tr/aspose.cells.charts/errorbar/
is_root: false
---
##  ErrorBar sınıfı
Veri serisinin hata çubuğunu temsil eder.



**Miras:** [`ErrorBar`](/cells/python-net/aspose.cells.charts/errorbar) → 
[`Line`](/cells/python-net/tr/aspose.cells.drawing/line)



ErrorBar türü aşağıdaki üyeleri ortaya çıkarır:

###  Özellikler
| Mülk| Tanım|
| :- | :- |
| [compound_type](/cells/python-net/tr/aspose.cells.charts/errorbar/compound_type) | Bileşik satır türünü belirtir|
| [dash_type](/cells/python-net/tr/aspose.cells.charts/errorbar/dash_type) | Kesik çizgi türünü belirtir|
| [cap_type](/cells/python-net/tr/aspose.cells.charts/errorbar/cap_type) | Son harfleri belirtir.|
| [join_type](/cells/python-net/tr/aspose.cells.charts/errorbar/join_type) | Birleştirme kapaklarını belirtir.|
| [begin_type](/cells/python-net/tr/aspose.cells.charts/errorbar/begin_type) | Bir satırın başlangıcı için bir ok ucu belirtir.|
| [end_type](/cells/python-net/tr/aspose.cells.charts/errorbar/end_type) | Bir satırın sonu için bir ok ucu belirtir.|
| [begin_arrow_length](/cells/python-net/tr/aspose.cells.charts/errorbar/begin_arrow_length) | Bir çizginin başlangıcındaki ok ucunun uzunluğunu belirtir.|
| [end_arrow_length](/cells/python-net/tr/aspose.cells.charts/errorbar/end_arrow_length) | Bir satırın sonundaki ok ucunun uzunluğunu belirtir.|
| [begin_arrow_width](/cells/python-net/tr/aspose.cells.charts/errorbar/begin_arrow_width) | Bir çizginin başlangıcındaki ok ucunun genişliğini belirtir.|
| [end_arrow_width](/cells/python-net/tr/aspose.cells.charts/errorbar/end_arrow_width) | Bir satırın sonundaki ok ucunun genişliğini belirtir.|
| [theme_color](/cells/python-net/tr/aspose.cells.charts/errorbar/theme_color) | Tema rengini alır ve ayarlar.|
| [color](/cells/python-net/tr/aspose.cells.charts/errorbar/color) | Çizginin rengini temsil eder.|
| [transparency](/cells/python-net/tr/aspose.cells.charts/errorbar/transparency) | Çizginin şeffaflık derecesini 0,0 (opak) ile 1,0 (temiz) arasında bir değer olarak döndürür veya ayarlar.|
| [style](/cells/python-net/tr/aspose.cells.charts/errorbar/style) | Çizginin tarzını temsil eder.|
| [weight](/cells/python-net/tr/aspose.cells.charts/errorbar/weight) | Satırın [`WeightType`](/cells/python-net/tr/aspose.cells.drawing/weighttype) değerini alır veya ayarlar.|
| [weight_pt](/cells/python-net/tr/aspose.cells.charts/errorbar/weight_pt) |Çizginin ağırlığını nokta biriminde alır veya ayarlar.|
| [weight_px](/cells/python-net/tr/aspose.cells.charts/errorbar/weight_px) | Çizginin kalınlığını piksel cinsinden alır veya ayarlar.|
| [formatting_type](/cells/python-net/tr/aspose.cells.charts/errorbar/formatting_type) | Biçim türünü alır veya ayarlar.|
| [is_automatic_color](/cells/python-net/tr/aspose.cells.charts/errorbar/is_automatic_color) | Çizginin renginin otomatik olarak atanıp atanmadığını belirtir.|
| [is_visible](/cells/python-net/tr/aspose.cells.charts/errorbar/is_visible) | Çizginin görünür olup olmadığını gösterir.|
| [is_auto](/cells/python-net/tr/aspose.cells.charts/errorbar/is_auto) | Bu çizgi stilinin otomatik olarak atanıp atanmadığını belirtir.|
| [gradient_fill](/cells/python-net/tr/aspose.cells.charts/errorbar/gradient_fill) | Degrade dolguyu temsil eder.|
| [type](/cells/python-net/tr/aspose.cells.charts/errorbar/type) | Hata çubuğu miktar türünü temsil eder.|
| [display_type](/cells/python-net/tr/aspose.cells.charts/errorbar/display_type) | Hata çubuğunun görüntülenme türünü temsil eder.|
| [amount](/cells/python-net/tr/aspose.cells.charts/errorbar/amount) | Hata çubuğunun miktarını temsil eder.|
| [show_marker_t_top](/cells/python-net/tr/aspose.cells.charts/errorbar/show_marker_t_top) | Biçimlendirme hatası çubuklarının T-üst ile gösterildiğini belirtir.|
| [plus_value](/cells/python-net/tr/aspose.cells.charts/errorbar/plus_value) | Hata çubuğu türü Özel olduğunda pozitif hata miktarını temsil eder.|
| [minus_value](/cells/python-net/tr/aspose.cells.charts/errorbar/minus_value) | Hata çubuğu türü Özel olduğunda negatif hata miktarını temsil eder.|



###  Örnek

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

###  Ayrıca bakınız
* modül [`aspose.cells.charts`](..)
* sınıf [`ErrorBar`](/cells/python-net/tr/aspose.cells.charts/errorbar)
* sınıf [`Line`](/cells/python-net/tr/aspose.cells.drawing/line)
* sınıf [`WeightType`](/cells/python-net/tr/aspose.cells.drawing/weighttype)
