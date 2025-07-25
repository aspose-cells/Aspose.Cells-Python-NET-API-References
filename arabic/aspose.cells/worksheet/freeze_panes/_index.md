---
title: طريقة freeze_panes
second_title: Aspose.Cells for Python via .NET API المراجع
description:
type: docs
weight: 140
url: /ar/aspose.cells/worksheet/freeze_panes/
is_root: false
---
##  freeze_panes(self, cell_name, freezed_rows, freezed_columns) {#str-int-int}
يقوم بتجميد الأجزاء عند الخلية المحددة في ورقة العمل.



```python

def freeze_panes(self, cell_name, freezed_rows, freezed_columns):
    ...
```


| معامل| يكتب| وصف|
| :- | :- | :- |
| cell_name | str | Cell الاسم.|
| freezed_rows | int | عدد الصفوف المرئية في الجزء العلوي، لا يزيد عن مؤشر الصف.|
| freezed_columns | int | عدد الأعمدة المرئية في الجزء الأيسر، لا يزيد عن فهرس العمود.|
###  ملاحظات

لا يمكن أن يكون مؤشر الصف ومؤشر العمود صفرًا. عدد الصفوف وعدد الأعمدة
أيضا لا يمكن أن تكون كلها صفر.

##  freeze_panes(self, row, column, freezed_rows, freezed_columns) {#int-int-int-int}
يقوم بتجميد الأجزاء عند الخلية المحددة في ورقة العمل.



```python

def freeze_panes(self, row, column, freezed_rows, freezed_columns):
    ...
```


| معامل| يكتب| وصف|
| :- | :- | :- |
| row | int | مؤشر الصف.|
| column | int | فهرس العمود.|
| freezed_rows | int | عدد الصفوف المرئية في الجزء العلوي، لا يزيد عن مؤشر الصف.|
| freezed_columns | int | عدد الأعمدة المرئية في الجزء الأيسر، لا يزيد عن فهرس العمود.|
###  ملاحظات

لا يمكن أن يكون مؤشر الصف ومؤشر العمود صفرًا. عدد الصفوف وعدد الأعمدة
أيضا لا يمكن أن تكون كلها صفر.


يحدد المعاملان الأولان الموضع المتجمد ويحدد المعاملان الأخيران المنطقة المجمدة في الجزء العلوي الأيسر.


###  أنظر أيضا
* الوحدة [`aspose.cells`](../../)
* فئة [`Worksheet`](/cells/python-net/ar/aspose.cells/worksheet)
