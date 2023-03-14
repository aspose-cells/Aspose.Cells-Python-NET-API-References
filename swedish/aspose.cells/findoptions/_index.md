---
title: FindOptions klass
second_title: Aspose.Cells for Python via .NET API Referenser
description:
type: docs
weight: 630
url: /sv/aspose.cells/findoptions/
is_root: false
---
##  FindOptions klass
Representerar sökalternativ.



Typen FindOptions avslöjar följande medlemmar:

###  Konstruktörer
| Konstruktör| Beskrivning|
| :- | :- |
| [FindOptions()](/cells/python-net/sv/aspose.cells/findoptions/__init__/#) | Konstruerar en ny instans av FindOptions|


###  Egenskaper
| Fast egendom| Beskrivning|
| :- | :- |
| [is_case_sensitive](/cells/python-net/sv/aspose.cells/findoptions/is_case_sensitive) | Indikerar om den sökta strängen är skiftlägeskänslig.|
| [case_sensitive](/cells/python-net/sv/aspose.cells/findoptions/case_sensitive) | Indikerar om den sökta strängen är skiftlägeskänslig.|
| [look_at_type](/cells/python-net/sv/aspose.cells/findoptions/look_at_type) | Titta på typ.|
| [is_range_set](/cells/python-net/sv/aspose.cells/findoptions/is_range_set) | Indikerar om det sökta området är inställt.|
| [search_next](/cells/python-net/sv/aspose.cells/findoptions/search_next) | Sökordning. Sant: sök nästa. Falskt: sök föregående.|
| [search_backward](/cells/python-net/sv/aspose.cells/findoptions/search_backward) | Om du söker bakåt efter celler.|
| [seach_order_by_rows](/cells/python-net/sv/aspose.cells/findoptions/seach_order_by_rows) | Anger om sökordning efter rader eller kolumner.|
| [look_in_type](/cells/python-net/sv/aspose.cells/findoptions/look_in_type) | Titta i typ.|
| [regex_key](/cells/python-net/sv/aspose.cells/findoptions/regex_key) | Indikerar om den sökta nyckeln är regex.<br/>Om sant kommer den sökta nyckeln att tas som regex och tolkas. Annars kommer nyckeln att tolkas enligt reglerna i ms excel.|
| [value_type_sensitive](/cells/python-net/sv/aspose.cells/findoptions/value_type_sensitive) | Anger om den sökta cellvärdetypen ska vara samma som den sökta nyckeln.|
| [style](/cells/python-net/sv/aspose.cells/findoptions/style) | Formatet att söka efter.|
| [convert_numeric_data](/cells/python-net/sv/aspose.cells/findoptions/convert_numeric_data) | Hämtar eller ställer in ett värde som anger om det sökta strängvärdet konverteras till numerisk data.|


###  Metoder
| Metod| Beskrivning|
| :- | :- |
| [get_range()](/cells/python-net/sv/aspose.cells/findoptions/get_range/#) | Hämtar och ställer in det sökta intervallet.|
| [set_range(ca)](/cells/python-net/sv/aspose.cells/findoptions/set_range/#CellArea) | Ställer in det sökta området.|



###  Exempel

```python
from aspose.cells import CellArea, FindOptions, LookInType, Workbook

# Instantiate the workbook object
workbook = Workbook("book1.xls")
# Get Cells collection
cells = workbook.worksheets[0].cells
# Instantiate FindOptions Object
findOptions = FindOptions()
# Create a Cells Area
ca = CellArea()
ca.start_row = 8
ca.start_column = 2
ca.end_row = 17
ca.end_column = 13
# Set cells area for find options
findOptions.set_range(ca)
# Set searching properties
findOptions.search_backward = False
findOptions.seach_order_by_rows = True
findOptions.look_in_type = LookInType.VALUES
# Find the cell with 0 value
cell = cells.find(0, None, findOptions)

```

###  Se även
* modul [aspose.cells](..)
