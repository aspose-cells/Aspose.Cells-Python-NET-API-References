---
title: طريقة refresh_dynamic_array_formulas
second_title: Aspose.Cells for Python via .NET API المراجع
description:
type: docs
weight: 270
url: /ar/aspose.cells/workbook/refresh_dynamic_array_formulas/
is_root: false
---
##  refresh_dynamic_array_formulas {#bool}
تحديث صيغ المصفوفة الديناميكية (تمتد إلى نطاق جديد من الخلايا المجاورة وفقًا للبيانات الحالية)
لن يتم حساب الصيغ الأخرى الموجودة في المصنف بشكل متكرر حتى إذا تم استخدامها بواسطة صيغ الصفيف الديناميكي.



```python
def refresh_dynamic_array_formulas(self, calculate):
    ...
```


| معامل| يكتب| وصف|
| :- | :- | :- |
| calculate | bool | ما إذا كان يتم حساب وتحديث قيم الخلايا لصيغ الصفيف الديناميكية تلك|


##  refresh_dynamic_array_formulas {#bool-aspose.cells.CalculationOptions}
تحديث صيغ المصفوفة الديناميكية (تمتد إلى نطاق جديد من الخلايا المجاورة وفقًا للبيانات الحالية)



```python
def refresh_dynamic_array_formulas(self, calculate, copts):
    ...
```


| معامل| يكتب| وصف|
| :- | :- | :- |
| calculate | bool | ما إذا كان يتم حساب وتحديث قيم الخلايا لصيغ الصفيف الديناميكية تلك|
| copts | [`CalculationOptions`](/cells/python-net/ar/aspose.cells/calculationoptions) | خيارات لحساب الصيغ|
###  ملاحظات

لاعتبارات الأداء، لا نقوم بتحديث كافة صيغ الصفيف الديناميكي تلقائيًا
عندما تتغير الصيغة نفسها أو البيانات التي تشير إليها.
لذلك يحتاج المستخدم إلى استدعاء هذه الطريقة يدويًا بعد تلك العمليات التي قد تؤثر على صيغ المصفوفة الديناميكية،
مثل استيراد/تحديد قيم الخلايا، وإدراج/حذف الصفوف/الأعمدة/النطاقات، ...إلخ.

بالنسبة لمعظم الصيغ ذات الوظائف، فإن حساب نطاق الانسكاب يحتاج أيضًا إلى حساب الصيغة،
لذا بشكل عام، تُفضل القيمة الحقيقية لعلامة "الحساب".
إذا كانت الصيغة بسيطة، مثل مرجع نطاق أو صفيف (على سبيل المثال "=C1:E5"، "={1,2;3,4}"، ...)،
دالة بسيطة على نطاق أو مصفوفة (على سبيل المثال "=ABS(C1:E5)"، "=1+{1,2;3,4}"، ...)،
وسيتم حساب كافة الصيغ في وقت لاحق (مثل [`Workbook.calculate_formula`](/cells/python-net/ar/aspose.cells/workbook/calculate_formula))،
فإن استخدام علامة vlaue الخاطئة لعلامة "الحساب" قد يؤدي إلى تجنب الحساب المكرر لصالح الأداء.


###  أنظر أيضا
* الوحدة [`aspose.cells`](../../)
* فئة [`Workbook`](/cells/python-net/ar/aspose.cells/workbook)
