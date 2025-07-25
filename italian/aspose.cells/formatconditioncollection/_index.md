---
title: FormatConditionCollection classe
second_title: Aspose.Cells for Python via .NET API Riferimenti
description:
type: docs
weight: 710
url: /it/aspose.cells/formatconditioncollection/
is_root: false
---
##  FormatConditionCollection classe
Rappresenta la formattazione condizionale.
FormatConditions può contenere fino a tre formati condizionali.



Il tipo FormatConditionCollection espone i seguenti membri:

###  Proprietà
| Proprietà| Descrizione|
| :- | :- |
| [count](/cells/python-net/it/aspose.cells/formatconditioncollection/count) | Ottiene il conteggio delle condizioni.|
| [range_count](/cells/python-net/it/aspose.cells/formatconditioncollection/range_count) | Ottiene il conteggio degli intervalli formattati in modo condizionale.|



Ottiene la condizione di formattazione tramite indice.
###  Indicizzatore
| Nome| Descrizione|
| :- | :- |
| [index] | l'indice della condizione di formattazione da restituire.|


###  Metodi
| Metodo| Descrizione|
| :- | :- |
| [`add_condition(self, type, operator_type, formula1, formula2)`](/cells/python-net/it/aspose.cells/formatconditioncollection/add_condition/#aspose.cells.formatconditiontype-aspose.cells.operatortype-str-str) | Aggiunge una condizione di formattazione.|
| [`add_condition(self, type)`](/cells/python-net/it/aspose.cells/formatconditioncollection/add_condition/#aspose.cells.formatconditiontype) | Aggiungere una condizione di formato.|
| [`remove_area(self, index)`](/cells/python-net/it/aspose.cells/formatconditioncollection/remove_area/#int) | Rimuove l'intervallo di celle formattato in modo condizionale in base all'indice.|
| [`remove_area(self, start_row, start_column, total_rows, total_columns)`](/cells/python-net/it/aspose.cells/formatconditioncollection/remove_area/#int-int-int-int) | Rimuovi la formattazione condizionale nell'intervallo.|
| [`add(self, cell_area, type, operator_type, formula1, formula2)`](/cells/python-net/it/aspose.cells/formatconditioncollection/add/#aspose.cells.cellarea-aspose.cells.formatconditiontype-aspose.cells.operatortype-str-str) |Aggiunge una condizione di formattazione e l'intervallo di celle interessate a FormatConditions<br/>FormatConditions può contenere fino a tre formati condizionali.<br/> I riferimenti ad altri fogli non sono consentiti nelle formule di formattazione condizionale.|
| [`add_area(self, cell_area)`](/cells/python-net/it/aspose.cells/formatconditioncollection/add_area/#aspose.cells.cellarea) | Aggiunge un intervallo di celle formattato in modo condizionale.|
| [`get_cell_area(self, index)`](/cells/python-net/it/aspose.cells/formatconditioncollection/get_cell_area/#int) | Ottiene l'intervallo di celle formattato in modo condizionale in base all'indice.|
| [`remove_condition(self, index)`](/cells/python-net/it/aspose.cells/formatconditioncollection/remove_condition/#int) | Rimuove la condizione di formattazione tramite indice.|



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
