---
title: add_scroll_bar yöntemi
second_title: Aspose.Cells for Python via .NET API Referanslar
description:
type: docs
weight: 260
url: /tr/aspose.cells.drawing/shapecollection/add_scroll_bar/
is_root: false
---
##  add_scroll_bar {#int-int-int-int-int-int}
Çalışma sayfasına bir ScrollBar ekler.


###  İadeler

Bir ScrollBar nesnesi.


```python
def add_scroll_bar(self, upper_left_row, top, upper_left_column, left, height, width):
    ...
```


| Parametre| Tip| Tanım|
| :- | :- | :- |
| upper_left_row | int | Sol üst satır dizini.|
| top | int | ScrollBar'ın sol satırından dikey uzaklığını piksel birimi cinsinden temsil eder.|
| upper_left_column | int | Sol üst sütun dizini.|
| left | int | ScrollBar'ın sol sütunundan yatay uzaklığını piksel birimi cinsinden temsil eder.|
| height | int | ScrollBar'ın yüksekliğini piksel birimi cinsinden temsil eder.|
| width | int | ScrollBar'ın genişliğini piksel birimi cinsinden temsil eder.|

###  Örnek

```python

# add a scroll bar
scrollBar = shapes.add_scroll_bar(1, 0, 1, 0, 100, 20)

```



###  Ayrıca bakınız
* modül [`aspose.cells.drawing`](../../)
* sınıf [`ShapeCollection`](/cells/python-net/tr/aspose.cells.drawing/shapecollection)
