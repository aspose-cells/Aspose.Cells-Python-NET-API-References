---
title: CellArea klass
second_title: Aspose.Cells for Python via .NET API Referenser
description:
type: docs
weight: 120
url: /sv/aspose.cells/cellarea/
is_root: false
---
##  CellArea klass
Representera ett område med celler.



Typen CellArea avslöjar följande medlemmar:

###  Konstruktörer
| Konstruktör| Beskrivning|
| :- | :- |
| [`__init__(self)`](/cells/python-net/sv/aspose.cells/cellarea/__init__/#) | Konstruerar en ny instans av CellArea|


###  Egenskaper
| Fast egendom| Beskrivning|
| :- | :- |
| [start_row](/cells/python-net/sv/aspose.cells/cellarea/start_row) | Hämtar eller anger startraden för detta område.|
| [end_row](/cells/python-net/sv/aspose.cells/cellarea/end_row) | Hämtar eller anger den sista raden för detta område.|
| [start_column](/cells/python-net/sv/aspose.cells/cellarea/start_column) | Hämtar eller anger startkolumnen för detta område.|
| [end_column](/cells/python-net/sv/aspose.cells/cellarea/end_column) | Hämtar eller anger slutkolumnen för detta område.|


###  Metoder
| Metod| Beskrivning|
| :- | :- |
| [`create_cell_area(, start_row, start_column, end_row, end_column)`](/cells/python-net/sv/aspose.cells/cellarea/create_cell_area/#int-int-int-int) | Skapar ett cellområde.|
| [`create_cell_area(, start_cell_name, end_cell_name)`](/cells/python-net/sv/aspose.cells/cellarea/create_cell_area/#str-str) | Skapar ett cellområde.|
| [`compare_to(self, obj)`](/cells/python-net/sv/aspose.cells/cellarea/compare_to/#any) | Jämför två CellArea-objekt enligt deras övre vänstra hörn.|



###  Exempel

```python
from aspose.cells import CellArea

# Create Cell Area
ca = CellArea()
ca.start_row = 0
ca.end_row = 0
ca.start_column = 0
ca.end_column = 0

```

###  Se även
* modul [`aspose.cells`](..)
