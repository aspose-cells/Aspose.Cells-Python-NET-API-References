---
title: calculation_id عقار
second_title: Aspose.Cells for Python via .NET API المراجع
description:
type: docs
weight: 50
url: /ar/aspose.cells/formulasettings/calculation_id/
is_root: false
---
##  calculation_id عقار

يحدد إصدار محرك الحساب المستخدم لحساب القيم في المصنف.

###  ملاحظات

هذه الخاصية مخصصة فقط لحفظ الإعدادات في ملف جدول البيانات الناتج
حتى تتمكن التطبيقات الأخرى (مثل ms excel) من التصرف وفقًا لذلك عند تحميل الملف الناتج ومعالجته.
في حالة برنامج ms excel، إذا كانت قيمة هذه الخاصية أقل من معرف محرك إعادة الحساب المرتبط
مع التطبيق الذي يفتح الملف الناتج، سيقوم التطبيق بإعادة حساب نتائج جميع الصيغ
في هذا المصنف فورًا بعد تحميل الملف.
من أجل مراعاة الأداء بالنسبة لمعظم تطبيقات المستخدمين، فإننا لا نحسب أي صيغة في المصنف تلقائيًا،
بغض النظر عن القيمة التي تم تعيينها لهذه الخاصية.
###  تعريف:
```python
@property
def calculation_id(self):
    ...
@calculation_id.setter
def calculation_id(self, value):
    ...
```

###  أنظر أيضا
* الوحدة [`aspose.cells`](../../)
* فئة [`FormulaSettings`](/cells/python-net/ar/aspose.cells/formulasettings)
