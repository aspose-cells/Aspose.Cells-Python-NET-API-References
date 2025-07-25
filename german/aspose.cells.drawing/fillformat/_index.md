---
title: FillFormat Klasse
second_title: Aspose.Cells for Python via .NET API Referenzen
description:
type: docs
weight: 170
url: /de/aspose.cells.drawing/fillformat/
is_root: false
---
##  FillFormat Klasse
Kapselt das Objekt, das die Füllformatierung für eine Form darstellt.



Der Typ FillFormat macht die folgenden Member verfügbar:

###  Eigenschaften
| Eigentum| Beschreibung|
| :- | :- |
| [type](/cells/python-net/de/aspose.cells.drawing/fillformat/type) | Ruft den Fülltyp ab und legt ihn fest.|
| [fill_type](/cells/python-net/de/aspose.cells.drawing/fillformat/fill_type) | Ruft den Fülltyp ab und legt ihn fest|
| [transparency](/cells/python-net/de/aspose.cells.drawing/fillformat/transparency) |Gibt den Transparenzgrad des Bereichs als Wert zwischen 0,0 (undurchsichtig) und 1,0 (durchsichtig) zurück oder legt ihn fest.|
| [set_type](/cells/python-net/de/aspose.cells.drawing/fillformat/set_type) | Ruft den Füllformatsatztyp ab.|
| [gradient_fill](/cells/python-net/de/aspose.cells.drawing/fillformat/gradient_fill) | Ruft das Objekt [`FillFormat.gradient_fill`](/cells/python-net/de/aspose.cells.drawing/fillformat#gradient_fill) ab.|
| [texture_fill](/cells/python-net/de/aspose.cells.drawing/fillformat/texture_fill) | Ruft das Objekt [`FillFormat.texture_fill`](/cells/python-net/de/aspose.cells.drawing/fillformat#texture_fill) ab.|
| [solid_fill](/cells/python-net/de/aspose.cells.drawing/fillformat/solid_fill) | Ruft das Objekt [`FillFormat.solid_fill`](/cells/python-net/de/aspose.cells.drawing/fillformat#solid_fill) ab.|
| [pattern_fill](/cells/python-net/de/aspose.cells.drawing/fillformat/pattern_fill) | Ruft das Objekt [`FillFormat.pattern_fill`](/cells/python-net/de/aspose.cells.drawing/fillformat#pattern_fill) ab.|
| [gradient_color_type](/cells/python-net/de/aspose.cells.drawing/fillformat/gradient_color_type) | Gibt den Farbverlaufstyp für die angegebene Füllung zurück.|
| [gradient_style](/cells/python-net/de/aspose.cells.drawing/fillformat/gradient_style) | Gibt den Farbverlaufsstil für die angegebene Füllung zurück.|
| [gradient_color1](/cells/python-net/de/aspose.cells.drawing/fillformat/gradient_color1) | Gibt die Verlaufsfarbe 1 für die angegebene Füllung zurück.|
| [gradient_color2](/cells/python-net/de/aspose.cells.drawing/fillformat/gradient_color2) |Gibt die Verlaufsfarbe 2 für die angegebene Füllung zurück.|
| [gradient_degree](/cells/python-net/de/aspose.cells.drawing/fillformat/gradient_degree) | Gibt den Gradienten für die angegebene Füllung zurück.<br/> Gilt nur für Excel 2007.|
| [gradient_variant](/cells/python-net/de/aspose.cells.drawing/fillformat/gradient_variant) | Gibt die Farbverlaufsvariante für die angegebene Füllung zurück.<br/> Gilt nur für Excel 2007.|
| [preset_color](/cells/python-net/de/aspose.cells.drawing/fillformat/preset_color) | Gibt die voreingestellte Farbverlaufsfarbe für die angegebene Füllung zurück.|
| [texture](/cells/python-net/de/aspose.cells.drawing/fillformat/texture) | Stellt den Texturtyp für die angegebene Füllung dar.|
| [pattern](/cells/python-net/de/aspose.cells.drawing/fillformat/pattern) | Stellt das Anzeigemuster eines Bereichs dar.|
| [picture_format_type](/cells/python-net/de/aspose.cells.drawing/fillformat/picture_format_type) | Ruft den Bildformattyp ab und legt ihn fest.|
| [scale](/cells/python-net/de/aspose.cells.drawing/fillformat/scale) | Ruft den Maßstab des Bildformats ab und legt ihn fest.|
| [image_data](/cells/python-net/de/aspose.cells.drawing/fillformat/image_data) | Ruft die Bilddaten ab und legt sie fest.|


###  Methoden
| Methode| Beschreibung|
| :- | :- |
| [`set_two_color_gradient(self, color1, color2, style, variant)`](/cells/python-net/de/aspose.cells.drawing/fillformat/set_two_color_gradient/#aspose.pydrawing.color-aspose.pydrawing.color-aspose.cells.drawing.gradientstyletype-int) | Legt die angegebene Füllung auf einen zweifarbigen Farbverlauf fest.<br/> Gilt nur für Excel 2007.|
| [`set_two_color_gradient(self, color1, transparency1, color2, transparency2, style, variant)`](/cells/python-net/de/aspose.cells.drawing/fillformat/set_two_color_gradient/#aspose.pydrawing.color-float-aspose.pydrawing.color-float-aspose.cells.drawing.gradientstyletype-int) | Legt die angegebene Füllung auf einen zweifarbigen Farbverlauf fest.<br/> Gilt nur für Excel 2007.|
| [`set_one_color_gradient(self, color, degree, style, variant)`](/cells/python-net/de/aspose.cells.drawing/fillformat/set_one_color_gradient/#aspose.pydrawing.color-float-aspose.cells.drawing.gradientstyletype-int) | Legt die angegebene Füllung auf einen einfarbigen Farbverlauf fest.<br/> Gilt nur für Excel 2007.|
| [`set_preset_color_gradient(self, preset_color, style, variant)`](/cells/python-net/de/aspose.cells.drawing/fillformat/set_preset_color_gradient/#aspose.cells.drawing.gradientpresettype-aspose.cells.drawing.gradientstyletype-int) | Legt die angegebene Füllung auf einen voreingestellten Farbverlauf fest.<br/> Gilt nur für Excel 2007.|



###  Beispiel

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

###  Siehe auch
* Modul [`aspose.cells.drawing`](..)
