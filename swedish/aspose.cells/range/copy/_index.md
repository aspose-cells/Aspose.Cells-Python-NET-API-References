---
title: copy metod
second_title: Aspose.Cells for Python via .NET API Referenser
description:
type: docs
weight: 50
url: /sv/aspose.cells/range/copy/
is_root: false
---
##  copy {#aspose.cells.Range}
Kopierar data (inklusive formler), formatering, rita objekt etc. från ett källområde.



```python
def copy(self, range):
    ...
```


| Parameter| Typ| Beskrivning|
| :- | :- | :- |
| range | [`Range`](/cells/python-net/sv/aspose.cells/range) |Källa [`Range`](/cells/python-net/sv/aspose.cells/range) objekt.|

###  Exempel

```python
from aspose.cells import Workbook

# Instantiating a Workbook object
workbook = Workbook()
#  Get the first Worksheet Cells.
cells = workbook.worksheets[0].cells
range1 = cells.create_range("A1:A5")
range2 = cells.create_range("A6:A10")
# Copy the range.
range1.copy(range2)
# Save the Excel file
workbook.save("book1.xlsm")

```


##  copy {#aspose.cells.Range-aspose.cells.PasteOptions}
Kopiera intervallet med specialalternativ för klistra in.



```python
def copy(self, range, options):
    ...
```


| Parameter| Typ| Beskrivning|
| :- | :- | :- |
| range | [`Range`](/cells/python-net/sv/aspose.cells/range) | Källomfånget.|
| options | [`PasteOptions`](/cells/python-net/sv/aspose.cells/pasteoptions) | Klistra specialalternativ.|



###  Se även
* modul [`aspose.cells`](../../)
* klass [`Range`](/cells/python-net/sv/aspose.cells/range)
