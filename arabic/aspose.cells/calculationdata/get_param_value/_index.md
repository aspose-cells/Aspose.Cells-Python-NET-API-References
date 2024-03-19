---
title: طريقة get_param_value
second_title: Aspose.Cells for Python via .NET API المراجع
description:
type: docs
weight: 30
url: /ar/aspose.cells/calculationdata/get_param_value/
is_root: false
---
##  get_param_value {#int}
يحصل على كائن القيمة الممثلة للمعلمة في فهرس معين.


###  عائدات

القيمة المحسوبة للمعلمة.


```python
def get_param_value(self, index):
    ...
```


| معامل| يكتب| وصف|
| :- | :- | :- |
| index | int | فهرس المعلمة (0 على أساس)|
###  ملاحظات

لمعلمة واحدة:

إذا كانت قيمة عادية، فسيتم إرجاع القيمة العادية نفسها؛


إذا كان مرجعًا، فسيتم إرجاع كائن ReferredArea؛


إذا كانت تشير إلى مجموعة (مجموعات) بيانات ذات قيم متعددة، فسيتم إرجاع مجموعة من الكائنات؛



إذا كان هناك نوع من التعبير الذي يحتاج إلى حساب، فسيتم حسابه في وضع القيمة
وبشكل عام سيتم إرجاع قيمة واحدة وفقًا لقاعدة الخلية الحالية. على سبيل المثال،
إذا كانت إحدى معلمات صيغة D2 هي A:A+B:B، فسيتم حساب A2+B2 وإرجاعها.
ومع ذلك، إذا تم تحديد هذه المعلمة كوضع صفيف
(بواسطة [`Workbook.update_custom_function_definition`](/cells/python-net/ar/aspose.cells/workbook/update_custom_function_definition)
أو [`FormulaParseOptions.custom_function_definition`](/cells/python-net/ar/aspose.cells/formulaparseoptions#custom_function_definition))،
ثم سيتم إرجاع صفيف (كائن [] []) عناصره هي A1 + B1، A2 + B2، ....


###  أنظر أيضا
* الوحدة [`aspose.cells`](../../)
* فئة [`CalculationData`](/cells/python-net/ar/aspose.cells/calculationdata)
