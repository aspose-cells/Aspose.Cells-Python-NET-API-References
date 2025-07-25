---
title: TrendlineCollection classe
second_title: Aspose.Cells for Python via .NET API Riferimenti
description:
type: docs
weight: 350
url: /it/aspose.cells.charts/trendlinecollection/
is_root: false
---
##  TrendlineCollection classe
Rappresenta una raccolta di tutti gli [`Trendline`](/cells/python-net/it/aspose.cells.charts/trendline) oggetti per la serie di dati specificata.



Il tipo TrendlineCollection espone i seguenti membri:

###  Proprietà
| Proprietà| Descrizione|
| :- | :- |
| [capacity](/cells/python-net/it/aspose.cells.charts/trendlinecollection/capacity) | Ottiene o imposta il numero di elementi che l'elenco dell'array può contenere.|


###  Metodi
| Metodo| Descrizione|
| :- | :- |
| [`add(self, type)`](/cells/python-net/it/aspose.cells.charts/trendlinecollection/add/#aspose.cells.charts.trendlinetype) | Aggiunge un oggetto [`Trendline`](/cells/python-net/it/aspose.cells.charts/trendline) a questa raccolta con il tipo specificato.|
| [`add(self, type, name)`](/cells/python-net/it/aspose.cells.charts/trendlinecollection/add/#aspose.cells.charts.trendlinetype-str) | Aggiunge un oggetto [`Trendline`](/cells/python-net/it/aspose.cells.charts/trendline) a questa raccolta con il tipo e il nome specificati.|
| [`copy_to(self, array)`](/cells/python-net/it/aspose.cells.charts/trendlinecollection/copy_to/#list) |Copia l'intero elenco di array in un elenco di array unidimensionale compatibile, iniziando dall'inizio dell'elenco di array di destinazione.|
| [`copy_to(self, index, array, array_index, count)`](/cells/python-net/it/aspose.cells.charts/trendlinecollection/copy_to/#int-list-int-int) | Copia un intervallo di elementi dall'elenco di array a un elenco di array unidimensionale compatibile, a partire dall'indice specificato dell'elenco di array di destinazione.|
| [`index_of(self, item, index)`](/cells/python-net/it/aspose.cells.charts/trendlinecollection/index_of/#aspose.cells.charts.trendline-int) | Cerca l'oggetto specificato e restituisce l'indice a partire da zero della prima occorrenza nell'intervallo di elementi nell'elenco di array che si estende dall'indice specificato all'ultimo elemento.|
| [`index_of(self, item, index, count)`](/cells/python-net/it/aspose.cells.charts/trendlinecollection/index_of/#aspose.cells.charts.trendline-int-int) | Cerca l'oggetto specificato e restituisce l'indice a partire da zero della prima occorrenza nell'intervallo di elementi nell'elenco di array che inizia dall'indice specificato e contiene il numero specificato di elementi.|
| [`last_index_of(self, item)`](/cells/python-net/it/aspose.cells.charts/trendlinecollection/last_index_of/#aspose.cells.charts.trendline) | Cerca l'oggetto specificato e restituisce l'indice a partire da zero dell'ultima occorrenza nell'intero elenco di array.|
| [`last_index_of(self, item, index)`](/cells/python-net/it/aspose.cells.charts/trendlinecollection/last_index_of/#aspose.cells.charts.trendline-int) |Cerca l'oggetto specificato e restituisce l'indice a partire da zero dell'ultima occorrenza nell'intervallo di elementi nell'elenco di array che si estende dal primo elemento all'indice specificato.|
| [`last_index_of(self, item, index, count)`](/cells/python-net/it/aspose.cells.charts/trendlinecollection/last_index_of/#aspose.cells.charts.trendline-int-int) | Cerca l'oggetto specificato e restituisce l'indice a partire da zero dell'ultima occorrenza nell'intervallo di elementi nell'elenco di array che contiene il numero specificato di elementi e termina all'indice specificato.|
| [`binary_search(self, item)`](/cells/python-net/it/aspose.cells.charts/trendlinecollection/binary_search/#aspose.cells.charts.trendline) | Cerca un elemento nell'intero elenco dell'array ordinato utilizzando il comparatore predefinito e restituisce l'indice basato su zero dell'elemento.|



###  Esempio

```python
from aspose.cells import Workbook
from aspose.cells.charts import ChartType, TrendlineType
from aspose.pydrawing import Color

# Instantiating a Workbook object
workbook = Workbook()
# Adding a new worksheet to the Excel object
sheetIndex = workbook.worksheets.add()
# Obtaining the reference of the newly added worksheet by passing its sheet index
worksheet = workbook.worksheets[sheetIndex]
worksheet.cells.get("A1").put_value(50)
worksheet.cells.get("A2").put_value(100)
worksheet.cells.get("A3").put_value(150)
worksheet.cells.get("A4").put_value(200)
worksheet.cells.get("B1").put_value(60)
worksheet.cells.get("B2").put_value(32)
worksheet.cells.get("B3").put_value(50)
worksheet.cells.get("B4").put_value(40)
# Adding a chart to the worksheet
chartIndex = workbook.worksheets[0].charts.add(ChartType.COLUMN, 3, 3, 15, 10)
chart = workbook.worksheets[0].charts[chartIndex]
chart.n_series.add("A1:a3", True)
chart.n_series[0].trend_lines.add(TrendlineType.LINEAR, "MyTrendLine")
line = chart.n_series[0].trend_lines[0]
line.display_equation = True
line.display_r_squared = True
line.color = Color.red

```

###  Guarda anche
* modulo [`aspose.cells.charts`](..)
* classe [`Trendline`](/cells/python-net/it/aspose.cells.charts/trendline)
