---
title: طريقة refresh_dynamic_array_formulas
second_title: Aspose.Cells for Python via .NET API المراجع
description:
type: docs
weight: 290
url: /ar/aspose.cells/workbook/refresh_dynamic_array_formulas/
is_root: false
---
##  refresh_dynamic_array_formulas(self, calculate) {#bool}
تحديث صيغ المصفوفة الديناميكية (الانسكاب في نطاق جديد من الخلايا المجاورة وفقًا للبيانات الحالية)
لن يتم حساب الصيغ الأخرى الموجودة في المصنف بشكل متكرر حتى لو تم استخدامها بواسطة صيغ المصفوفة الديناميكية.



```python

def refresh_dynamic_array_formulas(self, calculate):
    ...
```


| معامل| يكتب| وصف|
| :- | :- | :- |
| calculate | bool | ما إذا كان يحسب ويحدّث قيم الخلايا لصيغ المصفوفة الديناميكية تلك|


##  refresh_dynamic_array_formulas(self, calculate, copts) {#bool-aspose.cells.CalculationOptions}
تحديث صيغ المصفوفة الديناميكية (الانسكاب في نطاق جديد من الخلايا المجاورة وفقًا للبيانات الحالية)



```python

def refresh_dynamic_array_formulas(self, calculate, copts):
    ...
```


| معامل| يكتب| وصف|
| :- | :- | :- |
| calculate | bool | ما إذا كان يحسب ويحدّث قيم الخلايا لصيغ المصفوفة الديناميكية تلك|
| copts | [`CalculationOptions`](/cells/python-net/ar/aspose.cells/calculationoptions) | خيارات حساب الصيغ|
###  ملاحظات

من أجل مراعاة الأداء، لا نقوم بتحديث جميع صيغ المصفوفة الديناميكية تلقائيًا
عندما تتغير الصيغة نفسها أو البيانات التي تشير إليها.
لذلك يحتاج المستخدم إلى استدعاء هذه الطريقة يدويًا بعد تلك العمليات التي قد تؤثر على صيغ المصفوفة الديناميكية،
مثل استيراد/تعيين قيم الخلايا، إدراج/حذف الصفوف/الأعمدة/النطاقات، ...إلخ.

بالنسبة لمعظم الصيغ التي تحتوي على وظائف، فإن حساب نطاق الانسكاب يحتاج أيضًا إلى حساب الصيغة،
لذلك بشكل عام، يتم تفضيل القيمة الحقيقية لعلم "الحساب".
إذا كانت الصيغة بسيطة، مثل مرجع النطاق أو المصفوفة (على سبيل المثال "=C1:E5"، "={1,2;3,4}"، ...)،
دالة بسيطة على نطاق أو مصفوفة (على سبيل المثال "=ABS(C1:E5)", "=1+{1,2;3,4}", ...),
وسيتم حساب جميع الصيغ لاحقًا (مثل [`Workbook.calculate_formula`](/cells/python-net/ar/aspose.cells/workbook/calculate_formula))،
ثم استخدام قيمة خاطئة لعلم "الحساب" قد يتجنب الحساب المكرر لصالح الأداء.


###  أنظر أيضا
* الوحدة [`aspose.cells`](../../)
* فئة [`Workbook`](/cells/python-net/ar/aspose.cells/workbook)
