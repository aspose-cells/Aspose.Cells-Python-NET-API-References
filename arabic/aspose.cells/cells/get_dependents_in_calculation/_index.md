---
title: طريقة get_dependents_in_calculation
second_title: Aspose.Cells for Python via .NET API المراجع
description:
type: docs
weight: 370
url: /ar/aspose.cells/cells/get_dependents_in_calculation/
is_root: false
---
##  get_dependents_in_calculation {#int-int-bool}
يحصل على جميع الخلايا التي تعتمد نتائجها المحسوبة على خلية معينة.


###  عائدات

العداد لتعداد جميع المعالين (كائنات Cell)


```python
def get_dependents_in_calculation(self, row, column, recursive):
    ...
```


| معامل| يكتب| وصف|
| :- | :- | :- |
| row | int | فهرس الصف للخلية المحددة|
| column | int | فهرس العمود للخلية المحددة.|
| recursive | bool | سواء تقوم بإرجاع هؤلاء المعالين الذين لا يشيرون إلى خلية معينة مباشرة<br/> ولكن الإشارة إلى أوراق أخرى من تلك الخلية.|
###  ملاحظات

لاستخدام هذه الطريقة، الرجاء التأكد من تعيين المصنف بالقيمة الحقيقية لـ
[`FormulaSettings.enable_calculation_chain`](/cells/python-net/ar/aspose.cells/formulasettings#enable_calculation_chain) وتم حسابه بالكامل بهذا الإعداد.
إذا لم يكن هناك مرجع صيغة لهذه الخلية، فسيتم إرجاع القيمة null.
لمزيد من التفاصيل والأمثلة يرجى مراجعة [`Cell.get_dependents_in_calculation`](/cells/python-net/ar/aspose.cells/cell/get_dependents_in_calculation)


###  أنظر أيضا
* الوحدة [`aspose.cells`](../../)
* فئة [`Cells`](/cells/python-net/ar/aspose.cells/cells)
