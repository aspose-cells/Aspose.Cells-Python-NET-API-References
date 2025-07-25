---
title: طريقة add_signature_line
second_title: Aspose.Cells for Python via .NET API المراجع
description:
type: docs
weight: 310
url: /ar/aspose.cells.drawing/shapecollection/add_signature_line/
is_root: false
---
##  add_signature_line(self, upper_left_row, upper_left_column, signature_line) {#int-int-aspose.cells.drawing.SignatureLine}
إضافة سطر التوقيع إلى ورقة العمل.


###  عائدات




```python

def add_signature_line(self, upper_left_row, upper_left_column, signature_line):
    ...
```


| معامل| يكتب| وصف|
| :- | :- | :- |
| upper_left_row | int | مؤشر الصف العلوي الأيسر.|
| upper_left_column | int | فهرس العمود العلوي الأيسر.|
| signature_line | [`SignatureLine`](/cells/python-net/ar/aspose.cells.drawing/signatureline) | يمثل كائن خط التوقيع.|

###  مثال

```python
from aspose.cells.drawing import SignatureLine

wSignatureLine = SignatureLine()
wSignatureLine.allow_comments = True
wSignatureLine.email = "example@example.com"
wSignatureLine.instructions = "Sign to confirm the excel content."
wSignatureLine.is_line = True
wSignatureLine.show_signed_date = True
wSignatureLine.signer = "User"
wSignatureLine.title = "tester"
# wSignatureLine.SignatureLineType = SignatureType.Stamp;
signatureLine1 = shapes.add_signature_line(0, 0, wSignatureLine)

```



###  أنظر أيضا
* الوحدة [`aspose.cells.drawing`](../../)
* فئة [`ShapeCollection`](/cells/python-net/ar/aspose.cells.drawing/shapecollection)
