---
title: طريقة freeze_panes
second_title: Aspose.Cells for Python via .NET API المراجع
description:
type: docs
weight: 140
url: /ar/aspose.cells/worksheet/freeze_panes/
is_root: false
---
##  freeze_panes {#str-int-int}
تجميد الأجزاء في الخلية المحددة في ورقة العمل.



```python
def freeze_panes(self, cell_name, freezed_rows, freezed_columns):
    ...
```


| معامل| يكتب| وصف|
| :- | :- | :- |
| cell_name | str | الاسم Cell.|
| freezed_rows | int | عدد الصفوف المرئية في الجزء العلوي، لا يزيد عن فهرس الصفوف.|
| freezed_columns | int | عدد الأعمدة المرئية في الجزء الأيمن، لا يزيد عن فهرس العمود.|
###  ملاحظات

لا يمكن أن يكون فهرس الصف وفهرس العمود صفرًا. عدد الصفوف وعدد الأعمدة
كما لا يمكن أن يكون كل شيء صفرًا.

##  freeze_panes {#int-int-int-int}
تجميد الأجزاء في الخلية المحددة في ورقة العمل.



```python
def freeze_panes(self, row, column, freezed_rows, freezed_columns):
    ...
```


| معامل| يكتب| وصف|
| :- | :- | :- |
| row | int | مؤشر الصف.|
| column | int | مؤشر العمود.|
| freezed_rows | int | عدد الصفوف المرئية في الجزء العلوي، لا يزيد عن فهرس الصفوف.|
| freezed_columns | int | عدد الأعمدة المرئية في الجزء الأيمن، لا يزيد عن فهرس العمود.|
###  ملاحظات

لا يمكن أن يكون فهرس الصف وفهرس العمود صفرًا. عدد الصفوف وعدد الأعمدة
كما لا يمكن أن يكون كل شيء صفرًا.


تحدد المعلمتان الأوليان موضع التجميد وتحدد المعلمتان الأخيرتان المنطقة المجمدة في الجزء العلوي الأيسر.


###  أنظر أيضا
* الوحدة [`aspose.cells`](../../)
* فئة [`Worksheet`](/cells/python-net/ar/aspose.cells/worksheet)
