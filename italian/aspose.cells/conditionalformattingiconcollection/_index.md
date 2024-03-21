---
title: ConditionalFormattingIconCollection classe
second_title: Aspose.Cells for Python via .NET API Referenze
description:
type: docs
weight: 330
url: /it/aspose.cells/conditionalformattingiconcollection/
is_root: false
---
##  ConditionalFormattingIconCollection classe
Rappresenta una raccolta di [`ConditionalFormattingIcon`](/cells/python-net/it/aspose.cells/conditionalformattingicon) oggetti.



Il tipo ConditionalFormattingIconCollection espone i seguenti membri:

###  Proprietà
| Proprietà| Descrizione|
| :- | :- |
| [capacity](/cells/python-net/it/aspose.cells/conditionalformattingiconcollection/capacity) | Ottiene o imposta il numero di elementi che l'elenco di matrici può contenere.|


###  Metodi
| Metodo| Descrizione|
| :- | :- |
| [add](/cells/python-net/it/aspose.cells/conditionalformattingiconcollection/add/#aspose.cells.IconSetType-int) | Aggiunge l'oggetto [`ConditionalFormattingIcon`](/cells/python-net/it/aspose.cells/conditionalformattingicon).|
| [add](/cells/python-net/it/aspose.cells/conditionalformattingiconcollection/add/#aspose.cells.ConditionalFormattingIcon) | Aggiunge l'oggetto [`ConditionalFormattingIcon`](/cells/python-net/it/aspose.cells/conditionalformattingicon).|
| [copy_to](/cells/python-net/it/aspose.cells/conditionalformattingiconcollection/copy_to/#list) | Copia l'intero elenco di matrici in un elenco di matrici unidimensionali compatibile, a partire dall'inizio dell'elenco di matrici di destinazione.|
| [copy_to](/cells/python-net/it/aspose.cells/conditionalformattingiconcollection/copy_to/#int-list-int-int) | Copia un intervallo di elementi dall'elenco di matrici a un elenco di matrici unidimensionali compatibile, a partire dall'indice specificato dell'elenco di matrici di destinazione.|
| [index_of](/cells/python-net/it/aspose.cells/conditionalformattingiconcollection/index_of/#aspose.cells.ConditionalFormattingIcon-int) | Cerca l'oggetto specificato e restituisce l'indice in base zero della prima occorrenza all'interno dell'intervallo di elementi nell'elenco di matrice che si estende dall'indice specificato all'ultimo elemento.|
| [index_of](/cells/python-net/it/aspose.cells/conditionalformattingiconcollection/index_of/#aspose.cells.ConditionalFormattingIcon-int-int) |Cerca l'oggetto specificato e restituisce l'indice in base zero della prima occorrenza all'interno dell'intervallo di elementi nell'elenco di matrice che inizia in corrispondenza dell'indice specificato e contiene il numero di elementi specificato.|
| [last_index_of](/cells/python-net/it/aspose.cells/conditionalformattingiconcollection/last_index_of/#aspose.cells.ConditionalFormattingIcon) | Cerca l'oggetto specificato e restituisce l'indice in base zero dell'ultima occorrenza all'interno dell'intero elenco di matrici.|
| [last_index_of](/cells/python-net/it/aspose.cells/conditionalformattingiconcollection/last_index_of/#aspose.cells.ConditionalFormattingIcon-int) | Cerca l'oggetto specificato e restituisce l'indice in base zero dell'ultima occorrenza all'interno dell'intervallo di elementi nell'elenco di matrice che si estende dal primo elemento all'indice specificato.|
| [last_index_of](/cells/python-net/it/aspose.cells/conditionalformattingiconcollection/last_index_of/#aspose.cells.ConditionalFormattingIcon-int-int) | Cerca l'oggetto specificato e restituisce l'indice in base zero dell'ultima occorrenza all'interno dell'intervallo di elementi nell'elenco di matrice che contiene il numero di elementi specificato e termina con l'indice specificato.|
| [binary_search](/cells/python-net/it/aspose.cells/conditionalformattingiconcollection/binary_search/#aspose.cells.ConditionalFormattingIcon) | Cerca un elemento nell'intero elenco di array ordinato utilizzando l'operatore di confronto predefinito e restituisce l'indice in base zero dell'elemento.|



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
