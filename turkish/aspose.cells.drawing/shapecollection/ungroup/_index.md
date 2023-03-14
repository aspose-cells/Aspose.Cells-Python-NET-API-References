---
title: ungroup yöntemi
second_title: Aspose.Cells for Python via .NET API Referanslar
description:
type: docs
weight: 450
url: /tr/aspose.cells.drawing/shapecollection/ungroup/
is_root: false
---
##  ungroup(group) {#GroupShape}
Şekil öğelerinin grubunu çözer.



```python
def ungroup(self, group):
    ...
```


| Parametre| Tip| Tanım|
| :- | :- | :- |
| group | [GroupShape](/cells/python-net/tr/aspose.cells.drawing/groupshape) | Grup şekli.|
###  Notlar

Grup şekli başka bir grup şekli tarafından gruplanırsa hiçbir şey yapılmaz.
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
* modül [aspose.cells.drawing](../../)
* sınıf [ShapeCollection](/cells/python-net/tr/aspose.cells.drawing/shapecollection)
