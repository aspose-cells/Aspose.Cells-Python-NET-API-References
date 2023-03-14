---
title: get_linked_cell yöntemi
second_title: Aspose.Cells for Python via .NET API Referanslar
description:
type: docs
weight: 100
url: /tr/aspose.cells.drawing/oleobject/get_linked_cell/
is_root: false
---
##  get_linked_cell(is_r1c1, is_local) {#bool-bool}
Denetimin değerine bağlı aralığı alır.


###  İadeler

Kontrolün değerine bağlı aralık.


```python
def get_linked_cell(self, is_r1c1, is_local):
    ...
```


| Parametre| Tip| Tanım|
| :- | :- | :- |
| is_r1c1 | bool | Formülün R1C1 olarak biçimlendirilmesi gerekip gerekmediği.|
| is_local | bool | Formülün yerel ayarlara göre biçimlendirilmesi gerekip gerekmediği.|

###  Örnek

```python

# You may get results like '$A$1'
link = shape.get_linked_cell(False, False)

```



###  Ayrıca bakınız
* modül [aspose.cells.drawing](../../)
* sınıf [OleObject](/cells/python-net/tr/aspose.cells.drawing/oleobject)
