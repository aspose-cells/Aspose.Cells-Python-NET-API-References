---
title: copy_in_range yöntemi
second_title: Aspose.Cells for Python via .NET API Referanslar
description:
type: docs
weight: 410
url: /tr/aspose.cells.drawing/shapecollection/copy_in_range/
is_root: false
---
##  copy_in_range(self, source_shapes, ca, dest_row, dest_column, is_contained) {#aspose.cells.drawing.ShapeCollection-aspose.cells.CellArea-int-int-bool}
Aralıktaki şekilleri hedef aralığa kopyala.



```python

def copy_in_range(self, source_shapes, ca, dest_row, dest_column, is_contained):
    ...
```


| Parametre| Tip| Tanım|
| :- | :- | :- |
| source_shapes | [`ShapeCollection`](/cells/python-net/tr/aspose.cells.drawing/shapecollection) | Kaynak şekiller.|
| ca | [`CellArea`](/cells/python-net/tr/aspose.cells/cellarea) | Kaynak aralığı.|
| dest_row | int | Hedef aralığının hedef satır indeksi.|
| dest_column | int | Hedef aralığının hedef sütunu.|
| is_contained | bool | Sadece aralıkta bulunan şekillerin kopyalanması.<br/> Doğruysa, yalnızca aralıktaki şekilleri kopyalar.<br/> Aksi takdirde MS Office olarak çalışır.|

###  Örnek

```python
from aspose.cells import CellArea

# add a shape
shapes.add_rectangle(2, 0, 2, 0, 130, 130)
area2 = CellArea()
area2.start_column = 1
area2.start_row = 1
area2.end_column = 5
area2.end_row = 11
# copy
shapes.copy_in_range(shapes, area2, 12, 1, False)

```



###  Ayrıca bakınız
* modül [`aspose.cells.drawing`](../../)
* sınıf [`ShapeCollection`](/cells/python-net/tr/aspose.cells.drawing/shapecollection)
