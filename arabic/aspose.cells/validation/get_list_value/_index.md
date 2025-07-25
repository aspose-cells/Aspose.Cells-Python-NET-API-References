---
title: طريقة get_list_value
second_title: Aspose.Cells for Python via .NET API المراجع
description:
type: docs
weight: 70
url: /ar/aspose.cells/validation/get_list_value/
is_root: false
---
##  get_list_value(self, row, column) {#int-int}
احصل على قيمة لقائمة التحقق للخلية المحددة.


###  عائدات

القيمة لإنتاج قائمة التحقق هذه للخلية المحددة.
إذا كانت القائمة تشير إلى نطاق، فستكون القيمة المرتجعة عبارة عن كائن [`ReferredArea`](/cells/python-net/ar/aspose.cells/referredarea)؛
وإلا فإن القيمة المرتجعة قد تكون null أو object[] أو كائنًا بسيطًا.


```python

def get_list_value(self, row, column):
    ...
```


| معامل| يكتب| وصف|
| :- | :- | :- |
| row | int | مؤشر الصف.|
| column | int | فهرس العمود.|
###  ملاحظات

فقط للتحقق من صحة نوعه "قائمة" وتم تطبيقه على الخلية المحددة،
وإلا سيتم إرجاع القيمة null.


###  أنظر أيضا
* الوحدة [`aspose.cells`](../../)
* فئة [`ReferredArea`](/cells/python-net/ar/aspose.cells/referredarea)
* فئة [`Validation`](/cells/python-net/ar/aspose.cells/validation)
