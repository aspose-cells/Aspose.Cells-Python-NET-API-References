---
title: HorizontalPageBreak klass
second_title: Aspose.Cells for Python via .NET API Referenser
description:
type: docs
weight: 760
url: /sv/aspose.cells/horizontalpagebreak/
is_root: false
---
##  HorizontalPageBreak klass
Inkapslar objektet som representerar en horisontell sidbrytning.



Typen HorizontalPageBreak avslöjar följande medlemmar:

###  Egenskaper
| Fast egendom| Beskrivning|
| :- | :- |
| [start_column](/cells/python-net/sv/aspose.cells/horizontalpagebreak/start_column) | Hämtar startkolumnindexet för denna horisontella sidbrytning.|
| [end_column](/cells/python-net/sv/aspose.cells/horizontalpagebreak/end_column) | Hämtar indexet för den sista kolumnen för denna horisontella sidbrytning.|
| [row](/cells/python-net/sv/aspose.cells/horizontalpagebreak/row) |Hämtar det nollbaserade radindexet.|



###  Exempel

```python
from aspose.cells import Workbook

# Instantiating a Workbook object
workbook = Workbook()
# Obtaining the reference of the newly added worksheet by passing its sheet index
worksheet = workbook.worksheets[0]
# Add a page break at cell Y30
Index = worksheet.horizontal_page_breaks.add("Y30")
# get the newly added horizontal page break
hPageBreak = worksheet.horizontal_page_breaks[Index]

```

###  Se även
* modul [`aspose.cells`](..)
