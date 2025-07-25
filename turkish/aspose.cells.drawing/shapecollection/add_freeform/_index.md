---
title: add_freeform yöntemi
second_title: Aspose.Cells for Python via .NET API Referanslar
description:
type: docs
weight: 120
url: /tr/aspose.cells.drawing/shapecollection/add_freeform/
is_root: false
---
##  add_freeform(self, upper_left_row, top, upper_left_column, left, height, width, paths) {#int-int-int-int-int-int-list}
Çalışma sayfasına serbest biçimli bir şekil ekler.


###  İadeler

Serbest biçimli bir şekil.


```python

def add_freeform(self, upper_left_row, top, upper_left_column, left, height, width, paths):
    ...
```


| Parametre| Tip| Tanım|
| :- | :- | :- |
| upper_left_row | int | Sol üst sıra dizini.|
| top | int | Serbest biçimli şeklin sol satırından dikey uzaklığını piksel cinsinden temsil eder.|
| upper_left_column | int | Sol üst sütun dizini.|
| left | int | Serbest biçimli şeklin sol sütunundan yatay uzaklığını piksel cinsinden temsil eder.|
| height | int | Serbest biçimli şeklin yüksekliğini piksel cinsinden temsil eder.|
| width | int | Serbest biçimli şeklin genişliğini piksel biriminde temsil eder.|
| paths | list | Kullanıcı tanımlı bir yolu temsil eder|
###  Notlar

Dikkat: Parametrelerdeki genişlik ve yükseklik, 'paths' ile belirtilen ShapePath dizisinin toplam genişliği ve yüksekliği değil, herhangi bir pozitif tam sayı değeri olabilir. Aralarındaki ilişki ölçek-doldurma ilişkisidir; yani her ShapePath nesnesi, genişliğine ve yüksekliğine göre ölçeklendirilir. Bu nedenle, 'paths' içinde birden fazla nesne olduğunda, her ShapePath nesnesinin beklentileri karşılayacak şekilde makul bir şekilde tasarlanması gerekir. Tek bir ShapePath nesnesi olduğunda ve başka bir gereklilik olmadığında, nesnenin genişliğini ve yüksekliğini parametre değerleri olarak geçirmek iyi bir çözümdür.
###  Örnek


```python
from aspose.cells.drawing import ShapePath

# Custom figure
shapePath = ShapePath()
shapePath.move_to(60, 45)
shapePath.arc_to(25, 25, 0, 270)
shapePath.close()
shapePath.move_to(60, 20)
shapePath.line_to(110, 70)
shapePath.line_to(125, 155.5)
shapePath.arc_to(35.5, 35.5, 0, 270)
shapePath.close()
shapePath.move_to(150, 45)
shapePath.arc_to(25, 25, 0, 270)
shapePathW = shapePath.width_pixel
shapePathH = shapePath.height_pixel
shapePath1 = ShapePath()
shapePath1.move_to(0, 0)
shapePath1.cubic_bezier_to(48.24997, 0.6844,                                 96.5, -7.148871,                                 130, 11.517795)
shapePath1.cubic_bezier_to(163.5, 30.18446,                                 182.24997, 75.351,                                 201, 120.517795)
shapePath1.move_to(150, 80)
shapePath1.arc_to(25, 25, 0, 270)
if shapePath1.width_pixel > shapePathW:
    shapePathW = shapePath1.width_pixel
if shapePath1.height_pixel > shapePathH:
    shapePathH = shapePath1.height_pixel
# Notice: shapePathH and shapePathH can be any positive integer values, here we just simply set them.
# Insert custom figure into worksheet
shapes.add_freeform(1, 0, 1, 0, shapePathH, shapePathW, [shapePath, shapePath1])

```



###  Ayrıca bakınız
* modül [`aspose.cells.drawing`](../../)
* sınıf [`ShapeCollection`](/cells/python-net/tr/aspose.cells.drawing/shapecollection)
