---
title: طريقة set_dynamic_array_formula
second_title: Aspose.Cells for Python via .NET API المراجع
description:
type: docs
weight: 340
url: /ar/aspose.cells/cell/set_dynamic_array_formula/
is_root: false
---
##  set_dynamic_array_formula(self, array_formula, options, calculate_value) {#str-aspose.cells.FormulaParseOptions-bool}
تعيين صيغة المصفوفة الديناميكية وجعل الصيغة تنتشر في الخلايا المجاورة إذا كان ذلك ممكنًا.


###  عائدات

النطاق الذي ينبغي أن تنتشر فيه الصيغة.


```python

def set_dynamic_array_formula(self, array_formula, options, calculate_value):
    ...
```


| معامل| يكتب| وصف|
| :- | :- | :- |
| array_formula | str | صيغة التعبير|
| options | [`FormulaParseOptions`](/cells/python-net/ar/aspose.cells/formulaparseoptions) | خيارات لتحليل الصيغة.<br/> سيتم تجاهل خيار "التحليل" وسيتم دائمًا تحليل الصيغة على الفور|
| calculate_value | bool | هل يمكن حساب صيغة المصفوفة الديناميكية هذه للخلايا الموجودة في النطاق المنسكب؟|
###  ملاحظات

قد لا يكون النطاق المرتجع هو نفسه النطاق الفعلي الذي تنتقل إليه صيغة المصفوفة الديناميكية هذه.
إذا كانت هناك خلايا غير فارغة في النطاق، فسيتم تعيين الصيغة للخلية الحالية فقط ووضع علامة عليها كـ "#SPILL!".
ولكن بالنسبة لهذا النوع من المواقف فإننا لا نزال نرجع إلى النطاق الكامل الذي ينبغي أن تمتد إليه هذه الصيغة.

##  set_dynamic_array_formula(self, array_formula, options, values, calculate_range, calculate_value) {#str-aspose.cells.FormulaParseOptions-list-bool-bool}
تعيين صيغة المصفوفة الديناميكية وجعل الصيغة تنتشر في الخلايا المجاورة إذا كان ذلك ممكنًا.


###  عائدات

النطاق الذي ينبغي أن تنتشر فيه الصيغة.


```python

def set_dynamic_array_formula(self, array_formula, options, values, calculate_range, calculate_value):
    ...
```


| معامل| يكتب| وصف|
| :- | :- | :- |
| array_formula | str | صيغة التعبير|
| options | [`FormulaParseOptions`](/cells/python-net/ar/aspose.cells/formulaparseoptions) | خيارات لتحليل الصيغة.<br/> سيتم تجاهل خيار "التحليل" وسيتم دائمًا تحليل الصيغة على الفور|
| values | list |القيم (النتائج المحسوبة) لتلك الخلايا ذات صيغة المصفوفة الديناميكية المحددة|
| calculate_range | bool | ما إذا كان من الممكن حساب النطاق المنسكب لصيغة المصفوفة الديناميكية هذه.<br/>إذا لم تكن معلمة "القيم" فارغة وكان هذا العلم خاطئًا،<br/> ثم سيكون ارتفاع النطاق المنسكب عبارة عن قيم.الطول وسيكون العرض عبارة عن قيم[0].الطول.|
| calculate_value | bool | ما إذا كان من الممكن حساب صيغة المصفوفة الديناميكية هذه للخلايا الموجودة في النطاق المنسكب عندما تكون "القيم" فارغة<br/> أو العنصر المقابل في "القيم" لخلية واحدة هو فارغ.|
###  ملاحظات

قد لا يكون النطاق المرتجع هو نفسه النطاق الفعلي الذي تنتقل إليه صيغة المصفوفة الديناميكية هذه.
إذا كانت هناك خلايا غير فارغة في النطاق، فسيتم تعيين الصيغة للخلية الحالية فقط ووضع علامة عليها كـ "#SPILL!".
ولكن بالنسبة لهذا النوع من المواقف فإننا لا نزال نرجع إلى النطاق الكامل الذي ينبغي أن تمتد إليه هذه الصيغة.

##  set_dynamic_array_formula(self, array_formula, options, values, calculate_range, calculate_value, copts) {#str-aspose.cells.FormulaParseOptions-list-bool-bool-aspose.cells.CalculationOptions}
تعيين صيغة المصفوفة الديناميكية وجعل الصيغة تنتشر في الخلايا المجاورة إذا كان ذلك ممكنًا.


###  عائدات

النطاق الذي ينبغي أن تنتشر فيه الصيغة.


```python

def set_dynamic_array_formula(self, array_formula, options, values, calculate_range, calculate_value, copts):
    ...
```


| معامل| يكتب| وصف|
| :- | :- | :- |
| array_formula | str | صيغة التعبير|
| options | [`FormulaParseOptions`](/cells/python-net/ar/aspose.cells/formulaparseoptions) | خيارات لتحليل الصيغة.<br/> سيتم تجاهل خيار "التحليل" وسيتم دائمًا تحليل الصيغة على الفور|
| values | list |القيم (النتائج المحسوبة) لتلك الخلايا ذات صيغة المصفوفة الديناميكية المحددة|
| calculate_range | bool | ما إذا كان من الممكن حساب النطاق المنسكب لصيغة المصفوفة الديناميكية هذه.<br/>إذا لم تكن معلمة "القيم" فارغة وكان هذا العلم خاطئًا،<br/> ثم سيكون ارتفاع النطاق المنسكب عبارة عن قيم.الطول وسيكون العرض عبارة عن قيم[0].الطول.|
| calculate_value | bool | ما إذا كان من الممكن حساب صيغة المصفوفة الديناميكية هذه للخلايا الموجودة في النطاق المنسكب عندما تكون "القيم" فارغة<br/> أو العنصر المقابل في "القيم" لخلية واحدة هو فارغ.|
| copts | [`CalculationOptions`](/cells/python-net/ar/aspose.cells/calculationoptions) | خيارات لحساب الصيغة.<br/> بشكل عام، من أجل مراعاة الأداء، يجب أن تكون الخاصية [`CalculationOptions.recursive`](/cells/python-net/ar/aspose.cells/calculationoptions#recursive) خاطئة.|
###  ملاحظات

قد لا يكون النطاق المرتجع هو نفسه النطاق الفعلي الذي تنتقل إليه صيغة المصفوفة الديناميكية هذه.
إذا كانت هناك خلايا غير فارغة في النطاق، فسيتم تعيين الصيغة للخلية الحالية فقط ووضع علامة عليها كـ "#SPILL!".
ولكن بالنسبة لهذا النوع من المواقف فإننا لا نزال نرجع إلى النطاق الكامل الذي ينبغي أن تمتد إليه هذه الصيغة.


###  أنظر أيضا
* الوحدة [`aspose.cells`](../../)
* فئة [`Cell`](/cells/python-net/ar/aspose.cells/cell)
