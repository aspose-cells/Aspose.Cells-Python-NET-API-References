---
title: FillFormat klass
second_title: Aspose.Cells for Python via .NET API Referenser
description:
type: docs
weight: 170
url: /sv/aspose.cells.drawing/fillformat/
is_root: false
---
##  FillFormat klass
Inkapslar objektet som representerar fyllningsformatering för en form.



Typen FillFormat avslöjar följande medlemmar:

###  Egenskaper
| Fast egendom| Beskrivning|
| :- | :- |
| [type](/cells/python-net/sv/aspose.cells.drawing/fillformat/type) | Hämtar och anger fyllningstypen.|
| [fill_type](/cells/python-net/sv/aspose.cells.drawing/fillformat/fill_type) | Hämtar och anger fyllningstyp|
| [transparency](/cells/python-net/sv/aspose.cells.drawing/fillformat/transparency) |Returnerar eller anger områdets genomskinlighetsgrad som ett värde från 0,0 (ogenomskinlig) till 1,0 (klar).|
| [set_type](/cells/python-net/sv/aspose.cells.drawing/fillformat/set_type) | Hämtar fyllningsformatuppsättningstypen.|
| [gradient_fill](/cells/python-net/sv/aspose.cells.drawing/fillformat/gradient_fill) | Hämtar [`FillFormat.gradient_fill`](/cells/python-net/sv/aspose.cells.drawing/fillformat#gradient_fill)-objektet.|
| [texture_fill](/cells/python-net/sv/aspose.cells.drawing/fillformat/texture_fill) | Hämtar [`FillFormat.texture_fill`](/cells/python-net/sv/aspose.cells.drawing/fillformat#texture_fill)-objektet.|
| [solid_fill](/cells/python-net/sv/aspose.cells.drawing/fillformat/solid_fill) | Hämtar [`FillFormat.solid_fill`](/cells/python-net/sv/aspose.cells.drawing/fillformat#solid_fill)-objektet.|
| [pattern_fill](/cells/python-net/sv/aspose.cells.drawing/fillformat/pattern_fill) | Hämtar [`FillFormat.pattern_fill`](/cells/python-net/sv/aspose.cells.drawing/fillformat#pattern_fill)-objektet.|
| [gradient_color_type](/cells/python-net/sv/aspose.cells.drawing/fillformat/gradient_color_type) | Returnerar övertoningsfärgtypen för den angivna fyllningen.|
| [gradient_style](/cells/python-net/sv/aspose.cells.drawing/fillformat/gradient_style) | Returnerar övertoningsstilen för den angivna fyllningen.|
| [gradient_color1](/cells/python-net/sv/aspose.cells.drawing/fillformat/gradient_color1) | Returnerar gradientfärg 1 för den angivna fyllningen.|
| [gradient_color2](/cells/python-net/sv/aspose.cells.drawing/fillformat/gradient_color2) |Returnerar gradientfärg 2 för den angivna fyllningen.|
| [gradient_degree](/cells/python-net/sv/aspose.cells.drawing/fillformat/gradient_degree) | Returnerar gradientgraden för den angivna fyllningen.<br/> Gäller endast för Excel 2007.|
| [gradient_variant](/cells/python-net/sv/aspose.cells.drawing/fillformat/gradient_variant) | Returnerar gradientvarianten för den angivna fyllningen.<br/> Gäller endast för Excel 2007.|
| [preset_color](/cells/python-net/sv/aspose.cells.drawing/fillformat/preset_color) | Returnerar den förinställda övertoningsfärgen för den angivna fyllningen.|
| [texture](/cells/python-net/sv/aspose.cells.drawing/fillformat/texture) | Representerar texturtypen för den angivna fyllningen.|
| [pattern](/cells/python-net/sv/aspose.cells.drawing/fillformat/pattern) | Representerar ett områdes visningsmönster.|
| [picture_format_type](/cells/python-net/sv/aspose.cells.drawing/fillformat/picture_format_type) | Hämtar och anger bildformattypen.|
| [scale](/cells/python-net/sv/aspose.cells.drawing/fillformat/scale) | Hämtar och ställer in bildformatsskalan.|
| [image_data](/cells/python-net/sv/aspose.cells.drawing/fillformat/image_data) | Hämtar och ställer in bilddata.|


###  Metoder
| Metod| Beskrivning|
| :- | :- |
| [`set_two_color_gradient(self, color1, color2, style, variant)`](/cells/python-net/sv/aspose.cells.drawing/fillformat/set_two_color_gradient/#aspose.pydrawing.color-aspose.pydrawing.color-aspose.cells.drawing.gradientstyletype-int) | Ställer in den angivna fyllningen till en tvåfärgad övertoning.<br/> Gäller endast för Excel 2007.|
| [`set_two_color_gradient(self, color1, transparency1, color2, transparency2, style, variant)`](/cells/python-net/sv/aspose.cells.drawing/fillformat/set_two_color_gradient/#aspose.pydrawing.color-float-aspose.pydrawing.color-float-aspose.cells.drawing.gradientstyletype-int) | Ställer in den angivna fyllningen till en tvåfärgad övertoning.<br/> Gäller endast för Excel 2007.|
| [`set_one_color_gradient(self, color, degree, style, variant)`](/cells/python-net/sv/aspose.cells.drawing/fillformat/set_one_color_gradient/#aspose.pydrawing.color-float-aspose.cells.drawing.gradientstyletype-int) | Ställer in den angivna fyllningen till en enfärgad övertoning.<br/> Gäller endast för Excel 2007.|
| [`set_preset_color_gradient(self, preset_color, style, variant)`](/cells/python-net/sv/aspose.cells.drawing/fillformat/set_preset_color_gradient/#aspose.cells.drawing.gradientpresettype-aspose.cells.drawing.gradientstyletype-int) | Ställer in den angivna fyllningen till en förinställd färgövertoning.<br/> Gäller endast för Excel 2007.|



###  Exempel

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

###  Se även
* modul [`aspose.cells.drawing`](..)
