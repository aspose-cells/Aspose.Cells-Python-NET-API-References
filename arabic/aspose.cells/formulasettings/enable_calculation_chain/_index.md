---
title: enable_calculation_chain عقار
second_title: Aspose.Cells for Python via .NET API المراجع
description:
type: docs
weight: 70
url: /ar/aspose.cells/formulasettings/enable_calculation_chain/
is_root: false
---
##  enable_calculation_chain عقار

هل سيتم تفعيل سلسلة الحساب للصيغ؟ الإعداد الافتراضي هو خطأ.

###  ملاحظات

عندما يكون هناك الكثير من الصيغ في المصنف ويحتاج المستخدم إلى حسابها بشكل متكرر
من خلال تعديل جزء صغير فقط منها، قد يكون من المفيد لتحسين الأداء تمكين سلسلة الحساب.
من ناحية أخرى، إذا تم تمكين السلسلة، فإن الحفاظ على نموذج السلسلة يتطلب ذاكرة إضافية،
ويتطلب أيضًا وقتًا أطول قليلاً من وحدة المعالجة المركزية لبعض العمليات الأخرى مثل تغيير قيمة الخلية أو الصيغ.
بعد تغيير هذه الخاصية من false إلى true، سيتم تحليل سلسلة الحسابات وبنائها
في وقت الحساب الأول لدفتر العمل، لذا فإن الوقت المطلوب للحساب الأول
قد يكون أكثر من الحساب العادي بدون سلسلة.
###  تعريف:
```python
@property
def enable_calculation_chain(self):
    ...
@enable_calculation_chain.setter
def enable_calculation_chain(self, value):
    ...
```

###  أنظر أيضا
* الوحدة [`aspose.cells`](../../)
* فئة [`FormulaSettings`](/cells/python-net/ar/aspose.cells/formulasettings)
