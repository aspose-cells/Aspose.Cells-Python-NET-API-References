---
title: طريقة add
second_title: Aspose.Cells for Python via .NET API المراجع
description:
type: docs
weight: 20
url: /ar/aspose.cells/formatconditioncollection/add/
is_root: false
---
##  add(cell_area, type, operator_type, formula1, formula2) {#CellArea-FormatConditionType-OperatorType-str-str}
يضيف شرط تنسيق ونطاق خلية مؤثر إلى FormatConditions
يمكن أن تحتوي FormatConditions على ما يصل إلى ثلاثة تنسيقات شرطية.
غير مسموح بالإشارات إلى الأوراق الأخرى في صيغ التنسيق الشرطي.


###  عائدات

[0]: تنسيق فهرس كائن الشرط ؛ [1] فهرس مدى الخلية المتأثر.


```python
def add(self, cell_area, type, operator_type, formula1, formula2):
    ...
```


| معامل| يكتب| وصف|
| :- | :- | :- |
| cell_area | [CellArea](/cells/python-net/ar/aspose.cells/cellarea) |نطاق الخلايا المنسق الشرطي.|
| type | [FormatConditionType](/cells/python-net/ar/aspose.cells/formatconditiontype) | نوع التنسيق الشرطي: يمكن أن يكون أحد أعضاء FormatConditionType.|
| operator_type | [OperatorType](/cells/python-net/ar/aspose.cells/operatortype) | عامل المقارنة: يمكن أن يكون أحد أعضاء OperatorType.|
| formula1 | str | القيمة أو التعبير المرتبط بالتنسيق الشرطي.|
| formula2 | str | القيمة أو التعبير المرتبط بالتنسيق الشرطي|



###  أنظر أيضا
* وحدة [aspose.cells](../../)
* فئة [FormatConditionCollection](/cells/python-net/ar/aspose.cells/formatconditioncollection)
