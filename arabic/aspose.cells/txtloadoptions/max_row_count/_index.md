---
title: max_row_count عقار
second_title: Aspose.Cells for Python via .NET API المراجع
description:
type: docs
weight: 280
url: /ar/aspose.cells/txtloadoptions/max_row_count/
is_root: false
---
##  max_row_count عقار

الحد الأقصى لعدد الصفوف التي سيتم استيرادها لورقة واحدة.

###  ملاحظات

سيتم تجاهل الصفوف التي تتجاوز هذا الحد
أو تم تمديدها إلى الورقة التالية وفقًا لـ [`TxtLoadOptions.extend_to_next_sheet`](/cells/python-net/ar/aspose.cells/txtloadoptions#extend_to_next_sheet).
يتضمن هذا العدد صفوف الرأس ([`TxtLoadOptions.header_rows_count`](/cells/python-net/ar/aspose.cells/txtloadoptions#header_rows_count)).
القيمة القصوى المسموح بها هي حد الصف لتنسيق الملف المقابل، مثل ملف xlsx هو 1048576.
إذا لم يتم تحديد هذه الخاصية أو كانت القيمة المحددة غير موجبة، فسيتم استخدام الحد الأقصى أيضًا.
###  تعريف:
```python
@property
def max_row_count(self):
    ...
@max_row_count.setter
def max_row_count(self, value):
    ...
```

###  أنظر أيضا
* الوحدة [`aspose.cells`](../../)
* فئة [`TxtLoadOptions`](/cells/python-net/ar/aspose.cells/txtloadoptions)
