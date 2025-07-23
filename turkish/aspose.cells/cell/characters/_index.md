---
title: characters yöntemi
second_title: Aspose.Cells for Python via .NET API Referanslar
description:
type: docs
weight: 30
url: /tr/aspose.cells/cell/characters/
is_root: false
---
##  characters(self, start_index, length) {#int-int}
Hücre metni içinde characters aralığını temsil eden bir Characters nesnesi döndürür.


###  İadeler

Karakter nesnesi.


```python

def characters(self, start_index, length):
    ...
```


| Parametre| Tip| Tanım|
| :- | :- | :- |
| start_index | int | Karakterin başlangıcının indeksi.|
| length | int | Karakter sayısı.|
###  Notlar

Bu yöntem yalnızca string değeri olan hücrelerde çalışır.
###  Örnek


```python
from aspose.cells import Workbook
from aspose.pydrawing import Color

excel = Workbook()
cells = excel.worksheets[0].cells
cells.get("A1").put_value("Helloworld")
cells.get("A1").characters(5, 5).font.is_bold = True
cells.get("A1").characters(5, 5).font.color = Color.blue

```



###  Ayrıca bakınız
* modül [`aspose.cells`](../../)
* sınıf [`Cell`](/cells/python-net/tr/aspose.cells/cell)
