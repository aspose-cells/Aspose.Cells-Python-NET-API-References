---
title: طريقة get_enumerator
second_title: Aspose.Cells for Python via .NET API المراجع
description:
type: docs
weight: 100
url: /ar/aspose.cells/range/get_enumerator/
is_root: false
---
##  get_enumerator {#}
الحصول على العداد للخلايا الموجودة في هذا النطاق.


###  عائدات

عداد الخلايا


```python
def get_enumerator(self):
    ...
```


###  ملاحظات

عند اجتياز العناصر بواسطة العداد الذي تم إرجاعه، فإن مجموعة الخلايا
لا ينبغي تعديلها (مثل العمليات التي ستتسبب في إنشاء مثيل Cell/صف جديد أو حذف Cell/صف موجود).
وإلا فقد لا يتمكن العداد من اجتياز جميع الخلايا بشكل صحيح (قد يتم اجتياز بعض العناصر بشكل متكرر أو تخطيها).
###  مثال

```python
from aspose.cells import Workbook

workbook = Workbook("template.xlsx")
cells = workbook.worksheets[0].cells
en = cells.create_range("B2:C3").get_enumerator()
for cell in en:
    print(cell.name + ": "  + str(cell.value))

```



###  أنظر أيضا
* الوحدة [`aspose.cells`](../../)
* فئة [`Range`](/cells/python-net/ar/aspose.cells/range)
