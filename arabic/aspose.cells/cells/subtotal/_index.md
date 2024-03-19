---
title: طريقة subtotal
second_title: Aspose.Cells for Python via .NET API المراجع
description:
type: docs
weight: 910
url: /ar/aspose.cells/cells/subtotal/
is_root: false
---
##  subtotal {#aspose.cells.CellArea-int-aspose.cells.ConsolidationFunction-list}
إنشاء إجماليات فرعية للنطاق.



```python
def subtotal(self, ca, group_by, function, total_list):
    ...
```


| معامل| يكتب| وصف|
| :- | :- | :- |
| ca | [`CellArea`](/cells/python-net/ar/aspose.cells/cellarea) | النطاق|
| group_by | int | الحقل الذي سيتم التجميع حسبه، كإزاحة عدد صحيح يستند إلى صفر|
| function | [`ConsolidationFunction`](/cells/python-net/ar/aspose.cells/consolidationfunction) | دالة المجموع الفرعي|
| total_list | list | مصفوفة من إزاحات الحقول المستندة إلى الصفر، تشير إلى الحقول التي تتم إضافة الإجماليات الفرعية إليها.|


##  subtotal {#aspose.cells.CellArea-int-aspose.cells.ConsolidationFunction-list-bool-bool-bool}
إنشاء إجماليات فرعية للنطاق.



```python
def subtotal(self, ca, group_by, function, total_list, replace, page_breaks, summary_below_data):
    ...
```


| معامل| يكتب| وصف|
| :- | :- | :- |
| ca | [`CellArea`](/cells/python-net/ar/aspose.cells/cellarea) | النطاق|
| group_by | int | الحقل الذي سيتم التجميع حسبه، كإزاحة عدد صحيح يستند إلى صفر|
| function | [`ConsolidationFunction`](/cells/python-net/ar/aspose.cells/consolidationfunction) | دالة المجموع الفرعي|
| total_list | list | مصفوفة من إزاحات الحقول المستندة إلى الصفر، تشير إلى الحقول التي تتم إضافة الإجماليات الفرعية إليها.|
| replace | bool | يشير إلى ما إذا كان سيتم استبدال الإجماليات الفرعية الحالية|
| page_breaks | bool | يشير إلى ما إذا كان سيتم إضافة فاصل صفحات بين المجموعات|
| summary_below_data | bool | يشير إلى ما إذا كان سيتم إضافة ملخص أدناه للبيانات.|



###  أنظر أيضا
* الوحدة [`aspose.cells`](../../)
* فئة [`Cells`](/cells/python-net/ar/aspose.cells/cells)
