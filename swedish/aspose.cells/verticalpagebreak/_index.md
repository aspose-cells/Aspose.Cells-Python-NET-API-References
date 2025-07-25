---
title: VerticalPageBreak klass
second_title: Aspose.Cells for Python via .NET API Referenser
description:
type: docs
weight: 1540
url: /sv/aspose.cells/verticalpagebreak/
is_root: false
---
##  VerticalPageBreak klass
Inkapslar objektet som representerar en vertikal sidbrytning.



Typen VerticalPageBreak avslöjar följande medlemmar:

###  Egenskaper
| Fast egendom| Beskrivning|
| :- | :- |
| [start_row](/cells/python-net/sv/aspose.cells/verticalpagebreak/start_row) | Hämtar startradsindexet för den vertikala sidbrytningen.|
| [end_row](/cells/python-net/sv/aspose.cells/verticalpagebreak/end_row) | Hämtar radslutindexet för den vertikala sidbrytningen.|
| [column](/cells/python-net/sv/aspose.cells/verticalpagebreak/column) | Hämtar kolumnindexet för den vertikala sidbrytningen.|



###  Exempel

```python
from aspose.cells import Workbook

excel = Workbook()
# Add a pagebreak at G5
excel.worksheets[0].horizontal_page_breaks.add("G5")
excel.worksheets[0].vertical_page_breaks.add("G5")

```

###  Se även
* modul [`aspose.cells`](..)
