---
title: ErrorCheckOption صف
second_title: Aspose.Cells for Python via .NET API المراجع
description:
type: docs
weight: 530
url: /ar/aspose.cells/errorcheckoption/
is_root: false
---
##  ErrorCheckOption صف
تم تطبيق إعداد التحقق من الخطأ على نطاقات معينة.



يكشف النوع ErrorCheckOption عن الأعضاء التاليين:

###  طُرق
| طريقة| وصف|
| :- | :- |
| [`is_error_check(self, error_check_type)`](/cells/python-net/ar/aspose.cells/errorcheckoption/is_error_check/#aspose.cells.errorchecktype) | التحقق مما إذا كان سيتم التحقق من نوع الخطأ المحدد.|
| [`set_error_check(self, error_check_type, is_check)`](/cells/python-net/ar/aspose.cells/errorcheckoption/set_error_check/#aspose.cells.errorchecktype-bool) | يحدد ما إذا كان سيتم التحقق من نوع الخطأ المحدد.|
| [`get_count_of_range(self)`](/cells/python-net/ar/aspose.cells/errorcheckoption/get_count_of_range/#) | يحصل على عدد النطاقات المتأثرة بهذا الإعداد.|
| [`add_range(self, ca)`](/cells/python-net/ar/aspose.cells/errorcheckoption/add_range/#aspose.cells.cellarea) | يضيف نطاقًا واحدًا متأثرًا بهذا الإعداد.|
| [`get_range(self, index)`](/cells/python-net/ar/aspose.cells/errorcheckoption/get_range/#int) | يحصل على النطاق المتأثر بهذا الإعداد بواسطة الفهرس المحدد.|
| [`remove_range(self, index)`](/cells/python-net/ar/aspose.cells/errorcheckoption/remove_range/#int) | يقوم بإزالة نطاق واحد حسب الفهرس المحدد.|



###  مثال

```python
from aspose.cells import CellArea, ErrorCheckType, Workbook

workbook = Workbook()
opts = workbook.worksheets[0].error_check_options
optionIdx = opts.add()
opt = opts[optionIdx]
opt.set_error_check(ErrorCheckType.INCONSIST_FORMULA, False)
opt.set_error_check(ErrorCheckType.INCONSIST_RANGE, False)
opt.set_error_check(ErrorCheckType.TEXT_DATE, False)
opt.set_error_check(ErrorCheckType.TEXT_NUMBER, False)
opt.set_error_check(ErrorCheckType.VALIDATION, False)
opt.add_range(CellArea.create_cell_area("A1", "B10"))
workbook.save(r"Book1.xlsx")

```

###  أنظر أيضا
* الوحدة [`aspose.cells`](..)
