---
title: intersect yöntemi
second_title: Aspose.Cells for Python via .NET API Referanslar
description:
type: docs
weight: 170
url: /tr/aspose.cells/range/intersect/
is_root: false
---
##  intersect(self, range) {#aspose.cells.Range}
İki aralığın dikdörtgen kesişimini temsil eden [`Range`](/cells/python-net/tr/aspose.cells/range) nesnesini döndürür.


###  İadeler

[`Range`](/cells/python-net/tr/aspose.cells/range) nesnesini döndürür


```python

def intersect(self, range):
    ...
```


| Parametre| Tip| Tanım|
| :- | :- | :- |
| range | [`Range`](/cells/python-net/tr/aspose.cells/range) | Kesişen aralık.|
###  Notlar

Eğer iki aralık kesişmiyorsa null döndürür.
###  Örnek


```python
from aspose.cells import Workbook

# Instantiating a Workbook object
workbook = Workbook()
#  Get the first Worksheet Cells.
cells = workbook.worksheets[0].cells
range1 = cells.create_range("A1:A5")
range2 = cells.create_range("A3:A10")
# Get intersected range of the two ranges.
intersectRange = range1.intersect(range2)
# Save the Excel file
workbook.save("book1.xlsm")

```



###  Ayrıca bakınız
* modül [`aspose.cells`](../../)
* sınıf [`Range`](/cells/python-net/tr/aspose.cells/range)
