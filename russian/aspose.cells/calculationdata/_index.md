---
title: CalculationData класс
second_title: Aspose.Cells for Python via .NET API Рекомендации
description:
type: docs
weight: 120
url: /ru/aspose.cells/calculationdata/
is_root: false
---
##  CalculationData класс
Представляет необходимые данные при вычислении одной функции, такие как имя функции, параметры и т. д.



Тип CalculationData предоставляет следующие элементы:

###  Характеристики
| Свойство| Описание|
| :- | :- |
| [calculated_value](/cells/python-net/ru/aspose.cells/calculationdata/calculated_value) | Получает или задает расчетное значение для этой функции.|
| [workbook](/cells/python-net/ru/aspose.cells/calculationdata/workbook) | Получает объект Workbook, в котором находится функция.|
| [worksheet](/cells/python-net/ru/aspose.cells/calculationdata/worksheet) | Получает объект Worksheet, в котором находится функция.|
| [cell_row](/cells/python-net/ru/aspose.cells/calculationdata/cell_row) | Получает индекс строки ячейки, в которой находится функция.|
| [cell_column](/cells/python-net/ru/aspose.cells/calculationdata/cell_column) | Получает индекс столбца ячейки, в которой находится функция.|
| [cell](/cells/python-net/ru/aspose.cells/calculationdata/cell) | Получает объект Cell, в котором находится функция.|
| [function_name](/cells/python-net/ru/aspose.cells/calculationdata/function_name) |Получает имя функции для вычисления.|
| [param_count](/cells/python-net/ru/aspose.cells/calculationdata/param_count) | Получает количество параметров|


###  Методы
| Метод| Описание|
| :- | :- |
| [get_param_value](/cells/python-net/ru/aspose.cells/calculationdata/get_param_value/#int) | Получает представленный объект значения параметра по заданному индексу.|
| [get_param_value_in_array_mode](/cells/python-net/ru/aspose.cells/calculationdata/get_param_value_in_array_mode/#int-int-int) | Получает значения параметра по заданному индексу.<br/>Если параметр представляет собой какое-то выражение, которое необходимо вычислить,<br/> тогда он будет рассчитан в режиме массива.|
| [get_param_text](/cells/python-net/ru/aspose.cells/calculationdata/get_param_text/#int) | Получает буквальный текст параметра по заданному индексу.|



###  Примечания

Все объекты, предоставляемые этим классом, предназначены только для чтения.
Пользователь не должен изменять какие-либо данные в Рабочей книге в процессе расчета формулы.
В противном случае может возникнуть непредвиденный результат или исключение.

###  Смотрите также
* модуль [`aspose.cells`](..)
