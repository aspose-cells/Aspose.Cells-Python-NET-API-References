---
title: طريقة group_by
second_title: Aspose.Cells for Python via .NET API المراجع
description:
type: docs
weight: 80
url: /ar/aspose.cells.pivot/pivotfield/group_by/
is_root: false
---
##  group_by {#float-bool}
قم بتجميع الحقل تلقائيًا مع داخلي



```python
def group_by(self, interval, new_field):
    ...
```


| معامل| يكتب| وصف|
| :- | :- | :- |
| interval | float | الداخلية للمجموعة.<br/> سيتم تعيين القيمة التلقائية إذا كانت صفرًا،|
| new_field | bool | يشير إلى ما إذا كان سيتم إضافة حقل جديد إلى الجدول المحوري.|


##  group_by {#list-bool}
قم بتجميع الحقل المخصص.



```python
def group_by(self, custom_group_items, new_field):
    ...
```


| معامل| يكتب| وصف|
| :- | :- | :- |
| custom_group_items | list | عناصر المجموعة المخصصة.|
| new_field | bool |يشير إلى ما إذا كان سيتم إضافة حقل جديد إلى الجدول المحوري|


##  group_by {#float-float-float-bool}
قم بتجميع الملف حسب الرقم.



```python
def group_by(self, start, end, interval, new_field):
    ...
```


| معامل| يكتب| وصف|
| :- | :- | :- |
| start | float | قيمة البداية|
| end | float | نهاية القيمة|
| interval | float | الفاصل|
| new_field | bool |يشير إلى ما إذا كان سيتم إضافة حقل جديد إلى الجدول المحوري|


##  group_by {#DateTime-DateTime-list-float-bool}
قم بتجميع الملف حسب أنواع مجموعة التاريخ.



```python
def group_by(self, start, end, groups, interval, first_as_new_field):
    ...
```


| معامل| يكتب| وصف|
| :- | :- | :- |
| start | DateTime | تاريخ البداية|
| end | DateTime | نهاية التاريخ|
| groups | list | أنواع المجموعة|
| interval | float | الفاصل|
| first_as_new_field | bool | يشير إلى ما إذا كان سيتم إضافة حقل جديد إلى الجدول المحوري.<br/> فقط لعنصر المجموعة الأولى.|



###  أنظر أيضا
* الوحدة [`aspose.cells.pivot`](../../)
* فئة [`PivotField`](/cells/python-net/ar/aspose.cells.pivot/pivotfield)
