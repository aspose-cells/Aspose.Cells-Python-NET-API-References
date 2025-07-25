---
title: characters metod
second_title: Aspose.Cells for Python via .NET API Referenser
description:
type: docs
weight: 30
url: /sv/aspose.cells/cell/characters/
is_root: false
---
##  characters(self, start_index, length) {#int-int}
Returnerar ett Characters-objekt som representerar ett intervall på characters i celltexten.


###  Returnerar

Teckenobjekt.


```python

def characters(self, start_index, length):
    ...
```


| Parameter| Typ| Beskrivning|
| :- | :- | :- |
| start_index | int | Indexet för början av tecknet.|
| length | int | Antalet tecken.|
###  Anmärkningar

Den här metoden fungerar bara på celler med strängvärden.
###  Exempel


```python
from aspose.cells import Workbook
from aspose.pydrawing import Color

excel = Workbook()
cells = excel.worksheets[0].cells
cells.get("A1").put_value("Helloworld")
cells.get("A1").characters(5, 5).font.is_bold = True
cells.get("A1").characters(5, 5).font.color = Color.blue

```



###  Se även
* modul [`aspose.cells`](../../)
* klass [`Cell`](/cells/python-net/sv/aspose.cells/cell)
