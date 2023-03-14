---
title: طريقة find_formula
second_title: Aspose.Cells for Python via .NET API المراجع
description:
type: docs
weight: 300
url: /ar/aspose.cells/cells/find_formula/
is_root: false
---
##  find_formula(formula, previous_cell) {#str-Cell}
يبحث عن الخلية التي تحتوي على سلسلة الإدخال.


###  عائدات

Cell كائن.


```python
def find_formula(self, formula, previous_cell):
    ...
```


| معامل| يكتب| وصف|
| :- | :- | :- |
| formula | str | الصيغة للبحث عنها.|
| previous_cell | [Cell](/cells/python-net/ar/aspose.cells/cell) |الخلية السابقة بنفس الصيغة. يمكن ضبط هذه المعلمة على قيمة خالية في حالة البحث من البداية.|
###  ملاحظات

تُرجع فارغة (لا شيء) إذا لم يتم العثور على خلية.
 ملاحظة: هذا العضو قد عفا عليه الزمن الآن. بدلاً من،
الرجاء استخدام Cells.Find (object، Cell، FindOptions) طريقة مع LookInType كـ LookInType.OnlyFormulas
 و LookAtType كـ LookAtType.EntireContent.
 ستتم إزالة هذا العضو بعد 12 شهرًا منذ نوفمبر 2018.
Aspose يعتذر عن أي إزعاج قد يكون سببه لك.


###  أنظر أيضا
* وحدة [aspose.cells](../../)
* فئة [Cells](/cells/python-net/ar/aspose.cells/cells)
