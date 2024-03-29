---
title: ValidationCollection klass
second_title: Aspose.Cells for Python via .NET API Referenser
description:
type: docs
weight: 1620
url: /sv/aspose.cells/validationcollection/
is_root: false
---
##  ValidationCollection klass
Representerar insamling av datavalidering.



Typen ValidationCollection avslöjar följande medlemmar:

###  Egenskaper
| Fast egendom| Beskrivning|
| :- | :- |
| [capacity](/cells/python-net/sv/aspose.cells/validationcollection/capacity) | Hämtar eller ställer in antalet element som arraylistan kan innehålla.|


###  Metoder
| Metod| Beskrivning|
| :- | :- |
| [add](/cells/python-net/sv/aspose.cells/validationcollection/add/#) | Lägger till en datavalidering i samlingen.|
| [add](/cells/python-net/sv/aspose.cells/validationcollection/add/#aspose.cells.CellArea) | Lägger till en datavalidering i samlingen.|
| [copy_to](/cells/python-net/sv/aspose.cells/validationcollection/copy_to/#list) | Kopierar hela arraylistan till en kompatibel endimensionell arraylista, med början i början av målarraylistan.|
| [copy_to](/cells/python-net/sv/aspose.cells/validationcollection/copy_to/#int-list-int-int) | Kopierar ett intervall av element från arraylistan till en kompatibel endimensionell arraylista, med början vid det angivna indexet för målarraylistan.|
| [index_of](/cells/python-net/sv/aspose.cells/validationcollection/index_of/#aspose.cells.Validation-int) | Söker efter det angivna objektet och returnerar det nollbaserade indexet för den första förekomsten inom intervallet av element i arraylistan som sträcker sig från det angivna indexet till det sista elementet.|
| [index_of](/cells/python-net/sv/aspose.cells/validationcollection/index_of/#aspose.cells.Validation-int-int) |Söker efter det angivna objektet och returnerar det nollbaserade indexet för den första förekomsten inom intervallet av element i arraylistan som börjar vid det angivna indexet och innehåller det angivna antalet element.|
| [last_index_of](/cells/python-net/sv/aspose.cells/validationcollection/last_index_of/#aspose.cells.Validation) | Söker efter det angivna objektet och returnerar det nollbaserade indexet för den senaste förekomsten inom hela arraylistan.|
| [last_index_of](/cells/python-net/sv/aspose.cells/validationcollection/last_index_of/#aspose.cells.Validation-int) | Söker efter det angivna objektet och returnerar det nollbaserade indexet för den senaste förekomsten inom intervallet av element i arraylistan som sträcker sig från det första elementet till det angivna indexet.|
| [last_index_of](/cells/python-net/sv/aspose.cells/validationcollection/last_index_of/#aspose.cells.Validation-int-int) | Söker efter det angivna objektet och returnerar det nollbaserade indexet för den senaste förekomsten inom intervallet av element i arraylistan som innehåller det angivna antalet element och slutar vid det angivna indexet.|
| [remove_a_cell](/cells/python-net/sv/aspose.cells/validationcollection/remove_a_cell/#int-int) | Tar bort alla valideringsinställningar i cellen.|
| [remove_area](/cells/python-net/sv/aspose.cells/validationcollection/remove_area/#aspose.cells.CellArea) | Tar bort alla valideringsinställningar på området..|
| [get_validation_in_cell](/cells/python-net/sv/aspose.cells/validationcollection/get_validation_in_cell/#int-int) | Får valideringen tillämpad på given cell.|
| [binary_search](/cells/python-net/sv/aspose.cells/validationcollection/binary_search/#aspose.cells.Validation) | Söker i hela den sorterade arraylistan efter ett element med hjälp av standardjämföraren och returnerar elementets nollbaserade index.|



###  Exempel

```python
from aspose.cells import CellArea, ValidationType, Workbook

workbook = Workbook()
validations = workbook.worksheets[0].validations
area = CellArea.create_cell_area(0, 0, 1, 1)
validation = validations[validations.add(area)]
validation.type = ValidationType.LIST
validation.formula1 = "a,b,c,d"

```

###  Se även
* modul [`aspose.cells`](..)
