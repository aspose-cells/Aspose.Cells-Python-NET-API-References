---
title: cell عقار
second_title: Aspose.Cells for Python via .NET API المراجع
description:
type: docs
weight: 70
url: /ar/aspose.cells/calculationdata/cell/
is_root: false
---
##  cell عقار

يحصل على الكائن Cell حيث توجد الوظيفة.

###  ملاحظات

عند حساب صيغة دون تعيينها على cell،
مثل [`Worksheet.calculate_formula`](/cells/python-net/ar/aspose.cells/worksheet/calculate_formula)،
سيتم حساب الصيغة تمامًا كما تم ضبطها على cell A1،
لذا فإن كلا من [`CalculationData.cell_row`](/cells/python-net/ar/aspose.cells/calculationdata#cell_row) و[`CalculationData.cell_column`](/cells/python-net/ar/aspose.cells/calculationdata#cell_column) هما 0.
ومع ذلك، ربما لم يتم إنشاء مثيل للرقم cell A1 في ورقة العمل.
لذا، في مثل هذا النوع من المواقف، ستكون هذه الخاصية فارغة.
###  تعريف:
```python
@property
def cell(self):
    ...
```

###  أنظر أيضا
* الوحدة [`aspose.cells`](../../)
* فئة [`CalculationData`](/cells/python-net/ar/aspose.cells/calculationdata)
* فئة [`Cell`](/cells/python-net/ar/aspose.cells/cell)
