---
title: ErrorCheckOption classe
second_title: Aspose.Cells for Python via .NET API Referenze
description:
type: docs
weight: 550
url: /it/aspose.cells/errorcheckoption/
is_root: false
---
##  ErrorCheckOption classe
Impostazione del controllo errori applicata su determinati intervalli.



Il tipo ErrorCheckOption espone i seguenti membri:

###  Metodi
| Metodo| Descrizione|
| :- | :- |
| [is_error_check](/cells/python-net/it/aspose.cells/errorcheckoption/is_error_check/#aspose.cells.ErrorCheckType) | Controlla se verrà controllato il tipo di errore specificato.|
| [set_error_check](/cells/python-net/it/aspose.cells/errorcheckoption/set_error_check/#aspose.cells.ErrorCheckType-bool) | Imposta se verrà controllato il tipo di errore specificato.|
| [get_count_of_range](/cells/python-net/it/aspose.cells/errorcheckoption/get_count_of_range/#) | Ottiene il conteggio degli intervalli influenzati da questa impostazione.|
| [add_range](/cells/python-net/it/aspose.cells/errorcheckoption/add_range/#aspose.cells.CellArea) | Aggiunge un intervallo influenzato da questa impostazione.|
| [get_range](/cells/python-net/it/aspose.cells/errorcheckoption/get_range/#int) | Ottiene l'intervallo influenzato da questa impostazione in base all'indice specificato.|
| [remove_range](/cells/python-net/it/aspose.cells/errorcheckoption/remove_range/#int) | Rimuove un intervallo in base all'indice specificato.|



###  Esempio

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

###  Guarda anche
* modulo [`aspose.cells`](..)
