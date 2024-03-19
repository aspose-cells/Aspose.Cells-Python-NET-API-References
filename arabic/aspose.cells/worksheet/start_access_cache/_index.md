---
title: طريقة start_access_cache
second_title: Aspose.Cells for Python via .NET API المراجع
description:
type: docs
weight: 300
url: /ar/aspose.cells/worksheet/start_access_cache/
is_root: false
---
##  start_access_cache {#aspose.cells.AccessCacheOptions}
يبدأ الجلسة التي تستخدم ذاكرات التخزين المؤقت للوصول إلى البيانات الموجودة في ورقة العمل هذه.



```python
def start_access_cache(self, opts):
    ...
```


| معامل| يكتب| وصف|
| :- | :- | :- |
| opts | [`AccessCacheOptions`](/cells/python-net/ar/aspose.cells/accesscacheoptions) | خيارات الوصول إلى البيانات|
###  ملاحظات

بعد الانتهاء من الدخول للبيانات يجب الرقم [`Worksheet.close_access_cache`](/cells/python-net/ar/aspose.cells/worksheet/close_access_cache)
يمكن استدعاؤها بنفس الخيارات لمسح كافة ذاكرة التخزين المؤقت واستعادة وضع الوصول العادي.


###  أنظر أيضا
* الوحدة [`aspose.cells`](../../)
* فئة [`Worksheet`](/cells/python-net/ar/aspose.cells/worksheet)
