---
title: copy yöntemi
second_title: Aspose.Cells for Python via .NET API Referanslar
description:
type: docs
weight: 50
url: /tr/aspose.cells/range/copy/
is_root: false
---
##  copy {#aspose.cells.Range}
Kaynak aralığından verileri (formüller dahil), biçimlendirmeyi, çizim nesnelerini vb. kopyalar.



```python
def copy(self, range):
    ...
```


| Parametre| Tip| Tanım|
| :- | :- | :- |
| range | [`Range`](/cells/python-net/tr/aspose.cells/range) |Kaynak [`Range`](/cells/python-net/tr/aspose.cells/range) nesnesi.|

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


##  copy {#aspose.cells.Range-aspose.cells.PasteOptions}
Aralığın özel yapıştırma seçenekleriyle kopyalanması.



```python
def copy(self, range, options):
    ...
```


| Parametre| Tip| Tanım|
| :- | :- | :- |
| range | [`Range`](/cells/python-net/tr/aspose.cells/range) | Kaynak aralığı.|
| options | [`PasteOptions`](/cells/python-net/tr/aspose.cells/pasteoptions) | Yapıştırma özel seçenekleri.|



###  Ayrıca bakınız
* modül [`aspose.cells`](../../)
* sınıf [`Range`](/cells/python-net/tr/aspose.cells/range)
