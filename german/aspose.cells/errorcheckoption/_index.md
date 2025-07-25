---
title: ErrorCheckOption Klasse
second_title: Aspose.Cells for Python via .NET API Referenzen
description:
type: docs
weight: 530
url: /de/aspose.cells/errorcheckoption/
is_root: false
---
##  ErrorCheckOption Klasse
Auf bestimmte Bereiche wird eine Fehlerprüfungseinstellung angewendet.



Der Typ ErrorCheckOption macht die folgenden Member verfügbar:

###  Methoden
| Methode| Beschreibung|
| :- | :- |
| [`is_error_check(self, error_check_type)`](/cells/python-net/de/aspose.cells/errorcheckoption/is_error_check/#aspose.cells.errorchecktype) | Überprüft, ob der angegebene Fehlertyp überprüft wird.|
| [`set_error_check(self, error_check_type, is_check)`](/cells/python-net/de/aspose.cells/errorcheckoption/set_error_check/#aspose.cells.errorchecktype-bool) | Legt fest, ob der angegebene Fehlertyp überprüft wird.|
| [`get_count_of_range(self)`](/cells/python-net/de/aspose.cells/errorcheckoption/get_count_of_range/#) | Ruft die Anzahl der Bereiche ab, die von dieser Einstellung beeinflusst werden.|
| [`add_range(self, ca)`](/cells/python-net/de/aspose.cells/errorcheckoption/add_range/#aspose.cells.cellarea) | Fügt einen durch diese Einstellung beeinflussten Bereich hinzu.|
| [`get_range(self, index)`](/cells/python-net/de/aspose.cells/errorcheckoption/get_range/#int) | Ruft den beeinflussten Bereich dieser Einstellung anhand des angegebenen Index ab.|
| [`remove_range(self, index)`](/cells/python-net/de/aspose.cells/errorcheckoption/remove_range/#int) | Entfernt einen Bereich anhand des angegebenen Index.|



###  Beispiel

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

###  Siehe auch
* Modul [`aspose.cells`](..)
