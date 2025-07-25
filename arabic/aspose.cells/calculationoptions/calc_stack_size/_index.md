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

حجم المكدس لحساب الخلايا بشكل متكرر. القيمة الافتراضية هي ٢٠٠.

###  ملاحظات

عندما يكون هناك عدد كبير من الخلايا التي تحتاج إلى حسابها بشكل متكرر في شجرة التبعية،
قد يحدث StackOverflowException في عملية الحساب.
إذا كان الأمر كذلك، فيجب على المستخدم تحديد قيمة أصغر لهذه الخاصية.
في مثل هذه الحالة، يجب على المستخدم تحديد القيمة المناسبة لهذه الخاصية وفقًا للصيغ والبيانات الفعلية.
ومع ذلك، قد تتسبب القيمة الصغيرة جدًا في انخفاض الأداء لحساب الصيغة والقيمة الأقل من 2
سيجعل من المستحيل حساب صيغة تعتمد على صيغة أخرى. لذا، إذا كانت القيمة المحددة أقل من ٢،
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
