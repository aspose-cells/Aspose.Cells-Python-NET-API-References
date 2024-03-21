---
title: calc_stack_size عقار
second_title: Aspose.Cells for Python via .NET API المراجع
description:
type: docs
weight: 30
url: /ar/aspose.cells/calculationoptions/calc_stack_size/
is_root: false
---
##  calc_stack_size عقار

حجم المكدس لحساب الخلايا بشكل متكرر. القيمة الافتراضية هي 200.

###  ملاحظات

عندما تكون هناك حاجة إلى حساب كمية كبيرة من الخلايا بشكل متكرر في شجرة التبعية،
قد يكون سبب StackOverflowException في عملية الحساب.
إذا كان الأمر كذلك، يجب على المستخدم تحديد قيمة أصغر لهذه الخاصية.
في مثل هذه الحالة، يجب على المستخدم تحديد القيمة المناسبة لهذه الخاصية وفقًا للصيغ والبيانات الفعلية.
ومع ذلك، قد تؤدي القيمة الصغيرة جدًا إلى انخفاض أداء حساب الصيغة وقيمة أقل من 2
سيجعل من المستحيل حساب الصيغة التي تعتمد على صيغة أخرى. فإذا كانت القيمة المحددة أقل من 2،
سيتم إعادة تعيينه إلى 2.
###  تعريف:
```python
@property
def calc_stack_size(self):
    ...
@calc_stack_size.setter
def calc_stack_size(self, value):
    ...
```

###  أنظر أيضا
* الوحدة [`aspose.cells`](../../)
* فئة [`CalculationOptions`](/cells/python-net/ar/aspose.cells/calculationoptions)
