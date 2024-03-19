---
title: ErrorCheckOption صف
second_title: Aspose.Cells for Python via .NET API المراجع
description:
type: docs
weight: 550
url: /ar/aspose.cells/errorcheckoption/
is_root: false
---
##  ErrorCheckOption صف
تم تطبيق إعداد التحقق من الأخطاء على نطاقات معينة.



يكشف النوع ErrorCheckOption عن الأعضاء التاليين:

###  طُرق
| طريقة| وصف|
| :- | :- |
| [is_error_check](/cells/python-net/ar/aspose.cells/errorcheckoption/is_error_check/#aspose.cells.ErrorCheckType) | يتحقق مما إذا كان سيتم التحقق من نوع الخطأ المحدد.|
| [set_error_check](/cells/python-net/ar/aspose.cells/errorcheckoption/set_error_check/#aspose.cells.ErrorCheckType-bool) | يضبط ما إذا كان سيتم التحقق من نوع الخطأ المحدد.|
| [get_count_of_range](/cells/python-net/ar/aspose.cells/errorcheckoption/get_count_of_range/#) | الحصول على عدد النطاقات التي تأثرت بهذا الإعداد.|
| [add_range](/cells/python-net/ar/aspose.cells/errorcheckoption/add_range/#aspose.cells.CellArea) | يضيف نطاقًا واحدًا متأثرًا بهذا الإعداد.|
| [get_range](/cells/python-net/ar/aspose.cells/errorcheckoption/get_range/#int) | يحصل على النطاق المتأثر لهذا الإعداد من خلال فهرس معين.|
| [remove_range](/cells/python-net/ar/aspose.cells/errorcheckoption/remove_range/#int) | إزالة نطاق واحد حسب فهرس معين.|



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
