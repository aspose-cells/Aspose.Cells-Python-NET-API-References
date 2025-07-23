---
title: طريقة add_identify
second_title: Aspose.Cells for Python via .NET API المراجع
description:
type: docs
weight: 20
url: /ar/aspose.cells.pivot/pivotpagefields/add_identify/
is_root: false
---
##  add_identify(self, range_index, page_item_index) {#int-list}
تعيين تسمية العنصر في كل حقل صفحة لاستخدامها لتحديد نطاق البيانات.
يجب أن يكون طول pageItemIndex.Length مساويًا لـ PageFieldCount، لذا يرجى إضافة حقل الصفحة أولاً.



```python

def add_identify(self, range_index, page_item_index):
    ...
```


| معامل| يكتب| وصف|
| :- | :- | :- |
| range_index | int | مؤشر نطاق بيانات التوحيد.|
| page_item_index | list | فهرس عناصر الصفحة في حقل كل صفحة.<br/>pageItemIndex[2] = 1 يعني العنصر الثاني في الحقل الثالث الذي سيتم استخدامه لتحديد هذا النطاق.<br/> pageItemIndex[1] = -1 يعني عدم وجود عنصر في الحقل الثاني لاستخدامه لتحديد هذا النطاق<br/> وسوف يقوم Microsoft تلقائيًا بإنشاء عنصر "فارغ" في الحقل الثاني لتحديد هذا النطاق.|



###  أنظر أيضا
* الوحدة [`aspose.cells.pivot`](../../)
* فئة [`PivotPageFields`](/cells/python-net/ar/aspose.cells.pivot/pivotpagefields)
