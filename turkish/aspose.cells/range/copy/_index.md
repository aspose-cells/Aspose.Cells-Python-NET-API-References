---
title: copy yöntemi
second_title: Aspose.Cells for Python via .NET API Referanslar
description:
type: docs
weight: 100
url: /tr/aspose.cells/range/copy/
is_root: false
---
##  copy(self, range) {#aspose.cells.Range}
Bir kaynak aralığından verileri (formüller dahil), biçimlendirmeyi, çizim nesnelerini vb. kopyalar.



```python

def copy(self, range):
    ...
```


| Parametre| Tip| Tanım|
| :- | :- | :- |
| range | [`Range`](/cells/python-net/tr/aspose.cells/range) | Kaynak [`Range`](/cells/python-net/tr/aspose.cells/range) nesnesi.|

###  Örnek

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


##  copy(self, range, options) {#aspose.cells.Range-aspose.cells.PasteOptions}
Aralığı yapıştırma özel seçenekleriyle kopyalama.



```python

def copy(self, range, options):
    ...
```


| Parametre| Tip| Tanım|
| :- | :- | :- |
| range | [`Range`](/cells/python-net/tr/aspose.cells/range) | Kaynak aralığı.|
| options | [`PasteOptions`](/cells/python-net/tr/aspose.cells/pasteoptions) | Özel yapıştırma seçenekleri.|



###  Ayrıca bakınız
* modül [`aspose.cells`](../../)
* sınıf [`Range`](/cells/python-net/tr/aspose.cells/range)
