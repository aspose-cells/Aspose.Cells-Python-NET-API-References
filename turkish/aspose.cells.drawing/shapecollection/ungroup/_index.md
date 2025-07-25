---
title: ungroup yöntemi
second_title: Aspose.Cells for Python via .NET API Referanslar
description:
type: docs
weight: 500
url: /tr/aspose.cells.drawing/shapecollection/ungroup/
is_root: false
---
##  ungroup(self, group) {#aspose.cells.drawing.GroupShape}
Şekil öğelerini gruplandırmayı kaldırır.



```python

def ungroup(self, group):
    ...
```


| Parametre| Tip| Tanım|
| :- | :- | :- |
| group | [`GroupShape`](/cells/python-net/tr/aspose.cells.drawing/groupshape) | Grup şekli.|
###  Notlar

Eğer grup şekli başka bir grup şekli tarafından gruplandırılırsa hiçbir şey yapılmayacaktır.
###  Örnek


```python

# add first shape
shapes.add_rectangle(2, 0, 2, 0, 50, 50)
# add second shape
shapes.add_rectangle(6, 0, 2, 0, 30, 30)
# group
shapesArr = [shapes[0], shapes[1]]
groupShape = shapes.group(shapesArr)
# ungroup
shapes.ungroup(groupShape)

```



###  Ayrıca bakınız
* modül [`aspose.cells.drawing`](../../)
* sınıf [`ShapeCollection`](/cells/python-net/tr/aspose.cells.drawing/shapecollection)
