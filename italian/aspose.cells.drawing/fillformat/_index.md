---
title: FillFormat classe
second_title: Aspose.Cells for Python via .NET API Riferimenti
description:
type: docs
weight: 170
url: /it/aspose.cells.drawing/fillformat/
is_root: false
---
##  FillFormat classe
Incapsula l'oggetto che rappresenta la formattazione di riempimento per una forma.



Il tipo FillFormat espone i seguenti membri:

###  Proprietà
| Proprietà| Descrizione|
| :- | :- |
| [type](/cells/python-net/it/aspose.cells.drawing/fillformat/type) | Ottiene e imposta il tipo di riempimento.|
| [fill_type](/cells/python-net/it/aspose.cells.drawing/fillformat/fill_type) | Ottiene e imposta il tipo di riempimento|
| [transparency](/cells/python-net/it/aspose.cells.drawing/fillformat/transparency) |Restituisce o imposta il grado di trasparenza dell'area come valore compreso tra 0,0 (opaco) e 1,0 (trasparente).|
| [set_type](/cells/python-net/it/aspose.cells.drawing/fillformat/set_type) | Ottiene il tipo di set di formati di riempimento.|
| [gradient_fill](/cells/python-net/it/aspose.cells.drawing/fillformat/gradient_fill) | Ottiene l'oggetto [`FillFormat.gradient_fill`](/cells/python-net/it/aspose.cells.drawing/fillformat#gradient_fill).|
| [texture_fill](/cells/python-net/it/aspose.cells.drawing/fillformat/texture_fill) | Ottiene l'oggetto [`FillFormat.texture_fill`](/cells/python-net/it/aspose.cells.drawing/fillformat#texture_fill).|
| [solid_fill](/cells/python-net/it/aspose.cells.drawing/fillformat/solid_fill) | Ottiene l'oggetto [`FillFormat.solid_fill`](/cells/python-net/it/aspose.cells.drawing/fillformat#solid_fill).|
| [pattern_fill](/cells/python-net/it/aspose.cells.drawing/fillformat/pattern_fill) | Ottiene l'oggetto [`FillFormat.pattern_fill`](/cells/python-net/it/aspose.cells.drawing/fillformat#pattern_fill).|
| [gradient_color_type](/cells/python-net/it/aspose.cells.drawing/fillformat/gradient_color_type) | Restituisce il tipo di colore sfumato per il riempimento specificato.|
| [gradient_style](/cells/python-net/it/aspose.cells.drawing/fillformat/gradient_style) | Restituisce lo stile sfumato per il riempimento specificato.|
| [gradient_color1](/cells/python-net/it/aspose.cells.drawing/fillformat/gradient_color1) | Restituisce il colore sfumato 1 per il riempimento specificato.|
| [gradient_color2](/cells/python-net/it/aspose.cells.drawing/fillformat/gradient_color2) |Restituisce il colore sfumato 2 per il riempimento specificato.|
| [gradient_degree](/cells/python-net/it/aspose.cells.drawing/fillformat/gradient_degree) | Restituisce il grado di sfumatura per il riempimento specificato.<br/> Si applica solo a Excel 2007.|
| [gradient_variant](/cells/python-net/it/aspose.cells.drawing/fillformat/gradient_variant) | Restituisce la variante di sfumatura per il riempimento specificato.<br/> Si applica solo a Excel 2007.|
| [preset_color](/cells/python-net/it/aspose.cells.drawing/fillformat/preset_color) | Restituisce il colore preimpostato del gradiente per il riempimento specificato.|
| [texture](/cells/python-net/it/aspose.cells.drawing/fillformat/texture) | Rappresenta il tipo di trama per il riempimento specificato.|
| [pattern](/cells/python-net/it/aspose.cells.drawing/fillformat/pattern) | Rappresenta lo schema di visualizzazione di un'area.|
| [picture_format_type](/cells/python-net/it/aspose.cells.drawing/fillformat/picture_format_type) | Ottiene e imposta il tipo di formato dell'immagine.|
| [scale](/cells/python-net/it/aspose.cells.drawing/fillformat/scale) | Ottiene e imposta la scala del formato dell'immagine.|
| [image_data](/cells/python-net/it/aspose.cells.drawing/fillformat/image_data) | Ottiene e imposta i dati dell'immagine.|


###  Metodi
| Metodo| Descrizione|
| :- | :- |
| [`set_two_color_gradient(self, color1, color2, style, variant)`](/cells/python-net/it/aspose.cells.drawing/fillformat/set_two_color_gradient/#aspose.pydrawing.color-aspose.pydrawing.color-aspose.cells.drawing.gradientstyletype-int) | Imposta il riempimento specificato su un gradiente a due colori.<br/> Si applica solo a Excel 2007.|
| [`set_two_color_gradient(self, color1, transparency1, color2, transparency2, style, variant)`](/cells/python-net/it/aspose.cells.drawing/fillformat/set_two_color_gradient/#aspose.pydrawing.color-float-aspose.pydrawing.color-float-aspose.cells.drawing.gradientstyletype-int) | Imposta il riempimento specificato su un gradiente a due colori.<br/> Si applica solo a Excel 2007.|
| [`set_one_color_gradient(self, color, degree, style, variant)`](/cells/python-net/it/aspose.cells.drawing/fillformat/set_one_color_gradient/#aspose.pydrawing.color-float-aspose.cells.drawing.gradientstyletype-int) | Imposta il riempimento specificato su un gradiente di un solo colore.<br/> Si applica solo a Excel 2007.|
| [`set_preset_color_gradient(self, preset_color, style, variant)`](/cells/python-net/it/aspose.cells.drawing/fillformat/set_preset_color_gradient/#aspose.cells.drawing.gradientpresettype-aspose.cells.drawing.gradientstyletype-int) | Imposta il riempimento specificato su un gradiente di colore preimpostato.<br/> Si applica solo a Excel 2007.|



###  Esempio

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

###  Guarda anche
* modulo [`aspose.cells.drawing`](..)
