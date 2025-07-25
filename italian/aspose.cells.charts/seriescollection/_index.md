---
title: SeriesCollection classe
second_title: Aspose.Cells for Python via .NET API Riferimenti
description:
type: docs
weight: 250
url: /it/aspose.cells.charts/seriescollection/
is_root: false
---
##  SeriesCollection classe
Incapsula una raccolta di [`Series`](/cells/python-net/it/aspose.cells.charts/series) oggetti.



Il tipo SeriesCollection espone i seguenti membri:

###  Proprietà
| Proprietà| Descrizione|
| :- | :- |
| [category_data](/cells/python-net/it/aspose.cells.charts/seriescollection/category_data) | Ottiene o imposta l'intervallo di valori dell'asse della categoria.<br/> Può essere un intervallo di celle (ad esempio, "d1:e10"),<br/> o una sequenza di valori (ad esempio, "{2,6,8,10}").|
| [second_category_data](/cells/python-net/it/aspose.cells.charts/seriescollection/second_category_data) | Ottiene o imposta l'intervallo dei valori dell'asse della seconda categoria.<br/> Può essere un intervallo di celle (ad esempio, "d1:e10"),<br/> o una sequenza di valori (ad esempio, "{2,6,8,10}").<br/> Ha effetto solo quando alcune ASeries sono tracciate sul secondo asse.|
| [is_color_varied](/cells/python-net/it/aspose.cells.charts/seriescollection/is_color_varied) | Rappresenta se il colore dei punti è variato.|
| [capacity](/cells/python-net/it/aspose.cells.charts/seriescollection/capacity) | Ottiene o imposta il numero di elementi che l'elenco dell'array può contenere.|


###  Metodi
| Metodo| Descrizione|
| :- | :- |
| [`add(self, area, is_vertical)`](/cells/python-net/it/aspose.cells.charts/seriescollection/add/#str-bool) | Aggiunge la raccolta [`Series`](/cells/python-net/it/aspose.cells.charts/series) a un grafico.|
| [`add(self, area, is_vertical, check_labels)`](/cells/python-net/it/aspose.cells.charts/seriescollection/add/#str-bool-bool) | Aggiunge la raccolta [`Series`](/cells/python-net/it/aspose.cells.charts/series) a un grafico.|
| [`copy_to(self, array)`](/cells/python-net/it/aspose.cells.charts/seriescollection/copy_to/#list) |Copia l'intero elenco di array in un elenco di array unidimensionale compatibile, iniziando dall'inizio dell'elenco di array di destinazione.|
| [`copy_to(self, index, array, array_index, count)`](/cells/python-net/it/aspose.cells.charts/seriescollection/copy_to/#int-list-int-int) | Copia un intervallo di elementi dall'elenco di array a un elenco di array unidimensionale compatibile, a partire dall'indice specificato dell'elenco di array di destinazione.|
| [`index_of(self, item, index)`](/cells/python-net/it/aspose.cells.charts/seriescollection/index_of/#aspose.cells.charts.series-int) | Cerca l'oggetto specificato e restituisce l'indice a partire da zero della prima occorrenza nell'intervallo di elementi nell'elenco di array che si estende dall'indice specificato all'ultimo elemento.|
| [`index_of(self, item, index, count)`](/cells/python-net/it/aspose.cells.charts/seriescollection/index_of/#aspose.cells.charts.series-int-int) | Cerca l'oggetto specificato e restituisce l'indice a partire da zero della prima occorrenza nell'intervallo di elementi nell'elenco di array che inizia dall'indice specificato e contiene il numero specificato di elementi.|
| [`last_index_of(self, item)`](/cells/python-net/it/aspose.cells.charts/seriescollection/last_index_of/#aspose.cells.charts.series) | Cerca l'oggetto specificato e restituisce l'indice a partire da zero dell'ultima occorrenza nell'intero elenco di array.|
| [`last_index_of(self, item, index)`](/cells/python-net/it/aspose.cells.charts/seriescollection/last_index_of/#aspose.cells.charts.series-int) |Cerca l'oggetto specificato e restituisce l'indice a partire da zero dell'ultima occorrenza nell'intervallo di elementi nell'elenco di array che si estende dal primo elemento all'indice specificato.|
| [`last_index_of(self, item, index, count)`](/cells/python-net/it/aspose.cells.charts/seriescollection/last_index_of/#aspose.cells.charts.series-int-int) | Cerca l'oggetto specificato e restituisce l'indice a partire da zero dell'ultima occorrenza nell'intervallo di elementi nell'elenco di array che contiene il numero specificato di elementi e termina all'indice specificato.|
| [`get_series_by_order(self, order)`](/cells/python-net/it/aspose.cells.charts/seriescollection/get_series_by_order/#int) | Ottiene l'elemento [`Series`](/cells/python-net/it/aspose.cells.charts/series) tramite ordine.|
| [`change_series_order(self, source_index, dest_index)`](/cells/python-net/it/aspose.cells.charts/seriescollection/change_series_order/#int-int) | Cambia direttamente l'ordine delle due serie.|
| [`swap_series(self, source_index, dest_index)`](/cells/python-net/it/aspose.cells.charts/seriescollection/swap_series/#int-int) | Cambia direttamente l'ordine delle due serie.|
| [`set_series_names(self, start_index, area, is_vertical)`](/cells/python-net/it/aspose.cells.charts/seriescollection/set_series_names/#int-str-bool) | Imposta il nome di tutte le serie nel grafico.|
| [`add_r1c1(self, area, is_vertical)`](/cells/python-net/it/aspose.cells.charts/seriescollection/add_r1c1/#str-bool) | Aggiunge la raccolta [`Series`](/cells/python-net/it/aspose.cells.charts/series) a un grafico.|
| [`binary_search(self, item)`](/cells/python-net/it/aspose.cells.charts/seriescollection/binary_search/#aspose.cells.charts.series) | Cerca un elemento nell'intero elenco dell'array ordinato utilizzando il comparatore predefinito e restituisce l'indice basato su zero dell'elemento.|



###  Esempio

```python
from aspose.cells import Workbook
from aspose.cells.charts import ChartType

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
chart.n_series.add("A1:B4", True)
# Setting the data source for the category data of NSeries
chart.n_series.category_data = "C1:C4"
# Saving the Excel file
workbook.save("book1.xls")

```

###  Guarda anche
* modulo [`aspose.cells.charts`](..)
* classe [`Series`](/cells/python-net/it/aspose.cells.charts/series)
