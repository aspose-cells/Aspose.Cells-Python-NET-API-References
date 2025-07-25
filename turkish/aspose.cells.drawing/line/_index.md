---
title: Line sınıfı
second_title: Aspose.Cells for Python via .NET API Referanslar
description:
type: docs
weight: 270
url: /tr/aspose.cells.drawing/line/
is_root: false
---
##  Line sınıfı
Satır biçimini temsil eden nesneyi kapsüller.



Line türü aşağıdaki üyeleri ortaya çıkarır:

###  Özellikler
| Mülk| Tanım|
| :- | :- |
| [compound_type](/cells/python-net/tr/aspose.cells.drawing/line/compound_type) | Bileşik satır türünü belirtir|
| [dash_type](/cells/python-net/tr/aspose.cells.drawing/line/dash_type) | Kesik çizgi türünü belirtir|
| [cap_type](/cells/python-net/tr/aspose.cells.drawing/line/cap_type) | Son harfleri belirtir.|
| [join_type](/cells/python-net/tr/aspose.cells.drawing/line/join_type) | Birleştirme kapaklarını belirtir.|
| [begin_type](/cells/python-net/tr/aspose.cells.drawing/line/begin_type) | Bir satırın başlangıcı için bir ok ucu belirtir.|
| [end_type](/cells/python-net/tr/aspose.cells.drawing/line/end_type) | Bir satırın sonu için bir ok ucu belirtir.|
| [begin_arrow_length](/cells/python-net/tr/aspose.cells.drawing/line/begin_arrow_length) | Bir çizginin başlangıcındaki ok ucunun uzunluğunu belirtir.|
| [end_arrow_length](/cells/python-net/tr/aspose.cells.drawing/line/end_arrow_length) | Bir satırın sonundaki ok ucunun uzunluğunu belirtir.|
| [begin_arrow_width](/cells/python-net/tr/aspose.cells.drawing/line/begin_arrow_width) | Bir çizginin başlangıcındaki ok ucunun genişliğini belirtir.|
| [end_arrow_width](/cells/python-net/tr/aspose.cells.drawing/line/end_arrow_width) | Bir satırın sonundaki ok ucunun genişliğini belirtir.|
| [theme_color](/cells/python-net/tr/aspose.cells.drawing/line/theme_color) | Tema rengini alır ve ayarlar.|
| [color](/cells/python-net/tr/aspose.cells.drawing/line/color) | Çizginin rengini temsil eder.|
| [transparency](/cells/python-net/tr/aspose.cells.drawing/line/transparency) | Çizginin şeffaflık derecesini 0,0 (opak) ile 1,0 (temiz) arasında bir değer olarak döndürür veya ayarlar.|
| [style](/cells/python-net/tr/aspose.cells.drawing/line/style) | Çizginin tarzını temsil eder.|
| [weight](/cells/python-net/tr/aspose.cells.drawing/line/weight) | Satırın [`WeightType`](/cells/python-net/tr/aspose.cells.drawing/weighttype) değerini alır veya ayarlar.|
| [weight_pt](/cells/python-net/tr/aspose.cells.drawing/line/weight_pt) |Çizginin ağırlığını nokta biriminde alır veya ayarlar.|
| [weight_px](/cells/python-net/tr/aspose.cells.drawing/line/weight_px) | Çizginin kalınlığını piksel cinsinden alır veya ayarlar.|
| [formatting_type](/cells/python-net/tr/aspose.cells.drawing/line/formatting_type) | Biçim türünü alır veya ayarlar.|
| [is_automatic_color](/cells/python-net/tr/aspose.cells.drawing/line/is_automatic_color) | Çizginin renginin otomatik olarak atanıp atanmadığını belirtir.|
| [is_visible](/cells/python-net/tr/aspose.cells.drawing/line/is_visible) | Çizginin görünür olup olmadığını gösterir.|
| [is_auto](/cells/python-net/tr/aspose.cells.drawing/line/is_auto) | Bu çizgi stilinin otomatik olarak atanıp atanmadığını belirtir.|
| [gradient_fill](/cells/python-net/tr/aspose.cells.drawing/line/gradient_fill) | Degrade dolguyu temsil eder.|



###  Örnek

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

###  Ayrıca bakınız
* modül [`aspose.cells.drawing`](..)
* sınıf [`WeightType`](/cells/python-net/tr/aspose.cells.drawing/weighttype)
