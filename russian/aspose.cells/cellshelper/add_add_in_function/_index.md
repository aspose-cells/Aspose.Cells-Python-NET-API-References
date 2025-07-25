---
title: add_add_in_function метод
second_title: Aspose.Cells for Python via .NET API Ссылки
description:
type: docs
weight: 20
url: /ru/aspose.cells/cellshelper/add_add_in_function/
is_root: false
---
##  add_add_in_function(, функция, минимальное_количество_параметров, максимальное_количество_параметров, тип_параметров, тип_значения_функции){#str-int-int-list-aspose.cells.ParameterType}
Добавить дополнительную функцию.



```python

@staticmethod
def add_add_in_function(function, min_count_of_parameters, max_count_of_parameters, paramers_type, function_value_type):
    ...
```


| Параметр| Тип| Описание|
| :- | :- | :- |
| function | str | Имя функции.|
| min_count_of_parameters | int | Минимальное количество параметров, требуемых этой функцией|
| max_count_of_parameters | int | Максимальное количество параметров, которое допускает эта функция.|
| paramers_type | list | Тип исключенных параметров функции|
| function_value_type | [`ParameterType`](/cells/python-net/ru/aspose.cells/parametertype) | Тип значения функции.|
###  Примечания

ПРИМЕЧАНИЕ: Этот элемент устарел. Вместо этого,
используйте методы WorksheetCollection.RegisterAddInFunction().
 Этот метод будет удален через 12 месяцев, с января 2022 года.
Aspose приносит извинения за любые причиненные вам неудобства.


###  Смотрите также
* модуль [`aspose.cells`](../../)
* класс [`CellsHelper`](/cells/python-net/ru/aspose.cells/cellshelper)
