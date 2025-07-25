---
title: طريقة characters
second_title: Aspose.Cells for Python via .NET API المراجع
description:
type: docs
weight: 30
url: /ar/aspose.cells/cell/characters/
is_root: false
---
##  characters(self, start_index, length) {#int-int}
يقوم بإرجاع كائن أحرف يمثل نطاق characters داخل نص الخلية.


###  عائدات

كائنات الأحرف.


```python

def characters(self, start_index, length):
    ...
```


| معامل| يكتب| وصف|
| :- | :- | :- |
| start_index | int | مؤشر بداية الحرف.|
| length | int | عدد الأحرف.|
###  ملاحظات

تعمل هذه الطريقة فقط على الخلية ذات القيمة السلسلة.
###  مثال


```python
from aspose.cells import Workbook
from aspose.pydrawing import Color

excel = Workbook()
cells = excel.worksheets[0].cells
cells.get("A1").put_value("Helloworld")
cells.get("A1").characters(5, 5).font.is_bold = True
cells.get("A1").characters(5, 5).font.color = Color.blue

```



###  أنظر أيضا
* الوحدة [`aspose.cells`](../../)
* فئة [`Cell`](/cells/python-net/ar/aspose.cells/cell)
