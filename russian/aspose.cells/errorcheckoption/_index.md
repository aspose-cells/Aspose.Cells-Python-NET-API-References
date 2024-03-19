---
title: ErrorCheckOption класс
second_title: Aspose.Cells for Python via .NET API Рекомендации
description:
type: docs
weight: 550
url: /ru/aspose.cells/errorcheckoption/
is_root: false
---
##  ErrorCheckOption класс
Настройка проверки ошибок применяется к определенным диапазонам.



Тип ErrorCheckOption предоставляет следующие элементы:

###  Методы
| Метод| Описание|
| :- | :- |
| [is_error_check](/cells/python-net/ru/aspose.cells/errorcheckoption/is_error_check/#aspose.cells.ErrorCheckType) | Проверяет, будет ли проверяться данный тип ошибки.|
| [set_error_check](/cells/python-net/ru/aspose.cells/errorcheckoption/set_error_check/#aspose.cells.ErrorCheckType-bool) | Устанавливает, будет ли проверяться данный тип ошибки.|
| [get_count_of_range](/cells/python-net/ru/aspose.cells/errorcheckoption/get_count_of_range/#) | Получает количество диапазонов, на которые влияет этот параметр.|
| [add_range](/cells/python-net/ru/aspose.cells/errorcheckoption/add_range/#aspose.cells.CellArea) | Добавляет один диапазон, на который влияет эта настройка.|
| [get_range](/cells/python-net/ru/aspose.cells/errorcheckoption/get_range/#int) | Получает диапазон влияния этого параметра по заданному индексу.|
| [remove_range](/cells/python-net/ru/aspose.cells/errorcheckoption/remove_range/#int) | Удаляет один диапазон по заданному индексу.|



###  Пример

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

###  Смотрите также
* модуль [`aspose.cells`](..)
