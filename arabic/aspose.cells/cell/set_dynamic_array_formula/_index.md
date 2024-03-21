---
title: طريقة set_dynamic_array_formula
second_title: Aspose.Cells for Python via .NET API المراجع
description:
type: docs
weight: 330
url: /ar/aspose.cells/cell/set_dynamic_array_formula/
is_root: false
---
##  set_dynamic_array_formula {#str-aspose.cells.FormulaParseOptions-bool}
يضبط صيغة الصفيف الديناميكي ويجعل الصيغة تمتد إلى الخلايا المجاورة إن أمكن.


###  عائدات

النطاق الذي يجب أن تمتد إليه الصيغة.


```python
def set_dynamic_array_formula(self, array_formula, options, calculate_value):
    ...
```


| معامل| يكتب| وصف|
| :- | :- | :- |
| array_formula | str |تعبير الصيغة|
| options | [`FormulaParseOptions`](/cells/python-net/ar/aspose.cells/formulaparseoptions) | خيارات لتحليل الصيغة.<br/> سيتم تجاهل خيار "التحليل" وسيتم دائمًا تحليل الصيغة على الفور|
| calculate_value | bool | ما إذا كان سيتم حساب صيغة الصفيف الديناميكي هذه لتلك الخلايا الموجودة في النطاق الممتد.|


##  set_dynamic_array_formula {#str-aspose.cells.FormulaParseOptions-list-bool-bool}
يضبط صيغة الصفيف الديناميكي ويجعل الصيغة تمتد إلى الخلايا المجاورة إن أمكن.


###  عائدات

النطاق الذي يجب أن تمتد إليه الصيغة.


```python
def set_dynamic_array_formula(self, array_formula, options, values, calculate_range, calculate_value):
    ...
```


| معامل| يكتب| وصف|
| :- | :- | :- |
| array_formula | str |تعبير الصيغة|
| options | [`FormulaParseOptions`](/cells/python-net/ar/aspose.cells/formulaparseoptions) | خيارات لتحليل الصيغة.<br/> سيتم تجاهل خيار "التحليل" وسيتم دائمًا تحليل الصيغة على الفور|
| values | list | القيم (النتائج المحسوبة) لتلك الخلايا ذات صيغة الصفيف الديناميكي المحددة|
| calculate_range | bool | ما إذا كان سيتم حساب النطاق الممتد لصيغة الصفيف الديناميكي هذه.<br/>إذا لم تكن معلمة "القيم" فارغة وكانت هذه العلامة خاطئة،<br/> ثم سيكون ارتفاع النطاق الممتد قيمًا. وسيكون الطول والعرض قيمًا[0].الطول.|
| calculate_value | bool | ما إذا كان سيتم حساب صيغة الصفيف الديناميكي هذه لتلك الخلايا الموجودة في النطاق الممتد عندما تكون "القيم" فارغة<br/> أو أن العنصر المقابل في "القيم" لخلية واحدة يكون فارغًا.|


##  set_dynamic_array_formula {#str-aspose.cells.FormulaParseOptions-list-bool-bool-aspose.cells.CalculationOptions}
يضبط صيغة الصفيف الديناميكي ويجعل الصيغة تمتد إلى الخلايا المجاورة إن أمكن.


###  عائدات

النطاق الذي يجب أن تمتد إليه الصيغة.


```python
def set_dynamic_array_formula(self, array_formula, options, values, calculate_range, calculate_value, copts):
    ...
```


| معامل| يكتب| وصف|
| :- | :- | :- |
| array_formula | str |تعبير الصيغة|
| options | [`FormulaParseOptions`](/cells/python-net/ar/aspose.cells/formulaparseoptions) | خيارات لتحليل الصيغة.<br/> سيتم تجاهل خيار "التحليل" وسيتم دائمًا تحليل الصيغة على الفور|
| values | list | القيم (النتائج المحسوبة) لتلك الخلايا ذات صيغة الصفيف الديناميكي المحددة|
| calculate_range | bool | ما إذا كان سيتم حساب النطاق الممتد لصيغة الصفيف الديناميكي هذه.<br/>إذا لم تكن معلمة "القيم" فارغة وكانت هذه العلامة خاطئة،<br/> ثم سيكون ارتفاع النطاق الممتد قيمًا. وسيكون الطول والعرض قيمًا[0].الطول.|
| calculate_value | bool | ما إذا كان سيتم حساب صيغة الصفيف الديناميكي هذه لتلك الخلايا الموجودة في النطاق الممتد عندما تكون "القيم" فارغة<br/> أو أن العنصر المقابل في "القيم" لخلية واحدة يكون فارغًا.|
| copts | [`CalculationOptions`](/cells/python-net/ar/aspose.cells/calculationoptions) | خيارات لحساب الصيغة.<br/> بشكل عام، لاعتبارات الأداء، يجب أن تكون الخاصية [`CalculationOptions.recursive`](/cells/python-net/ar/aspose.cells/calculationoptions#recursive) خاطئة.|



###  أنظر أيضا
* الوحدة [`aspose.cells`](../../)
* فئة [`Cell`](/cells/python-net/ar/aspose.cells/cell)
