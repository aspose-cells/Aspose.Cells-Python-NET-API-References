---
title: ChartPointCollection classe
second_title: Aspose.Cells for Python via .NET API Riferimenti
description:
type: docs
weight: 110
url: /it/aspose.cells.charts/chartpointcollection/
is_root: false
---
##  ChartPointCollection classe
Rappresenta una raccolta che contiene tutti i punti di una serie.



Il tipo ChartPointCollection espone i seguenti membri:

###  Proprietà
| Proprietà| Descrizione|
| :- | :- |
| [count](/cells/python-net/it/aspose.cells.charts/chartpointcollection/count) | Ottiene il conteggio dei punti del grafico.|



Ottiene l'elemento [`ChartPoint`](/cells/python-net/it/aspose.cells.charts/chartpoint) all'indice specificato nella serie.
###  Indicizzatore
| Nome| Descrizione|
| :- | :- |
| [index] | Indice del punto del grafico nella serie.|


###  Metodi
| Metodo| Descrizione|
| :- | :- |
| [`clear(self)`](/cells/python-net/it/aspose.cells.charts/chartpointcollection/clear/#) | Rimuovi tutte le impostazioni dei punti del grafico.|
| [`remove_at(self, index)`](/cells/python-net/it/aspose.cells.charts/chartpointcollection/remove_at/#int) | Rimuove il punto dall'indice della serie.|



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
chartIndex = worksheet.charts.add(ChartType.PIE_EXPLODED, 5, 0, 25, 10)
# Accessing the instance of the newly added chart
chart = worksheet.charts[chartIndex]
# Adding NSeries (chart data source) to the chart ranging from "A1" cell to "B3"
chart.n_series.add("A1:B3", True)
# Show Data Labels
chart.n_series[0].data_labels.show_value = True
points = chart.n_series[0].points
for i in range(points.count):
    # Get Data Point
    point = points[i]
    # Set Pir Explosion
    point.explosion = 15
    # Set Border Color
    point.border.color = Color.red
# Saving the Excel file
workbook.save("book1.xls")

```

###  Guarda anche
* modulo [`aspose.cells.charts`](..)
* classe [`ChartPoint`](/cells/python-net/it/aspose.cells.charts/chartpoint)
