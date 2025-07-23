---
title: طريقة get_dependents
second_title: Aspose.Cells for Python via .NET API المراجع
description:
type: docs
weight: 90
url: /ar/aspose.cells/cell/get_dependents/
is_root: false
---
##  get_dependents(self, is_all) {#bool}
احصل على جميع الخلايا التي تشير صيغتها إلى هذه الخلية بشكل مباشر.



```python

def get_dependents(self, is_all):
    ...
```


| معامل| يكتب| وصف|
| :- | :- | :- |
| is_all | bool |يشير إلى ما إذا كان يتم التحقق من الصيغ في أوراق العمل الأخرى|
###  ملاحظات

* إذا ظهر مرجع واحد يحتوي على هذه الخلية في صيغة خلية واحدة، فسيتم اعتبار تلك الخلية

تعتمد هذه الخلية على المرجع أو يتم استخدام هذه الخلية أثناء الحساب أم لا.
على سبيل المثال، على الرغم من عدم استخدام الخلية A2 في الصيغة "=IF(TRUE,A1,A2)" أثناء الحساب،
لا تزال هذه الصيغة تعتبر معتمدة على A2.
للحصول على تلك الصيغ التي تعتمد نتائجها المحسوبة على هذه الخلية، يرجى استخدام [`Cell.get_dependents_in_calculation`](/cells/python-net/ar/aspose.cells/cell/get_dependents_in_calculation). عند تتبع التابعين لخلية واحدة، سيتم تحليل جميع الصيغ الموجودة في المصنف أو ورقة العمل والتحقق منها.
إنها عملية تستغرق وقتًا طويلاً. إذا احتاج المستخدم إلى تتبع المُعالين في العديد من الخلايا، فإن استخدام هذه الطريقة سيُمكّنه من:
يُسبب ضعف الأداء. لتحسين الأداء، يُرجى استخدام [`Cell.get_dependents_in_calculation`](/cells/python-net/ar/aspose.cells/cell/get_dependents_in_calculation).
أو، يمكن للمستخدم جمع خريطة السوابق لجميع الخلايا عن طريق [`Cell.get_precedents`](/cells/python-net/ar/aspose.cells/cell/get_precedents) أولاً،
ومن ثم قم ببناء خريطة التابعين وفقًا لخريطة السوابق.

* إذا ظهر مرجع واحد يحتوي على هذه الخلية في صيغة خلية واحدة، فسيتم اعتبار تلك الخلية
تعتمد هذه الخلية على المرجع أو يتم استخدام هذه الخلية أثناء الحساب أم لا.
على سبيل المثال، على الرغم من عدم استخدام الخلية A2 في الصيغة "=IF(TRUE,A1,A2)" أثناء الحساب،
لا تزال هذه الصيغة تعتبر معتمدة على A2.
للحصول على تلك الصيغ التي تعتمد نتائجها المحسوبة على هذه الخلية، يرجى استخدام [`Cell.get_dependents_in_calculation`](/cells/python-net/ar/aspose.cells/cell/get_dependents_in_calculation). عند تتبع التابعين لخلية واحدة، سيتم تحليل جميع الصيغ الموجودة في المصنف أو ورقة العمل والتحقق منها.
إنها عملية تستغرق وقتًا طويلاً. إذا احتاج المستخدم إلى تتبع المُعالين في العديد من الخلايا، فإن استخدام هذه الطريقة سيُمكّنه من:
يُسبب ضعف الأداء. لتحسين الأداء، يُرجى استخدام [`Cell.get_dependents_in_calculation`](/cells/python-net/ar/aspose.cells/cell/get_dependents_in_calculation).
أو، يمكن للمستخدم جمع خريطة السوابق لجميع الخلايا عن طريق [`Cell.get_precedents`](/cells/python-net/ar/aspose.cells/cell/get_precedents) أولاً،
ومن ثم قم ببناء خريطة التابعين وفقًا لخريطة السوابق.

* إذا ظهر مرجع واحد يحتوي على هذه الخلية في صيغة خلية واحدة، فسيتم اعتبار تلك الخلية
تعتمد هذه الخلية على المرجع أو يتم استخدام هذه الخلية أثناء الحساب أم لا.
على سبيل المثال، على الرغم من عدم استخدام الخلية A2 في الصيغة "=IF(TRUE,A1,A2)" أثناء الحساب،
لا تزال هذه الصيغة تعتبر معتمدة على A2.
للحصول على تلك الصيغ التي تعتمد نتائجها المحسوبة على هذه الخلية، يرجى استخدام [`Cell.get_dependents_in_calculation`](/cells/python-net/ar/aspose.cells/cell/get_dependents_in_calculation). عند تتبع التابعين لخلية واحدة، سيتم تحليل جميع الصيغ الموجودة في المصنف أو ورقة العمل والتحقق منها.
إنها عملية تستغرق وقتًا طويلاً. إذا احتاج المستخدم إلى تتبع المُعالين في العديد من الخلايا، فإن استخدام هذه الطريقة سيُمكّنه من:
يُسبب ضعف الأداء. لتحسين الأداء، يُرجى استخدام [`Cell.get_dependents_in_calculation`](/cells/python-net/ar/aspose.cells/cell/get_dependents_in_calculation).
أو، يمكن للمستخدم جمع خريطة السوابق لجميع الخلايا عن طريق [`Cell.get_precedents`](/cells/python-net/ar/aspose.cells/cell/get_precedents) أولاً،
ومن ثم قم ببناء خريطة التابعين وفقًا لخريطة السوابق.
###  مثال

```python
from aspose.cells import Workbook

workbook = Workbook()
cells = workbook.worksheets[0].cells
cells.get("A1").formula = "=B1+SUM(B1:B10)+[Book1.xls]Sheet1!B2"
cells.get("A2").formula = "=IF(TRUE,B2,B1)"
dependents = cells.get("B1").get_dependents(True)
for i in range(len(dependents)):
    print(dependents[i].name)

```



###  أنظر أيضا
* الوحدة [`aspose.cells`](../../)
* فئة [`Cell`](/cells/python-net/ar/aspose.cells/cell)
