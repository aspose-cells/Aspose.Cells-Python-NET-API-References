---
title: طريقة on_circular
second_title: Aspose.Cells for Python via .NET API المراجع
description:
type: docs
weight: 40
url: /ar/aspose.cells/abstractcalculationmonitor/on_circular/
is_root: false
---
##  on_circular {#collections.abc.Iterator}
قم بتطبيق هذه الطريقة للقيام بالأعمال عند حساب الصيغ ذات المراجع الدائرية.


###  عائدات

ما إذا كان محرك الصيغة يحتاج إلى حساب تلك الخلايا بشكل دائري بعد هذا الاستدعاء.
صحيح السماح لمحرك الصيغة بمواصلة إجراء العمليات الحسابية لهم.
خطأ للسماح لمحرك الصيغة فقط بوضع علامة على تلك الخلايا على أنها محسوبة.


```python
def on_circular(self, circular_cells_data):
    ...
```


| معامل| يكتب| وصف|
| :- | :- | :- |
| circular_cells_data | collections.abc.Iterator | IEnumerator مع [`CalculationCell`](/cells/python-net/ar/aspose.cells/calculationcell) عنصرًا يمثل الخلايا التي<br/> تعتمد على المراجع الدائرية.|
###  ملاحظات

في التنفيذ، يمكن للمستخدم أيضًا تعيين القيمة المتوقعة كنتيجة محسوبة
لجزء/كل هذه الخلايا حتى لا يقوم محرك الصيغة بحسابها بشكل متكرر.


###  أنظر أيضا
* الوحدة [`aspose.cells`](../../)
* فئة [`AbstractCalculationMonitor`](/cells/python-net/ar/aspose.cells/abstractcalculationmonitor)
* فئة [`CalculationCell`](/cells/python-net/ar/aspose.cells/calculationcell)
