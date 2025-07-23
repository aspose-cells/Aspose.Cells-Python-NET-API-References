---
title: ErrorCheckOption klass
second_title: Aspose.Cells for Python via .NET API Referenser
description:
type: docs
weight: 530
url: /sv/aspose.cells/errorcheckoption/
is_root: false
---
##  ErrorCheckOption klass
Felkontrollinställning tillämpad på vissa intervall.



Typen ErrorCheckOption avslöjar följande medlemmar:

###  Metoder
| Metod| Beskrivning|
| :- | :- |
| [`is_error_check(self, error_check_type)`](/cells/python-net/sv/aspose.cells/errorcheckoption/is_error_check/#aspose.cells.errorchecktype) | Kontrollerar om en given feltyp kommer att kontrolleras.|
| [`set_error_check(self, error_check_type, is_check)`](/cells/python-net/sv/aspose.cells/errorcheckoption/set_error_check/#aspose.cells.errorchecktype-bool) | Anger om en given feltyp ska kontrolleras.|
| [`get_count_of_range(self)`](/cells/python-net/sv/aspose.cells/errorcheckoption/get_count_of_range/#) | Hämtar antalet intervall som påverkas av den här inställningen.|
| [`add_range(self, ca)`](/cells/python-net/sv/aspose.cells/errorcheckoption/add_range/#aspose.cells.cellarea) | Lägger till ett påverkat område av den här inställningen.|
| [`get_range(self, index)`](/cells/python-net/sv/aspose.cells/errorcheckoption/get_range/#int) | Hämtar det påverkade intervallet för denna inställning med givet index.|
| [`remove_range(self, index)`](/cells/python-net/sv/aspose.cells/errorcheckoption/remove_range/#int) | Tar bort ett område med givet index.|



###  Exempel

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

###  Se även
* modul [`aspose.cells`](..)
