---
title: طريقة create_safe_sheet_name
second_title: Aspose.Cells for Python via .NET API المراجع
description:
type: docs
weight: 90
url: /ar/aspose.cells/cellshelper/create_safe_sheet_name/
is_root: false
---
##  create_safe_sheet_name(, اسم الاقتراح){#str}
التحقق من اسم الورقة المقدمة وإنشاء اسم صالح عند الحاجة إليه.
إذا كان اسم الورقة المقدمة يتوافق مع قواعد اسم ورقة Excel، فقم بإرجاعها.
وإلا سيتم قطع السلسلة إذا تجاوز الطول الحد الأقصى
وسيتم استبدال الأحرف غير الصالحة بـ ' '، ثم إرجاع قيمة السلسلة المعاد بناؤها.


###  عائدات




```python

@staticmethod
def create_safe_sheet_name(name_proposal):
    ...
```


| معامل| يكتب| وصف|
| :- | :- | :- |
| name_proposal | str | اسم الورقة المراد استخدامها|


##  create_safe_sheet_name(، اسم الاقتراح، استبدال الحرف){#str-char}
التحقق من اسم الورقة المقدمة وإنشاء اسم صالح عند الحاجة إليه.
إذا كان اسم الورقة المقدمة يتوافق مع قواعد اسم ورقة Excel، فقم بإرجاعها.
وإلا سيتم قطع السلسلة إذا تجاوز الطول الحد الأقصى
وسيتم استبدال الأحرف غير الصالحة بالحرف المحدد، ثم إرجاع قيمة السلسلة المعاد بناؤها.


###  عائدات




```python

@staticmethod
def create_safe_sheet_name(name_proposal, replace_char):
    ...
```


| معامل| يكتب| وصف|
| :- | :- | :- |
| name_proposal | str | اسم الورقة المراد استخدامها|
| replace_char | char | الحرف الذي سيتم استخدامه لاستبدال الأحرف غير الصالحة في اسم الورقة المحددة|



###  أنظر أيضا
* الوحدة [`aspose.cells`](../../)
* فئة [`CellsHelper`](/cells/python-net/ar/aspose.cells/cellshelper)
