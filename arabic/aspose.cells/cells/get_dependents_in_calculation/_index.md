---
title: طريقة get_dependents_in_calculation
second_title: Aspose.Cells for Python via .NET API المراجع
description:
type: docs
weight: 400
url: /ar/aspose.cells/cells/get_dependents_in_calculation/
is_root: false
---
##  get_dependents_in_calculation(self, row, column, recursive) {#int-int-bool}
يحصل على جميع الخلايا التي تعتمد نتيجتها المحسوبة على خلية معينة.


###  عائدات

مُعَدِّد لإحصاء جميع الكائنات التابعة (Cell كائنًا)


```python

def get_dependents_in_calculation(self, row, column, recursive):
    ...
```


| معامل| يكتب| وصف|
| :- | :- | :- |
| row | int | مؤشر الصف للخلية المحددة|
| column | int |فهرس العمود للخلية المحددة.|
| recursive | bool | ما إذا كان يتم إرجاع العناصر التابعة التي لا تشير إلى الخلية المحددة بشكل مباشر<br/> ولكن الإشارة إلى أوراق أخرى من تلك الخلية.|
###  ملاحظات

لاستخدام هذه الطريقة، يرجى التأكد من تعيين المصنف بالقيمة الصحيحة لـ
[`FormulaSettings.enable_calculation_chain`](/cells/python-net/ar/aspose.cells/formulasettings#enable_calculation_chain) وتم حسابه بالكامل باستخدام هذا الإعداد.
إذا لم يكن هناك مرجع صيغة لهذه الخلية، فسيتم إرجاع القيمة null.
لمزيد من التفاصيل والأمثلة، يرجى مراجعة [`Cell.get_dependents_in_calculation`](/cells/python-net/ar/aspose.cells/cell/get_dependents_in_calculation)


###  أنظر أيضا
* الوحدة [`aspose.cells`](../../)
* فئة [`Cells`](/cells/python-net/ar/aspose.cells/cells)
