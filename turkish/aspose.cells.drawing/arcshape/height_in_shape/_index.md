---
title: height_in_shape mülk
second_title: Aspose.Cells for Python via .NET API Referanslar
description:
type: docs
weight: 500
url: /tr/aspose.cells.drawing/arcshape/height_in_shape/
is_root: false
---
##  height_in_shape mülk

Ana şeklin üst sınırından şeklin dikey uzaklığını, ana şeklin yüksekliğinin 1/4000'i biriminde temsil eder.

###  Notlar

Yalnızca bu şekil grupta veya grafikte olduğunda geçerlidir.

###  Örnek

```python

if shape.is_in_group and shape.height_in_shape == 4000:
    shape.height_in_shape = 2000

```
###  Tanım:
```python
@property
def height_in_shape(self):
    ...
@height_in_shape.setter
def height_in_shape(self, value):
    ...
```

###  Ayrıca bakınız
* modül [`aspose.cells.drawing`](../../)
* sınıf [`ArcShape`](/cells/python-net/tr/aspose.cells.drawing/arcshape)
