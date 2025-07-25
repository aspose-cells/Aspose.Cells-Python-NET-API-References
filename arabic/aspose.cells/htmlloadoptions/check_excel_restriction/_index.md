---
title: check_excel_restriction عقار
second_title: Aspose.Cells for Python via .NET API المراجع
description:
type: docs
weight: 90
url: /ar/aspose.cells/htmlloadoptions/check_excel_restriction/
is_root: false
---
##  check_excel_restriction عقار

ما إذا كان يتم التحقق من تقييد ملف Excel عندما يقوم المستخدم بتعديل الكائنات المرتبطة بالخلايا.
على سبيل المثال، لا يسمح Excel بإدخال قيمة سلسلة أطول من 32 كيلو بايت.
عندما تقوم بإدخال قيمة أطول من 32 كيلو بايت مثل Cell.PutValue(string)، إذا كانت هذه الخاصية صحيحة، فسوف تحصل على استثناء.
إذا كانت هذه الخاصية خاطئة، فسنقبل قيمة السلسلة المدخلة كقيمة للخلية حتى نتمكن لاحقًا من
يمكنك إخراج قيمة السلسلة الكاملة لتنسيقات الملفات الأخرى مثل CSV.
ومع ذلك، إذا قمت بتعيين مثل هذا النوع من القيمة غير صالح لتنسيق ملف Excel،
لا تحفظ المصنف بصيغة ملف إكسل لاحقًا، وإلا فقد يحدث خطأ غير متوقع في ملف إكسل الناتج.
###  تعريف:
```python
@property
def check_excel_restriction(self):
    ...
@check_excel_restriction.setter
def check_excel_restriction(self, value):
    ...
```

###  أنظر أيضا
* الوحدة [`aspose.cells`](../../)
* فئة [`HtmlLoadOptions`](/cells/python-net/ar/aspose.cells/htmlloadoptions)
