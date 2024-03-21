---
title: SparklineGroupCollection classe
second_title: Aspose.Cells for Python via .NET API Referenze
description:
type: docs
weight: 300
url: /it/aspose.cells.charts/sparklinegroupcollection/
is_root: false
---
##  SparklineGroupCollection classe
Incapsula una raccolta di [`SparklineGroup`](/cells/python-net/it/aspose.cells.charts/sparklinegroup) oggetti.



Il tipo SparklineGroupCollection espone i seguenti membri:

###  Proprietà
| Proprietà| Descrizione|
| :- | :- |
| [capacity](/cells/python-net/it/aspose.cells.charts/sparklinegroupcollection/capacity) | Ottiene o imposta il numero di elementi che l'elenco di matrici può contenere.|


###  Metodi
| Metodo| Descrizione|
| :- | :- |
| [copy_to](/cells/python-net/it/aspose.cells.charts/sparklinegroupcollection/copy_to/#list) | Copia l'intero elenco di matrici in un elenco di matrici unidimensionali compatibile, a partire dall'inizio dell'elenco di matrici di destinazione.|
| [copy_to](/cells/python-net/it/aspose.cells.charts/sparklinegroupcollection/copy_to/#int-list-int-int) | Copia un intervallo di elementi dall'elenco di matrici a un elenco di matrici unidimensionali compatibile, a partire dall'indice specificato dell'elenco di matrici di destinazione.|
| [index_of](/cells/python-net/it/aspose.cells.charts/sparklinegroupcollection/index_of/#aspose.cells.charts.SparklineGroup-int) | Cerca l'oggetto specificato e restituisce l'indice in base zero della prima occorrenza all'interno dell'intervallo di elementi nell'elenco di matrice che si estende dall'indice specificato all'ultimo elemento.|
| [index_of](/cells/python-net/it/aspose.cells.charts/sparklinegroupcollection/index_of/#aspose.cells.charts.SparklineGroup-int-int) |Cerca l'oggetto specificato e restituisce l'indice in base zero della prima occorrenza all'interno dell'intervallo di elementi nell'elenco di matrice che inizia in corrispondenza dell'indice specificato e contiene il numero di elementi specificato.|
| [last_index_of](/cells/python-net/it/aspose.cells.charts/sparklinegroupcollection/last_index_of/#aspose.cells.charts.SparklineGroup) | Cerca l'oggetto specificato e restituisce l'indice in base zero dell'ultima occorrenza all'interno dell'intero elenco di matrici.|
| [last_index_of](/cells/python-net/it/aspose.cells.charts/sparklinegroupcollection/last_index_of/#aspose.cells.charts.SparklineGroup-int) | Cerca l'oggetto specificato e restituisce l'indice in base zero dell'ultima occorrenza all'interno dell'intervallo di elementi nell'elenco di matrice che si estende dal primo elemento all'indice specificato.|
| [last_index_of](/cells/python-net/it/aspose.cells.charts/sparklinegroupcollection/last_index_of/#aspose.cells.charts.SparklineGroup-int-int) | Cerca l'oggetto specificato e restituisce l'indice in base zero dell'ultima occorrenza all'interno dell'intervallo di elementi nell'elenco di matrice che contiene il numero di elementi specificato e termina con l'indice specificato.|
| [add](/cells/python-net/it/aspose.cells.charts/sparklinegroupcollection/add/#aspose.cells.charts.SparklineType-str-bool-aspose.cells.CellArea) | Aggiunge un elemento [`SparklineGroup`](/cells/python-net/it/aspose.cells.charts/sparklinegroup) alla raccolta.|
| [clear_sparklines](/cells/python-net/it/aspose.cells.charts/sparklinegroupcollection/clear_sparklines/#aspose.cells.CellArea) | Cancella le linee sparkline all'interno di un'area di celle.|
| [clear_sparkline_groups](/cells/python-net/it/aspose.cells.charts/sparklinegroupcollection/clear_sparkline_groups/#aspose.cells.CellArea) | Cancella i gruppi sparkline che si sovrappongono a un'area di celle.|
| [binary_search](/cells/python-net/it/aspose.cells.charts/sparklinegroupcollection/binary_search/#aspose.cells.charts.SparklineGroup) | Cerca un elemento nell'intero elenco di array ordinato utilizzando l'operatore di confronto predefinito e restituisce l'indice in base zero dell'elemento.|



###  Esempio

```python
from aspose.cells import CellArea, SaveFormat, Workbook
from aspose.cells.charts import SparklineType

book = Workbook()
sheet = book.worksheets[0]
sheet.cells.get("A1").put_value(5)
sheet.cells.get("B1").put_value(2)
sheet.cells.get("C1").put_value(1)
sheet.cells.get("D1").put_value(3)
#  Define the CellArea
ca = CellArea()
ca.start_column = 4
ca.end_column = 4
ca.start_row = 0
ca.end_row = 0
idx = sheet.sparkline_group_collection.add(SparklineType.LINE, "A1:D1", False, ca)
group = sheet.sparkline_group_collection[idx]
group.sparkline_collection.add(sheet.name + "!A1:D1", 0, 4)
book.save("output.xlsx", SaveFormat.XLSX)

```

###  Guarda anche
* modulo [`aspose.cells.charts`](..)
* classe [`SparklineGroup`](/cells/python-net/it/aspose.cells.charts/sparklinegroup)
