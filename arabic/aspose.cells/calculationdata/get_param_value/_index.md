---
title: طريقة get_param_value
second_title: Aspose.Cells for Python via .NET API المراجع
description:
type: docs
weight: 30
url: /ar/aspose.cells/calculationdata/get_param_value/
is_root: false
---
##  get_param_value(self, index) {#int}
يحصل على كائن القيمة الممثلة للمعلمة في فهرس معين.


###  عائدات

القيمة المحسوبة للمعلمة.


```python

def get_param_value(self, index):
    ...
```


| معامل| يكتب| وصف|
| :- | :- | :- |
| index | int | مؤشر المعلمة (على أساس 0)|
###  ملاحظات

لمعلمة واحدة:

إذا كانت قيمة عادية، فسيتم إرجاع القيمة العادية نفسها؛


إذا كان مرجعًا، فإنه يرجع كائن ReferredArea؛


إذا كان يشير إلى مجموعة بيانات تحتوي على قيم متعددة، فإنه يقوم بإرجاع مجموعة من الكائنات؛



إذا كان هناك نوع من التعبير الذي يحتاج إلى حساب، فسيتم حسابه في وضع القيمة
وعادةً ما تُرجع قيمة واحدة بناءً على قاعدة الخلية الحالية. على سبيل المثال،
إذا كانت إحدى معلمات صيغة D2 هي A:A+B:B، فسيتم حساب A2+B2 وإرجاعها.
ومع ذلك، إذا تم تحديد هذه المعلمة كوضع المصفوفة
(بواسطة [`Workbook.update_custom_function_definition`](/cells/python-net/ar/aspose.cells/workbook/update_custom_function_definition)
أو [`FormulaParseOptions.custom_function_definition`](/cells/python-net/ar/aspose.cells/formulaparseoptions#custom_function_definition))،
ثم سيتم إرجاع array(object[][]) الذي تكون عناصره A1+B1،A2+B2،....


###  أنظر أيضا
* الوحدة [`aspose.cells`](../../)
* فئة [`CalculationData`](/cells/python-net/ar/aspose.cells/calculationdata)
