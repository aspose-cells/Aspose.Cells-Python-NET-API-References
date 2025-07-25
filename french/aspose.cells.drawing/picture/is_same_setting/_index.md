---
title: méthode is_same_setting
second_title: Aspose.Cells for Python via .NET API Références
description:
type: docs
weight: 170
url: /fr/aspose.cells.drawing/picture/is_same_setting/
is_root: false
---
##  is_same_setting(self, obj) {#any}
Renvoie si la forme est la même.


###  Retour




```python

def is_same_setting(self, obj):
    ...
```


| Paramètre| Taper| Description|
| :- | :- | :- |
| obj | any |  |

###  Exemple

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



###  Voir également
* module [`aspose.cells.drawing`](../../)
* classe [`Picture`](/cells/python-net/fr/aspose.cells.drawing/picture)
