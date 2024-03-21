---
title: ConditionalFormattingCollection classe
second_title: Aspose.Cells for Python via .NET API Referenze
description:
type: docs
weight: 310
url: /it/aspose.cells/conditionalformattingcollection/
is_root: false
---
##  ConditionalFormattingCollection classe
Incapsula una raccolta di [`FormatCondition`](/cells/python-net/it/aspose.cells/formatcondition) oggetti.



Il tipo ConditionalFormattingCollection espone i seguenti membri:

###  Proprietà
| Proprietà| Descrizione|
| :- | :- |
| [capacity](/cells/python-net/it/aspose.cells/conditionalformattingcollection/capacity) | Ottiene o imposta il numero di elementi che l'elenco di matrici può contenere.|


###  Metodi
| Metodo| Descrizione|
| :- | :- |
| [copy_to](/cells/python-net/it/aspose.cells/conditionalformattingcollection/copy_to/#list) | Copia l'intero elenco di matrici in un elenco di matrici unidimensionali compatibile, a partire dall'inizio dell'elenco di matrici di destinazione.|
| [copy_to](/cells/python-net/it/aspose.cells/conditionalformattingcollection/copy_to/#int-list-int-int) | Copia un intervallo di elementi dall'elenco di matrici a un elenco di matrici unidimensionali compatibile, a partire dall'indice specificato dell'elenco di matrici di destinazione.|
| [index_of](/cells/python-net/it/aspose.cells/conditionalformattingcollection/index_of/#aspose.cells.FormatConditionCollection-int) | Cerca l'oggetto specificato e restituisce l'indice in base zero della prima occorrenza all'interno dell'intervallo di elementi nell'elenco di matrice che si estende dall'indice specificato all'ultimo elemento.|
| [index_of](/cells/python-net/it/aspose.cells/conditionalformattingcollection/index_of/#aspose.cells.FormatConditionCollection-int-int) |Cerca l'oggetto specificato e restituisce l'indice in base zero della prima occorrenza all'interno dell'intervallo di elementi nell'elenco di matrice che inizia in corrispondenza dell'indice specificato e contiene il numero di elementi specificato.|
| [last_index_of](/cells/python-net/it/aspose.cells/conditionalformattingcollection/last_index_of/#aspose.cells.FormatConditionCollection) | Cerca l'oggetto specificato e restituisce l'indice in base zero dell'ultima occorrenza all'interno dell'intero elenco di matrici.|
| [last_index_of](/cells/python-net/it/aspose.cells/conditionalformattingcollection/last_index_of/#aspose.cells.FormatConditionCollection-int) | Cerca l'oggetto specificato e restituisce l'indice in base zero dell'ultima occorrenza all'interno dell'intervallo di elementi nell'elenco di matrice che si estende dal primo elemento all'indice specificato.|
| [last_index_of](/cells/python-net/it/aspose.cells/conditionalformattingcollection/last_index_of/#aspose.cells.FormatConditionCollection-int-int) | Cerca l'oggetto specificato e restituisce l'indice in base zero dell'ultima occorrenza all'interno dell'intervallo di elementi nell'elenco di matrice che contiene il numero di elementi specificato e termina con l'indice specificato.|
| [remove_area](/cells/python-net/it/aspose.cells/conditionalformattingcollection/remove_area/#int-int-int-int) | Rimuovi tutta la formattazione condizionale nell'intervallo.|
| [add](/cells/python-net/it/aspose.cells/conditionalformattingcollection/add/#) | Aggiunge un FormatConditions alla raccolta.|
| [binary_search](/cells/python-net/it/aspose.cells/conditionalformattingcollection/binary_search/#aspose.cells.FormatConditionCollection) | Cerca un elemento nell'intero elenco di array ordinato utilizzando l'operatore di confronto predefinito e restituisce l'indice in base zero dell'elemento.|



###  Esempio

```python
from aspose.cells import CellArea, FormatConditionType, OperatorType, Workbook
from aspose.pydrawing import Color

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
# Add condition.
conditionIndex = fcs.add_condition(FormatConditionType.CELL_VALUE, OperatorType.BETWEEN, "=A2", "100")
# Add condition.
conditionIndex2 = fcs.add_condition(FormatConditionType.CELL_VALUE, OperatorType.BETWEEN, "50", "100")
# Sets the background color.
fc = fcs[conditionIndex]
fc.style.background_color = Color.red
# Saving the Excel file
workbook.save("output.xls")

```

###  Guarda anche
* modulo [`aspose.cells`](..)
* classe [`FormatCondition`](/cells/python-net/it/aspose.cells/formatcondition)
