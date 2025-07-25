---
title: Line klass
second_title: Aspose.Cells for Python via .NET API Referenser
description:
type: docs
weight: 270
url: /sv/aspose.cells.drawing/line/
is_root: false
---
##  Line klass
Inkapslar objektet som representerar linjeformatet.



Typen Line avslöjar följande medlemmar:

###  Egenskaper
| Fast egendom| Beskrivning|
| :- | :- |
| [compound_type](/cells/python-net/sv/aspose.cells.drawing/line/compound_type) | Anger den sammansatta linjetypen|
| [dash_type](/cells/python-net/sv/aspose.cells.drawing/line/dash_type) | Anger typen av streckad linje|
| [cap_type](/cells/python-net/sv/aspose.cells.drawing/line/cap_type) | Anger slutkapslarna.|
| [join_type](/cells/python-net/sv/aspose.cells.drawing/line/join_type) | Anger kopplingsfästena.|
| [begin_type](/cells/python-net/sv/aspose.cells.drawing/line/begin_type) | Anger en pilspets för början av en rad.|
| [end_type](/cells/python-net/sv/aspose.cells.drawing/line/end_type) | Anger en pilspets för slutet av en rad.|
| [begin_arrow_length](/cells/python-net/sv/aspose.cells.drawing/line/begin_arrow_length) | Anger längden på pilspetsen för början av en rad.|
| [end_arrow_length](/cells/python-net/sv/aspose.cells.drawing/line/end_arrow_length) | Anger längden på pilspetsen för slutet av en rad.|
| [begin_arrow_width](/cells/python-net/sv/aspose.cells.drawing/line/begin_arrow_width) | Anger bredden på pilspetsen för början av en rad.|
| [end_arrow_width](/cells/python-net/sv/aspose.cells.drawing/line/end_arrow_width) | Anger bredden på pilspetsen för slutet av en linje.|
| [theme_color](/cells/python-net/sv/aspose.cells.drawing/line/theme_color) | Hämtar och ställer in temafärgen.|
| [color](/cells/python-net/sv/aspose.cells.drawing/line/color) | Representerar linjens färg.|
| [transparency](/cells/python-net/sv/aspose.cells.drawing/line/transparency) | Returnerar eller anger graden av genomskinlighet för linjen som ett värde från 0,0 (ogenomskinlig) till 1,0 (klar).|
| [style](/cells/python-net/sv/aspose.cells.drawing/line/style) | Representerar linjens stil.|
| [weight](/cells/python-net/sv/aspose.cells.drawing/line/weight) | Hämtar eller ställer in [`WeightType`](/cells/python-net/sv/aspose.cells.drawing/weighttype) för raden.|
| [weight_pt](/cells/python-net/sv/aspose.cells.drawing/line/weight_pt) |Hämtar eller ställer in linjens vikt i enheter av punkter.|
| [weight_px](/cells/python-net/sv/aspose.cells.drawing/line/weight_px) | Hämtar eller anger linjens vikt i pixlar.|
| [formatting_type](/cells/python-net/sv/aspose.cells.drawing/line/formatting_type) | Hämtar eller anger formattyp.|
| [is_automatic_color](/cells/python-net/sv/aspose.cells.drawing/line/is_automatic_color) | Anger om linjens färg tilldelas automatiskt.|
| [is_visible](/cells/python-net/sv/aspose.cells.drawing/line/is_visible) | Representerar om linjen är synlig.|
| [is_auto](/cells/python-net/sv/aspose.cells.drawing/line/is_auto) | Anger om denna linjestil tilldelas automatiskt.|
| [gradient_fill](/cells/python-net/sv/aspose.cells.drawing/line/gradient_fill) | Representerar gradientfyllning.|



###  Exempel

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

###  Se även
* modul [`aspose.cells.drawing`](..)
* klass [`WeightType`](/cells/python-net/sv/aspose.cells.drawing/weighttype)
