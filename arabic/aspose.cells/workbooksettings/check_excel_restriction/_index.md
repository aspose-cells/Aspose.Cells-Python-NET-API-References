---
title: check_excel_restriction عقار
second_title: Aspose.Cells for Python via .NET API المراجع
description:
type: docs
weight: 110
url: /ar/aspose.cells/workbooksettings/check_excel_restriction/
is_root: false
---
##  check_excel_restriction عقار

ما إذا كان يجب التحقق من تقييد ملف Excel عندما يقوم المستخدم بتعديل الكائنات ذات الصلة بالخلايا.
على سبيل المثال، لا يسمح برنامج Excel بإدخال قيمة سلسلة أطول من 32 كيلو بايت.
عند إدخال قيمة أطول من 32 كيلو مثل Cell.PutValue(string)، إذا كانت هذه الخاصية صحيحة، فسوف تحصل على استثناء.
إذا كانت هذه الخاصية خاطئة، فسنقبل قيمة سلسلة الإدخال الخاصة بك كقيمة للخلية، وذلك لاحقًا
يمكنك إخراج قيمة السلسلة الكاملة لتنسيقات الملفات الأخرى مثل CSV.
ومع ذلك، إذا قمت بتعيين هذا النوع من القيمة غير الصالحة لتنسيق ملف Excel،
يجب ألا تقوم بحفظ المصنف بتنسيق ملف Excel لاحقًا. وإلا فقد يكون هناك خطأ غير متوقع لملف Excel الذي تم إنشاؤه.
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
* فئة [`WorkbookSettings`](/cells/python-net/ar/aspose.cells/workbooksettings)
