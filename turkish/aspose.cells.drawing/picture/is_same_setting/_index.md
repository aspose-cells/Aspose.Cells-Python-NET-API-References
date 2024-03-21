---
title: is_same_setting yöntemi
second_title: Aspose.Cells for Python via .NET API Referanslar
description:
type: docs
weight: 160
url: /tr/aspose.cells.drawing/picture/is_same_setting/
is_root: false
---
##  is_same_setting {#any}
Şeklin aynı olup olmadığını döndürür.


###  İadeler




```python
def is_same_setting(self, obj):
    ...
```


| Parametre| Tip| Tanım|
| :- | :- | :- |
| obj | any |  |

###  Örnek

```python
from aspose.cells import Workbook

# Instantiating a Workbook object
workbook = Workbook()
worksheet = workbook.worksheets[0]
# insert first picture
imgIndex1 = worksheet.pictures.add(1, 1, "1.png")
# Get the inserted picture object
pic1 = worksheet.pictures[imgIndex1]
# insert second picture
imgIndex2 = worksheet.pictures.add(1, 9, "2.jpeg")
# Get the inserted picture object
pic2 = worksheet.pictures[imgIndex2]
if pic1.is_same_setting(pic1):
    pass
if notpic1.is_same_setting(pic2):
    pass

```



###  Ayrıca bakınız
* modül [`aspose.cells.drawing`](../../)
* sınıf [`Picture`](/cells/python-net/tr/aspose.cells.drawing/picture)
