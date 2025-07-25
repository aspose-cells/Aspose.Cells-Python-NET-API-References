---
title: Validation класс
second_title: Aspose.Cells for Python via .NET API Ссылки
description:
type: docs
weight: 1520
url: /ru/aspose.cells/validation/
is_root: false
---
##  Validation класс
Представляет настройки проверки данных.



Тип Validation предоставляет следующие элементы:

###  Характеристики
| Свойство| Описание|
| :- | :- |
| [operator](/cells/python-net/ru/aspose.cells/validation/operator) | Представляет собой оператора проверки данных.|
| [alert_style](/cells/python-net/ru/aspose.cells/validation/alert_style) | Представляет стиль оповещения о проверке.|
| [type](/cells/python-net/ru/aspose.cells/validation/type) | Представляет тип проверки данных.|
| [input_message](/cells/python-net/ru/aspose.cells/validation/input_message) | Представляет собой входное сообщение проверки данных.|
| [input_title](/cells/python-net/ru/aspose.cells/validation/input_title) | Представляет заголовок диалогового окна ввода проверки данных.|
| [error_message](/cells/python-net/ru/aspose.cells/validation/error_message) | Представляет сообщение об ошибке проверки данных.|
| [error_title](/cells/python-net/ru/aspose.cells/validation/error_title) | Представляет заголовок диалогового окна с сообщением об ошибке проверки данных.|
| [show_input](/cells/python-net/ru/aspose.cells/validation/show_input) | Указывает, будет ли отображаться сообщение о проверке данных каждый раз, когда пользователь выбирает ячейку в диапазоне проверки данных.|
| [show_error](/cells/python-net/ru/aspose.cells/validation/show_error) | Указывает, будет ли отображаться сообщение об ошибке проверки данных каждый раз, когда пользователь вводит неверные данные.|
| [ignore_blank](/cells/python-net/ru/aspose.cells/validation/ignore_blank) |Указывает, разрешены ли пустые значения при проверке диапазона данных.|
| [formula1](/cells/python-net/ru/aspose.cells/validation/formula1) | Представляет значение или выражение, связанное с проверкой данных.|
| [formula2](/cells/python-net/ru/aspose.cells/validation/formula2) | Представляет значение или выражение, связанное с проверкой данных.|
| [value1](/cells/python-net/ru/aspose.cells/validation/value1) | Представляет первое значение, связанное с проверкой данных.|
| [value2](/cells/python-net/ru/aspose.cells/validation/value2) | Представляет второе значение, связанное с проверкой данных.|
| [in_cell_drop_down](/cells/python-net/ru/aspose.cells/validation/in_cell_drop_down) | Указывает, отображает ли проверка данных раскрывающийся список, содержащий приемлемые значения.|
| [areas](/cells/python-net/ru/aspose.cells/validation/areas) | Получает все [`CellArea`](/cells/python-net/ru/aspose.cells/cellarea), содержащие настройки проверки данных.|


###  Методы
| Метод| Описание|
| :- | :- |
| [`get_formula1(self, is_r1c1, is_local)`](/cells/python-net/ru/aspose.cells/validation/get_formula1/#bool-bool) | Получает значение или выражение, связанное с этой проверкой.|
| [`get_formula1(self, is_r1c1, is_local, row, column)`](/cells/python-net/ru/aspose.cells/validation/get_formula1/#bool-bool-int-int) | Возвращает значение или выражение, связанное с этой проверкой для определенной ячейки.|
| [`get_formula2(self, is_r1c1, is_local)`](/cells/python-net/ru/aspose.cells/validation/get_formula2/#bool-bool) | Получает значение или выражение, связанное с этой проверкой.|
| [`get_formula2(self, is_r1c1, is_local, row, column)`](/cells/python-net/ru/aspose.cells/validation/get_formula2/#bool-bool-int-int) | Возвращает значение или выражение, связанное с этой проверкой для определенной ячейки.|
| [`add_area(self, cell_area)`](/cells/python-net/ru/aspose.cells/validation/add_area/#aspose.cells.cellarea) | Применяет проверку к области.|
| [`add_area(self, cell_area, check_intersection, check_edge)`](/cells/python-net/ru/aspose.cells/validation/add_area/#aspose.cells.cellarea-bool-bool) | Применяет проверку к области.|
| [`set_formula1(self, formula, is_r1c1, is_local)`](/cells/python-net/ru/aspose.cells/validation/set_formula1/#str-bool-bool) | Устанавливает значение или выражение, связанное с этой проверкой.|
| [`set_formula2(self, formula, is_r1c1, is_local)`](/cells/python-net/ru/aspose.cells/validation/set_formula2/#str-bool-bool) | Устанавливает значение или выражение, связанное с этой проверкой.|
| [`get_list_value(self, row, column)`](/cells/python-net/ru/aspose.cells/validation/get_list_value/#int-int) | Получить значение для списка проверки для указанной ячейки.|
| [`get_value(self, row, column, is_value1)`](/cells/python-net/ru/aspose.cells/validation/get_value/#int-int-bool) | Получить значение проверки для конкретной ячейки.|
| [`add_areas(self, areas, check_intersection, check_edge)`](/cells/python-net/ru/aspose.cells/validation/add_areas/#list-bool-bool) | Применяет проверку к заданным областям.|
| [`remove_area(self, cell_area)`](/cells/python-net/ru/aspose.cells/validation/remove_area/#aspose.cells.cellarea) | Удалить настройки проверки в диапазоне.|
| [`remove_areas(self, areas)`](/cells/python-net/ru/aspose.cells/validation/remove_areas/#list) |Удаляет данную проверку из указанных областей.|
| [`remove_a_cell(self, row, column)`](/cells/python-net/ru/aspose.cells/validation/remove_a_cell/#int-int) | Удалить настройки проверки в ячейке.|
| [`copy(self, source, copy_option)`](/cells/python-net/ru/aspose.cells/validation/copy/#aspose.cells.validation-aspose.cells.copyoptions) | Проверка копии.|



###  Пример

```python
from aspose.cells import CellArea, OperatorType, ValidationType, Workbook

workbook = Workbook()
validations = workbook.worksheets[0].validations
area = CellArea.create_cell_area(0, 0, 1, 1)
validation = validations[validations.add(area)]
validation.type = ValidationType.WHOLE_NUMBER
validation.operator = OperatorType.BETWEEN
validation.formula1 = "3"
validation.formula2 = "1234"

```

###  Смотрите также
* модуль [`aspose.cells`](..)
* класс [`CellArea`](/cells/python-net/ru/aspose.cells/cellarea)
