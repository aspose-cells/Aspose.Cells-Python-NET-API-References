---
title: add_line yöntemi
second_title: Aspose.Cells for Python via .NET API Referanslar
description:
type: docs
weight: 170
url: /tr/aspose.cells.drawing/shapecollection/add_line/
is_root: false
---
##  add_line(self, upper_left_row, top, upper_left_column, left, height, width) {#int-int-int-int-int-int}
Çalışma sayfasına bir Çizgi Şekli ekler.


###  İadeler

Bir LineShape nesnesi.


```python

def add_line(self, upper_left_row, top, upper_left_column, left, height, width):
    ...
```


| Parametre| Tip| Tanım|
| :- | :- | :- |
| upper_left_row | int | Sol üst sıra dizini.|
| top | int | LineShape'in sol satırından dikey uzaklığını piksel cinsinden temsil eder.|
| upper_left_column | int | Sol üst sütun dizini.|
| left | int | LineShape'in sol sütunundan yatay uzaklığını piksel cinsinden temsil eder.|
| height | int | LineShape'in yüksekliğini piksel cinsinden temsil eder.|
| width | int |LineShape'in genişliğini piksel cinsinden temsil eder.|

###  Örnek

```python

#  add a line object
lineShape = shapes.add_line(1, 0, 1, 0, 100, 50)

```



###  Ayrıca bakınız
* modül [`aspose.cells.drawing`](../../)
* sınıf [`ShapeCollection`](/cells/python-net/tr/aspose.cells.drawing/shapecollection)
