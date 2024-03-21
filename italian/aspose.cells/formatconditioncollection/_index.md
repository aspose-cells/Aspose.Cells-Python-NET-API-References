---
title: FormatConditionCollection classe
second_title: Aspose.Cells for Python via .NET API Referenze
description:
type: docs
weight: 730
url: /it/aspose.cells/formatconditioncollection/
is_root: false
---
##  FormatConditionCollection classe
Rappresenta la formattazione condizionale.
Le FormatConditions possono contenere fino a tre formati condizionali.



Il tipo FormatConditionCollection espone i seguenti membri:

###  Proprietà
| Proprietà| Descrizione|
| :- | :- |
| [count](/cells/python-net/it/aspose.cells/formatconditioncollection/count) | Ottiene il conteggio delle condizioni.|
| [range_count](/cells/python-net/it/aspose.cells/formatconditioncollection/range_count) | Ottiene il conteggio degli intervalli formattati in modo condizionale.|



Ottiene la condizione di formattazione in base all'indice.
###  Indicizzatore
| Nome| Descrizione|
| :- | :- |
| [index] |l'indice della condizione di formattazione da restituire.|


###  Metodi
| Metodo| Descrizione|
| :- | :- |
| [add_condition](/cells/python-net/it/aspose.cells/formatconditioncollection/add_condition/#aspose.cells.FormatConditionType-aspose.cells.OperatorType-str-str) | Aggiunge una condizione di formattazione.|
| [add_condition](/cells/python-net/it/aspose.cells/formatconditioncollection/add_condition/#aspose.cells.FormatConditionType) | Aggiungi una condizione di formato.|
| [remove_area](/cells/python-net/it/aspose.cells/formatconditioncollection/remove_area/#int) | Rimuove l'intervallo di celle formattato condizionale in base all'indice.|
| [remove_area](/cells/python-net/it/aspose.cells/formatconditioncollection/remove_area/#int-int-int-int) | Rimuovi la formattazione condizionale nell'intervallo.|
| [add](/cells/python-net/it/aspose.cells/formatconditioncollection/add/#aspose.cells.CellArea-aspose.cells.FormatConditionType-aspose.cells.OperatorType-str-str) | Aggiunge una condizione di formattazione e la cella interessata a FormatConditions<br/>Le FormatConditions possono contenere fino a tre formati condizionali.<br/> Nelle formule di formattazione condizionale non sono ammessi riferimenti ad altri fogli.|
| [add_area](/cells/python-net/it/aspose.cells/formatconditioncollection/add_area/#aspose.cells.CellArea) | Aggiunge un intervallo di celle formattato condizionale.|
| [get_cell_area](/cells/python-net/it/aspose.cells/formatconditioncollection/get_cell_area/#int) | Ottiene l'intervallo di celle formattato condizionale in base all'indice.|
| [remove_condition](/cells/python-net/it/aspose.cells/formatconditioncollection/remove_condition/#int) | Rimuove la condizione di formattazione per indice.|



###  Esempio

```python
from aspose.cells import CellArea, FormatConditionType, OperatorType, Workbook
from aspose.pydrawing import Color

# Create a new Workbook.
workbook = Workbook()
# Get the first worksheet.
sheet = workbook.worksheets[0]
# Adds an empty conditional formatting
index = sheet.conditional_formattings.add()
fcs = sheet.conditional_formattings[index]
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
# Adds condition.
conditionIndex = fcs.add_condition(FormatConditionType.CELL_VALUE, OperatorType.BETWEEN, "=A2", "100")
# Adds condition.
conditionIndex2 = fcs.add_condition(FormatConditionType.CELL_VALUE, OperatorType.BETWEEN, "50", "100")
# Sets the background color.
fc = fcs[conditionIndex]
fc.style.background_color = Color.red
# Saving the Excel file
workbook.save("output.xls")

```

###  Guarda anche
* modulo [`aspose.cells`](..)
