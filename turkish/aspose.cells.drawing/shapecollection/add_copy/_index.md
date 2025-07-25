---
title: add_copy yöntemi
second_title: Aspose.Cells for Python via .NET API Referanslar
description:
type: docs
weight: 90
url: /tr/aspose.cells.drawing/shapecollection/add_copy/
is_root: false
---
##  add_copy(self, source_shape, top_row, top, left_column, left) {#aspose.cells.drawing.Shape-int-int-int-int}
Çalışma sayfasına bir şekil ekler ve kopyalar.


###  İadeler

Yeni [`Shape`](/cells/python-net/tr/aspose.cells.drawing/shape) nesnesi.


```python

def add_copy(self, source_shape, top_row, top, left_column, left):
    ...
```


| Parametre| Tip| Tanım|
| :- | :- | :- |
| source_shape | [`Shape`](/cells/python-net/tr/aspose.cells.drawing/shape) | Kaynak şekli.|
| top_row | int |Üst sıra indeksi.|
| top | int | En üst satırından itibaren dikey uzaklığı piksel cinsinden gösterir.|
| left_column | int | Sol sütun dizini.|
| left | int | Sol sütundan yatay uzaklığı piksel cinsinden gösterir.|

###  Örnek

```python

# add a shape
rectangle = shapes.add_rectangle(2, 0, 2, 0, 130, 130)
# Adds and copies a shape.
shapes.add_copy(rectangle, 7, 0, 7, 0)

```



###  Ayrıca bakınız
* modül [`aspose.cells.drawing`](../../)
* sınıf [`Shape`](/cells/python-net/tr/aspose.cells.drawing/shape)
* sınıf [`ShapeCollection`](/cells/python-net/tr/aspose.cells.drawing/shapecollection)
