---
title: طريقة remove_at
second_title: Aspose.Cells for Python via .NET API المراجع
description:
type: docs
weight: 40
url: /ar/aspose.cells/externallinkcollection/remove_at/
is_root: false
---
##  remove_at(self, index) {#int}
إزالة الرابط الخارجي المحدد من المصنف.



```python

def remove_at(self, index):
    ...
```


| معامل| يكتب| وصف|
| :- | :- | :- |
| index | int | فهرس الرابط الخارجي المراد إزالته.|
###  ملاحظات

عند إزالة الرابط الخارجي، سيتم أيضًا إزالة جميع الصيغ التي تشير إليه لأنه
تصبح المراجع غير صالحة.

##  remove_at(self, index, update_references_as_local) {#int-bool}
إزالة الرابط الخارجي المحدد من المصنف.



```python

def remove_at(self, index, update_references_as_local):
    ...
```


| معامل| يكتب| وصف|
| :- | :- | :- |
| index | int | فهرس الرابط الخارجي المراد إزالته.|
| update_references_as_local | bool | ما إذا كان تحديث جميع المراجع للرابط الخارجي المحدد إلى مرجع المصنف الحالي نفسه.<br/> تحقق من [`ExternalLinkCollection.clear`](/cells/python-net/ar/aspose.cells/externallinkcollection/clear) للحصول على مزيد من التفاصيل حول هذه المعلمة.|



###  أنظر أيضا
* الوحدة [`aspose.cells`](../../)
* فئة [`ExternalLinkCollection`](/cells/python-net/ar/aspose.cells/externallinkcollection)
