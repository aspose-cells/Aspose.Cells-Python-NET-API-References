---
title: Metodo is_same_setting
second_title: Aspose.Cells for Python via .NET API Referenze
description:
type: docs
weight: 160
url: /it/aspose.cells.drawing/picture/is_same_setting/
is_root: false
---
##  is_same_setting {#any}
Restituisce se la forma è la stessa.


###  ritorna




```python
def is_same_setting(self, obj):
    ...
```


| Parametro| Tipo| Descrizione|
| :- | :- | :- |
| obj | any |  |

###  Esempio

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



###  Guarda anche
* modulo [`aspose.cells.drawing`](../../)
* classe [`Picture`](/cells/python-net/it/aspose.cells.drawing/picture)
