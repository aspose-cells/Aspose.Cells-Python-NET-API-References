---
title: max_column_count عقار
second_title: Aspose.Cells for Python via .NET API المراجع
description:
type: docs
weight: 270
url: /ar/aspose.cells/txtloadoptions/max_column_count/
is_root: false
---
##  max_column_count عقار

الحد الأقصى لعدد الأعمدة التي سيتم استيرادها لورقة واحدة.

###  ملاحظات

سيتم تجاهل الأعمدة التي تتجاوز هذا الحد
أو تم تمديدها إلى الورقة التالية وفقًا لـ [`TxtLoadOptions.extend_to_next_sheet`](/cells/python-net/ar/aspose.cells/txtloadoptions#extend_to_next_sheet).
يتضمن هذا العدد أعمدة الرأس ([`TxtLoadOptions.header_columns_count`](/cells/python-net/ar/aspose.cells/txtloadoptions#header_columns_count)).
القيمة القصوى لها هي حد العمود لتنسيق الملف المقابل، مثل ملف xlsx هو 16384.
إذا لم يتم تحديد هذه الخاصية أو كانت القيمة المحددة غير موجبة، فسيتم استخدام الحد الأقصى أيضًا.
###  تعريف:
```python
@property
def max_column_count(self):
    ...
@max_column_count.setter
def max_column_count(self, value):
    ...
```

###  أنظر أيضا
* الوحدة [`aspose.cells`](../../)
* فئة [`TxtLoadOptions`](/cells/python-net/ar/aspose.cells/txtloadoptions)
