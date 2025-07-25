---
title: FormatConditionCollection klass
second_title: Aspose.Cells for Python via .NET API Referenser
description:
type: docs
weight: 710
url: /sv/aspose.cells/formatconditioncollection/
is_root: false
---
##  FormatConditionCollection klass
Representerar villkorsstyrd formatering.
FormatConditions kan innehålla upp till tre villkorliga format.



Typen FormatConditionCollection avslöjar följande medlemmar:

###  Egenskaper
| Fast egendom| Beskrivning|
| :- | :- |
| [count](/cells/python-net/sv/aspose.cells/formatconditioncollection/count) | Hämtar antalet villkor.|
| [range_count](/cells/python-net/sv/aspose.cells/formatconditioncollection/range_count) | Hämtar antal villkorligt formaterade områden.|



Hämtar formateringsvillkoret efter index.
###  Indexerare
| Namn| Beskrivning|
| :- | :- |
| [index] | indexet för formateringsvillkoret som ska returneras.|


###  Metoder
| Metod| Beskrivning|
| :- | :- |
| [`add_condition(self, type, operator_type, formula1, formula2)`](/cells/python-net/sv/aspose.cells/formatconditioncollection/add_condition/#aspose.cells.formatconditiontype-aspose.cells.operatortype-str-str) | Lägger till ett formateringsvillkor.|
| [`add_condition(self, type)`](/cells/python-net/sv/aspose.cells/formatconditioncollection/add_condition/#aspose.cells.formatconditiontype) | Lägg till ett formatvillkor.|
| [`remove_area(self, index)`](/cells/python-net/sv/aspose.cells/formatconditioncollection/remove_area/#int) | Tar bort villkorsstyrt formaterat cellområde efter index.|
| [`remove_area(self, start_row, start_column, total_rows, total_columns)`](/cells/python-net/sv/aspose.cells/formatconditioncollection/remove_area/#int-int-int-int) | Ta bort villkorsstyrd formatering i området.|
| [`add(self, cell_area, type, operator_type, formula1, formula2)`](/cells/python-net/sv/aspose.cells/formatconditioncollection/add/#aspose.cells.cellarea-aspose.cells.formatconditiontype-aspose.cells.operatortype-str-str) |Lägger till ett formateringsvillkor och påverkat cellnummer till FormatConditions<br/>FormatConditions kan innehålla upp till tre villkorliga format.<br/> Referenser till andra ark är inte tillåtna i formler för villkorsstyrd formatering.|
| [`add_area(self, cell_area)`](/cells/python-net/sv/aspose.cells/formatconditioncollection/add_area/#aspose.cells.cellarea) | Lägger till ett villkorsstyrt formaterat cellområde.|
| [`get_cell_area(self, index)`](/cells/python-net/sv/aspose.cells/formatconditioncollection/get_cell_area/#int) | Hämtar det villkorsstyrda formaterade cellområdet efter index.|
| [`remove_condition(self, index)`](/cells/python-net/sv/aspose.cells/formatconditioncollection/remove_condition/#int) | Tar bort formateringsvillkoret efter index.|



###  Exempel

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

###  Se även
* modul [`aspose.cells`](..)
