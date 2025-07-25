---
title: add_active_x_control yöntemi
second_title: Aspose.Cells for Python via .NET API Referanslar
description:
type: docs
weight: 20
url: /tr/aspose.cells.drawing/shapecollection/add_active_x_control/
is_root: false
---
##  add_active_x_control(self, type, top_row, top, left_column, left, width, height) {#aspose.cells.drawing.activexcontrols.ControlType-int-int-int-int-int-int}
Bir Activex Denetimi oluşturur.


###  İadeler




```python

def add_active_x_control(self, type, top_row, top, left_column, left, width, height):
    ...
```


| Parametre| Tip| Tanım|
| :- | :- | :- |
| type | aspose.cells.drawing.activexcontrols.ControlType | Kontrolün türü.|
| top_row | int | Sol üst sıra dizini.|
| top | int | Şeklin sol satırından dikey uzaklığını piksel cinsinden temsil eder.|
| left_column | int | Sol üst sütun dizini.|
| left | int | Şeklin sol sütunundan yatay uzaklığını piksel cinsinden temsil eder.|
| width | int | Şeklin genişliğini piksel cinsinden temsil eder.|
| height | int | Şeklin yüksekliğini piksel cinsinden temsil eder.|

###  Örnek

```python
from aspose.cells.drawing.activexcontrols import ControlType

# add an ActiveX control
activeXControl = shapes.add_active_x_control(ControlType.CHECK_BOX, 1, 0, 1, 0, 100, 50)

```



###  Ayrıca bakınız
* modül [`aspose.cells.drawing`](../../)
* sınıf [`ShapeCollection`](/cells/python-net/tr/aspose.cells.drawing/shapecollection)
