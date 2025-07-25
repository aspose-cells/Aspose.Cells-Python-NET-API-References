---
title: طريقة get_dependents_in_calculation
second_title: Aspose.Cells for Python via .NET API المراجع
description:
type: docs
weight: 100
url: /ar/aspose.cells/cell/get_dependents_in_calculation/
is_root: false
---
##  get_dependents_in_calculation(self, recursive) {#bool}
يحصل على جميع الخلايا التي تعتمد نتيجتها المحسوبة على هذه الخلية.


###  عائدات

مُعَدِّد لإحصاء جميع الكائنات التابعة (Cell كائنًا)


```python

def get_dependents_in_calculation(self, recursive):
    ...
```


| معامل| يكتب| وصف|
| :- | :- | :- |
| recursive | bool | ما إذا كان يتم إرجاع العناصر التابعة التي لا تشير إلى هذه الخلية بشكل مباشر<br/> لكن الإشارة إلى أوراق أخرى من هذه الخلية|
###  ملاحظات

لاستخدام هذه الطريقة، يرجى التأكد من تعيين المصنف بالقيمة الصحيحة لـ
[`FormulaSettings.enable_calculation_chain`](/cells/python-net/ar/aspose.cells/formulasettings#enable_calculation_chain) وتم حسابه بالكامل باستخدام هذا الإعداد.
إذا لم يكن هناك مرجع صيغة لهذه الخلية، فسيتم إرجاع القيمة null.
###  مثال

```python
from aspose.cells import Workbook

workbook = Workbook()
cells = workbook.worksheets[0].cells
cells.get("A1").formula = "=B1+SUM(B1:B10)+[Book1.xls]Sheet1!B2"
cells.get("A2").formula = "=IF(TRUE,B2,B1)"
workbook.settings.formula_settings.enable_calculation_chain = True
workbook.calculate_formula()
en = cells.get("B1").get_dependents_in_calculation(False)
print("B1's calculation dependents:")
for c in en:
    print(c.name)
en = cells.get("B2").get_dependents_in_calculation(False)
print("B2's calculation dependents:")
for c in en:
    print(c.name)

```



###  أنظر أيضا
* الوحدة [`aspose.cells`](../../)
* فئة [`Cell`](/cells/python-net/ar/aspose.cells/cell)
