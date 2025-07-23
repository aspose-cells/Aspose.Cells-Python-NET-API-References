---
title: calculation_mode عقار
second_title: Aspose.Cells for Python via .NET API المراجع
description:
type: docs
weight: 60
url: /ar/aspose.cells/formulasettings/calculation_mode/
is_root: false
---
##  calculation_mode عقار

يحصل على أو يعين الوضع لحساب المصنف في MS Excel.

###  ملاحظات

هذه الخاصية مخصصة فقط لحفظ الإعدادات في ملف جدول البيانات الناتج
حتى تتمكن التطبيقات الأخرى (مثل ms excel) من التصرف وفقًا لذلك عند تحميل الملف الناتج ومعالجته.
من أجل مراعاة الأداء بالنسبة لتطبيقات معظم المستخدمين، فإننا لا نحسب أي صيغة في المصنف تلقائيًا،
بغض النظر عن الوضع الذي تم تعيينه لهذه الخاصية.
إذا احتاج المستخدم إلى حساب الصيغ، فيرجى دائمًا استدعاء الأساليب على كائنات مختلفة وفقًا للمتطلبات:
[`Workbook.calculate_formula`](/cells/python-net/aspose.cells/workbook/calculate_formula), [`Worksheet.calculate_formula`](/cells/python-net/aspose.cells/worksheet/calculate_formula),
[`Cell.calculate`](/cells/python-net/ar/aspose.cells/cell/calculate)، ...الخ.
###  تعريف:
```python
@property
def calculation_mode(self):
    ...
@calculation_mode.setter
def calculation_mode(self, value):
    ...
```

###  أنظر أيضا
* الوحدة [`aspose.cells`](../../)
* فئة [`CalcModeType`](/cells/python-net/ar/aspose.cells/calcmodetype)
* فئة [`FormulaSettings`](/cells/python-net/ar/aspose.cells/formulasettings)
