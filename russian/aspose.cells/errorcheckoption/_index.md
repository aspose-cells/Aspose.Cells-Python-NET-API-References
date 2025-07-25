---
title: ErrorCheckOption класс
second_title: Aspose.Cells for Python via .NET API Ссылки
description:
type: docs
weight: 530
url: /ru/aspose.cells/errorcheckoption/
is_root: false
---
##  ErrorCheckOption класс
Настройка проверки ошибок применена к определенным диапазонам.



Тип ErrorCheckOption предоставляет следующие элементы:

###  Методы
| Метод| Описание|
| :- | :- |
| [`is_error_check(self, error_check_type)`](/cells/python-net/ru/aspose.cells/errorcheckoption/is_error_check/#aspose.cells.errorchecktype) | Проверяет, будет ли проверяться заданный тип ошибки.|
| [`set_error_check(self, error_check_type, is_check)`](/cells/python-net/ru/aspose.cells/errorcheckoption/set_error_check/#aspose.cells.errorchecktype-bool) | Устанавливает, будет ли проверяться заданный тип ошибки.|
| [`get_count_of_range(self)`](/cells/python-net/ru/aspose.cells/errorcheckoption/get_count_of_range/#) | Возвращает количество диапазонов, на которые влияет этот параметр.|
| [`add_range(self, ca)`](/cells/python-net/ru/aspose.cells/errorcheckoption/add_range/#aspose.cells.cellarea) | Добавляет один диапазон, на который влияет эта настройка.|
| [`get_range(self, index)`](/cells/python-net/ru/aspose.cells/errorcheckoption/get_range/#int) | Получает диапазон влияния этого параметра по заданному индексу.|
| [`remove_range(self, index)`](/cells/python-net/ru/aspose.cells/errorcheckoption/remove_range/#int) | Удаляет один диапазон по указанному индексу.|



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
