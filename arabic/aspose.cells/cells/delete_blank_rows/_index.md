---
title: طريقة delete_blank_rows
second_title: Aspose.Cells for Python via .NET API المراجع
description:
type: docs
weight: 210
url: /ar/aspose.cells/cells/delete_blank_rows/
is_root: false
---
##  delete_blank_rows(self) {#}
احذف جميع الصفوف الفارغة التي لا تحتوي على أي بيانات أو كائن آخر.



```python

def delete_blank_rows(self):
    ...
```




##  delete_blank_rows(self, options) {#aspose.cells.DeleteOptions}
حذف جميع الصفوف الفارغة التي لا تحتوي على أي بيانات أو بعض الكائنات الخاصة مثل التعليق المرئي أو جدول البيانات المحوري.



```python

def delete_blank_rows(self, options):
    ...
```


| معامل| يكتب| وصف|
| :- | :- | :- |
| options | [`DeleteOptions`](/cells/python-net/ar/aspose.cells/deleteoptions) | خيارات حذف النطاق.|
###  ملاحظات

بالنسبة للصفوف الفارغة التي سيتم حذفها، ليس مطلوبًا فقط أن يكون [`Row.is_blank`](/cells/python-net/ar/aspose.cells/row#is_blank) صحيحًا،
ولكن لا ينبغي أيضًا أن يكون هناك تعليق مرئي محدد لأي خلية في تلك الصفوف،
ولا يوجد جدول محوري يتقاطع نطاقه معهم.


###  أنظر أيضا
* الوحدة [`aspose.cells`](../../)
* فئة [`Cells`](/cells/python-net/ar/aspose.cells/cells)
