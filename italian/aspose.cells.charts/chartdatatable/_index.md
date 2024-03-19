---
title: ChartDataTable classe
second_title: Aspose.Cells for Python via .NET API Referenze
description:
type: docs
weight: 70
url: /it/aspose.cells.charts/chartdatatable/
is_root: false
---
##  ChartDataTable classe
Rappresenta una tabella dati del grafico.



Il tipo ChartDataTable espone i seguenti membri:

###  Proprietà
| Proprietà| Descrizione|
| :- | :- |
| [font](/cells/python-net/it/aspose.cells.charts/chartdatatable/font) | Ottiene un oggetto [`ChartDataTable.font`](/cells/python-net/it/aspose.cells.charts/chartdatatable#font) che rappresenta l'impostazione del carattere della tabella dati del grafico specificata.|
| [auto_scale_font](/cells/python-net/it/aspose.cells.charts/chartdatatable/auto_scale_font) | Vero se il testo nell'oggetto cambia la dimensione del carattere quando cambia la dimensione dell'oggetto.<br/>Il valore predefinito è Vero.|
| [background_mode](/cells/python-net/it/aspose.cells.charts/chartdatatable/background_mode) | Ottiene e imposta la modalità di visualizzazione dello sfondo|
| [background](/cells/python-net/it/aspose.cells.charts/chartdatatable/background) | Ottiene e imposta la modalità di visualizzazione dello sfondo|
| [has_border_horizontal](/cells/python-net/it/aspose.cells.charts/chartdatatable/has_border_horizontal) | Vero se la tabella dati del grafico ha bordi di cella orizzontali|
| [has_border_vertical](/cells/python-net/it/aspose.cells.charts/chartdatatable/has_border_vertical) | Vero se la tabella dati del grafico ha bordi di cella verticali|
| [has_border_outline](/cells/python-net/it/aspose.cells.charts/chartdatatable/has_border_outline) | Vero se la tabella dati del grafico presenta bordi delineati|
| [show_legend_key](/cells/python-net/it/aspose.cells.charts/chartdatatable/show_legend_key) | Vero se la chiave della legenda dell'etichetta dati è visibile.|
| [border](/cells/python-net/it/aspose.cells.charts/chartdatatable/border) | Restituisce un oggetto Border che rappresenta il bordo dell'oggetto|



###  Esempio

```python
from aspose.cells import Workbook
from aspose.cells.charts import ChartType
from aspose.pydrawing import Color

# Instantiating a Workbook object
workbook = Workbook()
# Obtaining the reference of the first worksheet
worksheet = workbook.worksheets[0]
# Adding a sample value to "A1" cell
worksheet.cells.get("A1").put_value(50)
# Adding a sample value to "A2" cell
worksheet.cells.get("A2").put_value(100)
# Adding a sample value to "A3" cell
worksheet.cells.get("A3").put_value(150)
# Adding a sample value to "B1" cell
worksheet.cells.get("B1").put_value(60)
# Adding a sample value to "B2" cell
worksheet.cells.get("B2").put_value(32)
# Adding a sample value to "B3" cell
worksheet.cells.get("B3").put_value(50)
# Adding a chart to the worksheet
chartIndex = worksheet.charts.add(ChartType.COLUMN, 5, 0, 25, 10)
# Accessing the instance of the newly added chart
chart = worksheet.charts[chartIndex]
# Adding NSeries (chart data source) to the chart ranging from "A1" cell to "B3"
chart.n_series.add("A1:B3", True)
chart.show_data_table = True
# Getting Chart Table
chartTable = chart.chart_data_table
# Setting Chart Table Font Color
chartTable.font.color = Color.red
# Setting Legend Key VisibilityOptions
chartTable.show_legend_key = False
# Saving the Excel file
workbook.save("book1.xls")

```

###  Guarda anche
* modulo [`aspose.cells.charts`](..)
