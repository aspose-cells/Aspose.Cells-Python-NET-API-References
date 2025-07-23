---
title: طريقة start_access_cache
second_title: Aspose.Cells for Python via .NET API المراجع
description:
type: docs
weight: 400
url: /ar/aspose.cells/workbook/start_access_cache/
is_root: false
---
##  start_access_cache(self, opts) {#aspose.cells.AccessCacheOptions}
بدء الجلسة التي تستخدم ذاكرة التخزين المؤقت للوصول إلى البيانات.



```python

def start_access_cache(self, opts):
    ...
```


| معامل| يكتب| وصف|
| :- | :- | :- |
| opts | [`AccessCacheOptions`](/cells/python-net/ar/aspose.cells/accesscacheoptions) | خيارات الوصول إلى البيانات|
###  ملاحظات

إذا كانت ذاكرة التخزين المؤقت لوصول البيانات المحددة تتطلب أن تكون بعض نماذج البيانات في ورقة العمل "للقراءة فقط"،
ثم سيتم اعتبار نماذج البيانات المقابلة في كل ورقة عمل في هذا المصنف "للقراءة فقط"
ويجب على المستخدم عدم تغيير أي منها.


بعد الانتهاء من الوصول إلى البيانات، يجب الاتصال بالرقم [`Workbook.close_access_cache`](/cells/python-net/ar/aspose.cells/workbook/close_access_cache)
يمكن استدعاؤها بنفس الخيارات لمسح كافة ذاكرات التخزين المؤقت واستعادة وضع الوصول العادي.


###  أنظر أيضا
* الوحدة [`aspose.cells`](../../)
* فئة [`Workbook`](/cells/python-net/ar/aspose.cells/workbook)
