---
title: طريقة group_by
second_title: Aspose.Cells for Python via .NET API المراجع
description:
type: docs
weight: 140
url: /ar/aspose.cells.pivot/pivotfield/group_by/
is_root: false
---
##  group_by(self, interval, new_field) {#float-bool}
تجميع الحقل تلقائيًا مع البيانات الداخلية



```python

def group_by(self, interval, new_field):
    ...
```


| معامل| يكتب| وصف|
| :- | :- | :- |
| interval | float | الجزء الداخلي للمجموعة.<br/> سيتم تعيين القيمة تلقائيًا إذا كانت صفرًا،|
| new_field | bool | يشير إلى ما إذا كان يتم إضافة حقل جديد إلى الجدول المحوري.|


##  group_by(self, custom_group_items, new_field) {#list-bool}
مجموعة مخصصة للحقل.


###  عائدات

خطأ يعني أنه لا يمكن تجميع هذا الحقل حسب التاريخ والوقت.


```python

def group_by(self, custom_group_items, new_field):
    ...
```


| معامل| يكتب| وصف|
| :- | :- | :- |
| custom_group_items | list | عناصر المجموعة المخصصة.|
| new_field | bool | يشير إلى ما إذا كان من الممكن إضافة حقل جديد إلى الجدول المحوري|


##  group_by(self, start, end, interval, new_field) {#float-float-float-bool}
تجميع الملف حسب الرقم.


###  عائدات

خطأ يعني أنه لا يمكن تجميع هذا الحقل حسب التاريخ والوقت.


```python

def group_by(self, start, end, interval, new_field):
    ...
```


| معامل| يكتب| وصف|
| :- | :- | :- |
| start | float | قيمة البداية|
| end | float | نهاية القيمة|
| interval | float | الفاصل الزمني|
| new_field | bool | يشير إلى ما إذا كان من الممكن إضافة حقل جديد إلى الجدول المحوري|


##  group_by(self, start, end, groups, interval, first_as_new_field) {#DateTime-DateTime-list-float-bool}
قم بتجميع الملف حسب أنواع مجموعة التاريخ.


###  عائدات

خطأ يعني أنه لا يمكن تجميع هذا الحقل حسب التاريخ والوقت.


```python

def group_by(self, start, end, groups, interval, first_as_new_field):
    ...
```


| معامل| يكتب| وصف|
| :- | :- | :- |
| start | DateTime | تاريخ ووقت البدء|
| end | DateTime | نهاية التاريخ والوقت|
| groups | list | أنواع المجموعات|
| interval | float | الفاصل الزمني|
| first_as_new_field | bool | يشير إلى ما إذا كان يتم إضافة حقل جديد إلى الجدول المحوري.<br/> فقط للعنصر الأول للمجموعة.|



###  أنظر أيضا
* الوحدة [`aspose.cells.pivot`](../../)
* فئة [`PivotField`](/cells/python-net/ar/aspose.cells.pivot/pivotfield)
