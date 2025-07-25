---
title: Line classe
second_title: Aspose.Cells for Python via .NET API Riferimenti
description:
type: docs
weight: 270
url: /it/aspose.cells.drawing/line/
is_root: false
---
##  Line classe
Incapsula l'oggetto che rappresenta il formato della linea.



Il tipo Line espone i seguenti membri:

###  Proprietà
| Proprietà| Descrizione|
| :- | :- |
| [compound_type](/cells/python-net/it/aspose.cells.drawing/line/compound_type) | Specifica il tipo di linea composta|
| [dash_type](/cells/python-net/it/aspose.cells.drawing/line/dash_type) | Specifica il tipo di linea tratteggiata|
| [cap_type](/cells/python-net/it/aspose.cells.drawing/line/cap_type) | Specifica le estremità finali.|
| [join_type](/cells/python-net/it/aspose.cells.drawing/line/join_type) | Specifica i tappi di giunzione.|
| [begin_type](/cells/python-net/it/aspose.cells.drawing/line/begin_type) | Specifica una punta di freccia per l'inizio di una riga.|
| [end_type](/cells/python-net/it/aspose.cells.drawing/line/end_type) | Specifica una punta di freccia per la fine di una riga.|
| [begin_arrow_length](/cells/python-net/it/aspose.cells.drawing/line/begin_arrow_length) | Specifica la lunghezza della punta della freccia all'inizio di una riga.|
| [end_arrow_length](/cells/python-net/it/aspose.cells.drawing/line/end_arrow_length) | Specifica la lunghezza della punta della freccia alla fine di una riga.|
| [begin_arrow_width](/cells/python-net/it/aspose.cells.drawing/line/begin_arrow_width) | Specifica la larghezza della punta della freccia all'inizio di una linea.|
| [end_arrow_width](/cells/python-net/it/aspose.cells.drawing/line/end_arrow_width) | Specifica la larghezza della punta della freccia alla fine di una riga.|
| [theme_color](/cells/python-net/it/aspose.cells.drawing/line/theme_color) | Ottiene e imposta il colore del tema.|
| [color](/cells/python-net/it/aspose.cells.drawing/line/color) | Rappresenta il colore della linea.|
| [transparency](/cells/python-net/it/aspose.cells.drawing/line/transparency) | Restituisce o imposta il grado di trasparenza della linea come valore compreso tra 0,0 (opaco) e 1,0 (trasparente).|
| [style](/cells/python-net/it/aspose.cells.drawing/line/style) | Rappresenta lo stile della linea.|
| [weight](/cells/python-net/it/aspose.cells.drawing/line/weight) | Ottiene o imposta il valore [`WeightType`](/cells/python-net/it/aspose.cells.drawing/weighttype) della riga.|
| [weight_pt](/cells/python-net/it/aspose.cells.drawing/line/weight_pt) |Ottiene o imposta il peso della linea in unità di punti.|
| [weight_px](/cells/python-net/it/aspose.cells.drawing/line/weight_px) | Ottiene o imposta lo spessore della linea in unità di pixel.|
| [formatting_type](/cells/python-net/it/aspose.cells.drawing/line/formatting_type) | Ottiene o imposta il tipo di formato.|
| [is_automatic_color](/cells/python-net/it/aspose.cells.drawing/line/is_automatic_color) | Indica se il colore della linea viene assegnato automaticamente.|
| [is_visible](/cells/python-net/it/aspose.cells.drawing/line/is_visible) | Indica se la linea è visibile.|
| [is_auto](/cells/python-net/it/aspose.cells.drawing/line/is_auto) | Indica se questo stile di linea è assegnato automaticamente.|
| [gradient_fill](/cells/python-net/it/aspose.cells.drawing/line/gradient_fill) | Rappresenta il riempimento sfumato.|



###  Esempio

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

###  Guarda anche
* modulo [`aspose.cells.drawing`](..)
* classe [`WeightType`](/cells/python-net/it/aspose.cells.drawing/weighttype)
