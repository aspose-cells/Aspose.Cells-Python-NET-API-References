---
title: calculated_value عقار
second_title: Aspose.Cells for Python via .NET API المراجع
description:
type: docs
weight: 60
url: /ar/aspose.cells/calculationdata/calculated_value/
is_root: false
---
##  calculated_value عقار

يحصل على القيمة المحسوبة لهذه الوظيفة أو يعينها.

###  ملاحظات

يجب على المستخدم تعيين هذه الخاصية في محرك الحساب المخصص الخاص به لتلك الوظائف التي يدعمها المحرك،
وسيتم إرجاع القيمة المحددة عند الحصول على هذه الخاصية لاحقًا.
قد تكون القيمة المحددة من الأنواع المحتملة [`Cell.value`](/cells/python-net/ar/aspose.cells/cell#value)،
أو مجموعة من هذا النوع من القيم، أو نطاق، أو اسم، أو منطقة مرجعية.
الحصول على هذه الخاصية قبل تعيين القيمة لها سيؤدي إلى حساب الوظيفة
من خلال محرك الحساب الافتراضي Aspose.Cells ومن ثم سيتم حساب القيمة
يتم إرجاعها (عادةً ما يجب أن تكون #NAME؟ للوظائف التي يحددها المستخدم).
###  تعريف:
```python
@property
def calculated_value(self):
    ...
@calculated_value.setter
def calculated_value(self, value):
    ...
```

###  أنظر أيضا
* الوحدة [`aspose.cells`](../../)
* فئة [`CalculationData`](/cells/python-net/ar/aspose.cells/calculationdata)
