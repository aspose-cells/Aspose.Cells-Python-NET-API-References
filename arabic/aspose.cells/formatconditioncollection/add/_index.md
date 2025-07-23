---
title: طريقة add
second_title: Aspose.Cells for Python via .NET API المراجع
description:
type: docs
weight: 20
url: /ar/aspose.cells/formatconditioncollection/add/
is_root: false
---
##  add(self, cell_area, type, operator_type, formula1, formula2) {#aspose.cells.CellArea-aspose.cells.FormatConditionType-aspose.cells.OperatorType-str-str}
يضيف شرط التنسيق ونطاق الخلية المتأثرة إلى شروط التنسيق
يمكن أن تحتوي FormatConditions على ما يصل إلى ثلاثة تنسيقات شرطية.
لا يُسمح بالإشارة إلى الأوراق الأخرى في صيغ التنسيق الشرطي.


###  عائدات

[0]: فهرس كائن شرط التنسيق؛[1] فهرس نطاق الخلية المتأثر.


```python

def add(self, cell_area, type, operator_type, formula1, formula2):
    ...
```


| معامل| يكتب| وصف|
| :- | :- | :- |
| cell_area | [`CellArea`](/cells/python-net/ar/aspose.cells/cellarea) |نطاق الخلايا المنسقة بشكل مشروط.|
| type | [`FormatConditionType`](/cells/python-net/ar/aspose.cells/formatconditiontype) | نوع من التنسيق الشرطي. يمكن أن يكون أحد أعضاء FormatConditionType.|
| operator_type | [`OperatorType`](/cells/python-net/ar/aspose.cells/operatortype) | عامل المقارنة.يمكن أن يكون أحد أعضاء OperatorType.|
| formula1 | str | القيمة أو التعبير المرتبط بالتنسيق الشرطي.|
| formula2 | str | القيمة أو التعبير المرتبط بالتنسيق الشرطي|



###  أنظر أيضا
* الوحدة [`aspose.cells`](../../)
* فئة [`FormatConditionCollection`](/cells/python-net/ar/aspose.cells/formatconditioncollection)
