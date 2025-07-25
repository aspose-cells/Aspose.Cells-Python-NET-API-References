---
title: Top10 klass
second_title: Aspose.Cells for Python via .NET API Referenser
description:
type: docs
weight: 1460
url: /sv/aspose.cells/top10/
is_root: false
---
##  Top10 klass
 Beskriv regeln för villkorlig formatering Top10.
Denna regel för villkorlig formatering markerar celler vars
värden faller inom den övre N- eller nedre N-parentesen, enligt anvisningarna.



Typen Top10 avslöjar följande medlemmar:

###  Konstruktörer
| Konstruktör| Beskrivning|
| :- | :- |
| [`__init__(self)`](/cells/python-net/sv/aspose.cells/top10/__init__/#) | Konstruerar en ny instans av Top10|


###  Egenskaper
| Fast egendom| Beskrivning|
| :- | :- |
| [is_percent](/cells/python-net/sv/aspose.cells/top10/is_percent) | Hämta eller ange om en "topp/botten n"-regel är en "topp/botten n procent"-regel.<br/> Standardvärdet är falskt.|
| [is_bottom](/cells/python-net/sv/aspose.cells/top10/is_bottom) | Hämta eller ange om en "topp/botten n"-regel är en "botten n"-regel.<br/> Standardvärdet är falskt.|
| [rank](/cells/python-net/sv/aspose.cells/top10/rank) | Hämta eller ange värdet för "n" i en villkorsstyrd formateringsregel för "övre/nedre n".<br/>Om IsPercent är sant måste värdet vara mellan 0 och 100.<br/>Annars måste det vara mellan 0 och 1000.<br/> Standardvärdet är 10.|



###  Exempel

```python
from aspose.cells import CellArea, FormatConditionType, OperatorType, Workbook
from aspose.pydrawing import Color

# Instantiating a Workbook object
workbook = Workbook()
sheet = workbook.worksheets[0]
# Adds an empty conditional formatting
index = sheet.conditional_formattings.add()
fcs = sheet.conditional_formattings[index]
# Sets the conditional format range.
ca = CellArea.create_cell_area(0, 0, 10, 10)
fcs.add_area(ca)
# Adds condition.
conditionIndex = fcs.add_condition(FormatConditionType.TOP10, OperatorType.NONE, None, None)
# Sets the background color.
fc = fcs[conditionIndex]
fc.style.background_color = Color.red
top10 = fc.top10
# Set the Top N
top10.rank = 5
# Saving the Excel file
workbook.save("output.xls")

```

###  Se även
* modul [`aspose.cells`](..)
