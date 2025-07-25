---
title: ConditionalFormattingIconCollection classe
second_title: Aspose.Cells for Python via .NET API Riferimenti
description:
type: docs
weight: 300
url: /it/aspose.cells/conditionalformattingiconcollection/
is_root: false
---
##  ConditionalFormattingIconCollection classe
Rappresenta una raccolta di [`ConditionalFormattingIcon`](/cells/python-net/it/aspose.cells/conditionalformattingicon) oggetti.



Il tipo ConditionalFormattingIconCollection espone i seguenti membri:

###  Proprietà
| Proprietà| Descrizione|
| :- | :- |
| [capacity](/cells/python-net/it/aspose.cells/conditionalformattingiconcollection/capacity) | Ottiene o imposta il numero di elementi che l'elenco dell'array può contenere.|


###  Metodi
| Metodo| Descrizione|
| :- | :- |
| [`add(self, type, index)`](/cells/python-net/it/aspose.cells/conditionalformattingiconcollection/add/#aspose.cells.iconsettype-int) | Aggiunge l'oggetto [`ConditionalFormattingIcon`](/cells/python-net/it/aspose.cells/conditionalformattingicon).|
| [`add(self, cficon)`](/cells/python-net/it/aspose.cells/conditionalformattingiconcollection/add/#aspose.cells.conditionalformattingicon) | Aggiunge l'oggetto [`ConditionalFormattingIcon`](/cells/python-net/it/aspose.cells/conditionalformattingicon).|
| [`copy_to(self, array)`](/cells/python-net/it/aspose.cells/conditionalformattingiconcollection/copy_to/#list) |Copia l'intero elenco di array in un elenco di array unidimensionale compatibile, iniziando dall'inizio dell'elenco di array di destinazione.|
| [`copy_to(self, index, array, array_index, count)`](/cells/python-net/it/aspose.cells/conditionalformattingiconcollection/copy_to/#int-list-int-int) | Copia un intervallo di elementi dall'elenco di array a un elenco di array unidimensionale compatibile, a partire dall'indice specificato dell'elenco di array di destinazione.|
| [`index_of(self, item, index)`](/cells/python-net/it/aspose.cells/conditionalformattingiconcollection/index_of/#aspose.cells.conditionalformattingicon-int) | Cerca l'oggetto specificato e restituisce l'indice a partire da zero della prima occorrenza nell'intervallo di elementi nell'elenco di array che si estende dall'indice specificato all'ultimo elemento.|
| [`index_of(self, item, index, count)`](/cells/python-net/it/aspose.cells/conditionalformattingiconcollection/index_of/#aspose.cells.conditionalformattingicon-int-int) | Cerca l'oggetto specificato e restituisce l'indice a partire da zero della prima occorrenza nell'intervallo di elementi nell'elenco di array che inizia dall'indice specificato e contiene il numero specificato di elementi.|
| [`last_index_of(self, item)`](/cells/python-net/it/aspose.cells/conditionalformattingiconcollection/last_index_of/#aspose.cells.conditionalformattingicon) | Cerca l'oggetto specificato e restituisce l'indice a partire da zero dell'ultima occorrenza nell'intero elenco di array.|
| [`last_index_of(self, item, index)`](/cells/python-net/it/aspose.cells/conditionalformattingiconcollection/last_index_of/#aspose.cells.conditionalformattingicon-int) |Cerca l'oggetto specificato e restituisce l'indice a partire da zero dell'ultima occorrenza nell'intervallo di elementi nell'elenco di array che si estende dal primo elemento all'indice specificato.|
| [`last_index_of(self, item, index, count)`](/cells/python-net/it/aspose.cells/conditionalformattingiconcollection/last_index_of/#aspose.cells.conditionalformattingicon-int-int) | Cerca l'oggetto specificato e restituisce l'indice a partire da zero dell'ultima occorrenza nell'intervallo di elementi nell'elenco di array che contiene il numero specificato di elementi e termina all'indice specificato.|
| [`binary_search(self, item)`](/cells/python-net/it/aspose.cells/conditionalformattingiconcollection/binary_search/#aspose.cells.conditionalformattingicon) | Cerca un elemento nell'intero elenco dell'array ordinato utilizzando il comparatore predefinito e restituisce l'indice basato su zero dell'elemento.|



###  Esempio

```python
from aspose.cells import CellArea, FormatConditionType, IconSetType, Workbook

# Instantiating a Workbook object
workbook = Workbook()
sheet = workbook.worksheets[0]
# Get Conditional Formatting
cformattings = sheet.conditional_formattings
# Adds an empty conditional formatting
index = cformattings.add()
# Get newly added Conditional formatting
fcs = cformattings[index]
# Sets the conditional format range.
ca = CellArea()
ca.start_row = 0
ca.end_row = 0
ca.start_column = 0
ca.end_column = 0
fcs.add_area(ca)
ca = CellArea()
ca.start_row = 1
ca.end_row = 1
ca.start_column = 1
ca.end_column = 1
fcs.add_area(ca)
# Sets condition
idx = fcs.add_condition(FormatConditionType.ICON_SET)
cond = fcs[idx]
# Sets condition's type
cond.icon_set.type = IconSetType.ARROWS_GRAY3
# Add custom iconset condition.
cfIcon = cond.icon_set.cf_icons[0]
cfIcon.type = IconSetType.ARROWS3
cfIcon.index = 0
cfIcon1 = cond.icon_set.cf_icons[1]
cfIcon1.type = IconSetType.ARROWS_GRAY3
cfIcon1.index = 1
cfIcon2 = cond.icon_set.cf_icons[2]
cfIcon2.type = IconSetType.BOXES5
cfIcon2.index = 2
# Saving the Excel file
workbook.save("output.xls")

```

###  Guarda anche
* modulo [`aspose.cells`](..)
* classe [`ConditionalFormattingIcon`](/cells/python-net/it/aspose.cells/conditionalformattingicon)
