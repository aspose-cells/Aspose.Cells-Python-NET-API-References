---
title: ErrorCheckOption sınıfı
second_title: Aspose.Cells for Python via .NET API Referanslar
description:
type: docs
weight: 550
url: /tr/aspose.cells/errorcheckoption/
is_root: false
---
##  ErrorCheckOption sınıfı
Belirli aralıklara uygulanan hata kontrolü ayarı.



ErrorCheckOption türü aşağıdaki üyeleri ortaya çıkarır:

###  Yöntemler
| Yöntem| Tanım|
| :- | :- |
| [is_error_check](/cells/python-net/tr/aspose.cells/errorcheckoption/is_error_check/#aspose.cells.ErrorCheckType) | Verilen hata tipinin kontrol edilip edilmeyeceğini kontrol eder.|
| [set_error_check](/cells/python-net/tr/aspose.cells/errorcheckoption/set_error_check/#aspose.cells.ErrorCheckType-bool) | Verilen hata tipinin kontrol edilip edilmeyeceğini ayarlar.|
| [get_count_of_range](/cells/python-net/tr/aspose.cells/errorcheckoption/get_count_of_range/#) | Bu ayardan etkilenen aralıkların sayısını alır.|
| [add_range](/cells/python-net/tr/aspose.cells/errorcheckoption/add_range/#aspose.cells.CellArea) | Bu ayardan etkilenen bir aralık ekler.|
| [get_range](/cells/python-net/tr/aspose.cells/errorcheckoption/get_range/#int) | Verilen dizine göre bu ayarın etkilenen aralığını alır.|
| [remove_range](/cells/python-net/tr/aspose.cells/errorcheckoption/remove_range/#int) | Verilen dizine göre bir aralığı kaldırır.|



###  Örnek

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

###  Ayrıca bakınız
* modül [`aspose.cells`](..)
