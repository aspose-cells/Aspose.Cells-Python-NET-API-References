---
title: ErrorBar classe
second_title: Aspose.Cells for Python via .NET API Riferimenti
description:
type: docs
weight: 160
url: /it/aspose.cells.charts/errorbar/
is_root: false
---
##  ErrorBar classe
Rappresenta la barra di errore della serie di dati.



**Eredità:** [`ErrorBar`](/cells/python-net/aspose.cells.charts/errorbar) → 
[`Line`](/cells/python-net/it/aspose.cells.drawing/line)



Il tipo ErrorBar espone i seguenti membri:

###  Proprietà
| Proprietà| Descrizione|
| :- | :- |
| [compound_type](/cells/python-net/it/aspose.cells.charts/errorbar/compound_type) | Specifica il tipo di linea composta|
| [dash_type](/cells/python-net/it/aspose.cells.charts/errorbar/dash_type) | Specifica il tipo di linea tratteggiata|
| [cap_type](/cells/python-net/it/aspose.cells.charts/errorbar/cap_type) | Specifica le estremità finali.|
| [join_type](/cells/python-net/it/aspose.cells.charts/errorbar/join_type) | Specifica i tappi di giunzione.|
| [begin_type](/cells/python-net/it/aspose.cells.charts/errorbar/begin_type) | Specifica una punta di freccia per l'inizio di una riga.|
| [end_type](/cells/python-net/it/aspose.cells.charts/errorbar/end_type) | Specifica una punta di freccia per la fine di una riga.|
| [begin_arrow_length](/cells/python-net/it/aspose.cells.charts/errorbar/begin_arrow_length) | Specifica la lunghezza della punta della freccia all'inizio di una riga.|
| [end_arrow_length](/cells/python-net/it/aspose.cells.charts/errorbar/end_arrow_length) | Specifica la lunghezza della punta della freccia alla fine di una riga.|
| [begin_arrow_width](/cells/python-net/it/aspose.cells.charts/errorbar/begin_arrow_width) | Specifica la larghezza della punta della freccia all'inizio di una linea.|
| [end_arrow_width](/cells/python-net/it/aspose.cells.charts/errorbar/end_arrow_width) | Specifica la larghezza della punta della freccia alla fine di una riga.|
| [theme_color](/cells/python-net/it/aspose.cells.charts/errorbar/theme_color) | Ottiene e imposta il colore del tema.|
| [color](/cells/python-net/it/aspose.cells.charts/errorbar/color) | Rappresenta il colore della linea.|
| [transparency](/cells/python-net/it/aspose.cells.charts/errorbar/transparency) | Restituisce o imposta il grado di trasparenza della linea come valore compreso tra 0,0 (opaco) e 1,0 (trasparente).|
| [style](/cells/python-net/it/aspose.cells.charts/errorbar/style) | Rappresenta lo stile della linea.|
| [weight](/cells/python-net/it/aspose.cells.charts/errorbar/weight) | Ottiene o imposta il valore [`WeightType`](/cells/python-net/it/aspose.cells.drawing/weighttype) della riga.|
| [weight_pt](/cells/python-net/it/aspose.cells.charts/errorbar/weight_pt) |Ottiene o imposta il peso della linea in unità di punti.|
| [weight_px](/cells/python-net/it/aspose.cells.charts/errorbar/weight_px) | Ottiene o imposta lo spessore della linea in unità di pixel.|
| [formatting_type](/cells/python-net/it/aspose.cells.charts/errorbar/formatting_type) | Ottiene o imposta il tipo di formato.|
| [is_automatic_color](/cells/python-net/it/aspose.cells.charts/errorbar/is_automatic_color) | Indica se il colore della linea viene assegnato automaticamente.|
| [is_visible](/cells/python-net/it/aspose.cells.charts/errorbar/is_visible) | Indica se la linea è visibile.|
| [is_auto](/cells/python-net/it/aspose.cells.charts/errorbar/is_auto) | Indica se questo stile di linea è assegnato automaticamente.|
| [gradient_fill](/cells/python-net/it/aspose.cells.charts/errorbar/gradient_fill) | Rappresenta il riempimento sfumato.|
| [type](/cells/python-net/it/aspose.cells.charts/errorbar/type) | Rappresenta il tipo di importo della barra di errore.|
| [display_type](/cells/python-net/it/aspose.cells.charts/errorbar/display_type) | Rappresenta il tipo di visualizzazione della barra di errore.|
| [amount](/cells/python-net/it/aspose.cells.charts/errorbar/amount) | Rappresenta la quantità di barra di errore.|
| [show_marker_t_top](/cells/python-net/it/aspose.cells.charts/errorbar/show_marker_t_top) | Indica se le barre di errore di formattazione hanno una parte superiore a T.|
| [plus_value](/cells/python-net/it/aspose.cells.charts/errorbar/plus_value) | Rappresenta un importo di errore positivo quando il tipo di barra di errore è Personalizzato.|
| [minus_value](/cells/python-net/it/aspose.cells.charts/errorbar/minus_value) | Rappresenta un importo di errore negativo quando il tipo di barra di errore è Personalizzato.|



###  Esempio

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

###  Guarda anche
* modulo [`aspose.cells.charts`](..)
* classe [`ErrorBar`](/cells/python-net/it/aspose.cells.charts/errorbar)
* classe [`Line`](/cells/python-net/it/aspose.cells.drawing/line)
* classe [`WeightType`](/cells/python-net/it/aspose.cells.drawing/weighttype)
