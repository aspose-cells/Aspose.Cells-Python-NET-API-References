---
title: طريقة get_precedents_in_calculation
second_title: Aspose.Cells for Python via .NET API المراجع
description:
type: docs
weight: 190
url: /ar/aspose.cells/cell/get_precedents_in_calculation/
is_root: false
---
##  get_precedents_in_calculation(self) {#}
يحصل على جميع السوابق (الإشارة إلى الخلايا في المصنف الحالي) التي تستخدمها صيغة هذه الخلية أثناء حسابها.


###  عائدات

مُعَدِّد لإحصاء جميع المراجع (ReferredArea)


```python

def get_precedents_in_calculation(self):
    ...
```


###  ملاحظات

لا يمكن لهذه الطريقة أن تعمل إلا في حالة [`FormulaSettings.enable_calculation_chain`](/cells/python-net/ar/aspose.cells/formulasettings#enable_calculation_chain)
هذا صحيح بالنسبة للمصنف وقد تم حساب المصنف بالكامل.
إذا لم تكن هذه الخلية عبارة عن صيغة أو لم تشير إلى أي خلايا أخرى، فسيتم إرجاع القيمة null.
###  مثال

```python
from aspose.cells import Workbook

workbook = Workbook()
cells = workbook.worksheets[0].cells
cells.get("A2").formula = "=IF(TRUE,B2,B1)"
workbook.settings.formula_settings.enable_calculation_chain = True
workbook.calculate_formula()
en = cells.get("A2").get_precedents_in_calculation()
print("A2's calculation precedents:")
for r in en:
    print(r)

```



###  أنظر أيضا
* الوحدة [`aspose.cells`](../../)
* فئة [`Cell`](/cells/python-net/ar/aspose.cells/cell)
