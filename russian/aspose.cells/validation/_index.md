---
title: Validation класс
second_title: Aspose.Cells for Python via .NET API Рекомендации
description:
type: docs
weight: 1610
url: /ru/aspose.cells/validation/
is_root: false
---
##  Validation класс
Представляет данные validation.settings.



Тип Validation предоставляет следующие элементы:

###  Характеристики
| Свойство| Описание|
| :- | :- |
| [operator](/cells/python-net/ru/aspose.cells/validation/operator) | Представляет оператор проверки данных.|
| [alert_style](/cells/python-net/ru/aspose.cells/validation/alert_style) | Представляет стиль оповещения проверки.|
| [type](/cells/python-net/ru/aspose.cells/validation/type) | Представляет тип проверки данных.|
| [input_message](/cells/python-net/ru/aspose.cells/validation/input_message) | Представляет входное сообщение проверки данных.|
| [input_title](/cells/python-net/ru/aspose.cells/validation/input_title) | Представляет заголовок диалогового окна ввода данных для проверки данных.|
| [error_message](/cells/python-net/ru/aspose.cells/validation/error_message) | Представляет сообщение об ошибке проверки данных.|
| [error_title](/cells/python-net/ru/aspose.cells/validation/error_title) | Представляет заголовок диалогового окна ошибки проверки данных.|
| [show_input](/cells/python-net/ru/aspose.cells/validation/show_input) | Указывает, будет ли отображаться входное сообщение проверки данных всякий раз, когда пользователь выбирает ячейку в диапазоне проверки данных.|
| [show_error](/cells/python-net/ru/aspose.cells/validation/show_error) | Указывает, будет ли отображаться сообщение об ошибке проверки данных всякий раз, когда пользователь вводит неверные данные.|
| [ignore_blank](/cells/python-net/ru/aspose.cells/validation/ignore_blank) | Указывает, разрешены ли пустые значения при проверке данных диапазона.|
| [formula1](/cells/python-net/ru/aspose.cells/validation/formula1) |Представляет значение или выражение, связанное с проверкой данных.|
| [formula2](/cells/python-net/ru/aspose.cells/validation/formula2) |Представляет значение или выражение, связанное с проверкой данных.|
| [value1](/cells/python-net/ru/aspose.cells/validation/value1) | Представляет первое значение, связанное с проверкой данных.|
| [value2](/cells/python-net/ru/aspose.cells/validation/value2) | Представляет второе значение, связанное с проверкой данных.|
| [in_cell_drop_down](/cells/python-net/ru/aspose.cells/validation/in_cell_drop_down) | Указывает, отображает ли проверка данных раскрывающийся список, содержащий допустимые значения.|
| [areas](/cells/python-net/ru/aspose.cells/validation/areas) | Получает все [`CellArea`](/cells/python-net/ru/aspose.cells/cellarea), содержащие настройки проверки данных.|


###  Методы
| Метод| Описание|
| :- | :- |
| [get_formula1](/cells/python-net/ru/aspose.cells/validation/get_formula1/#bool-bool) | Получает значение или выражение, связанное с этой проверкой.|
| [get_formula1](/cells/python-net/ru/aspose.cells/validation/get_formula1/#bool-bool-int-int) | Получает значение или выражение, связанное с этой проверкой для конкретной ячейки.|
| [get_formula2](/cells/python-net/ru/aspose.cells/validation/get_formula2/#bool-bool) | Получает значение или выражение, связанное с этой проверкой.|
| [get_formula2](/cells/python-net/ru/aspose.cells/validation/get_formula2/#bool-bool-int-int) | Получает значение или выражение, связанное с этой проверкой для конкретной ячейки.|
| [add_area](/cells/python-net/ru/aspose.cells/validation/add_area/#aspose.cells.CellArea) | Применяет проверку к области.|
| [add_area](/cells/python-net/ru/aspose.cells/validation/add_area/#aspose.cells.CellArea-bool-bool) | Применяет проверку к области.|
| [set_formula1](/cells/python-net/ru/aspose.cells/validation/set_formula1/#str-bool-bool) | Устанавливает значение или выражение, связанное с этой проверкой.|
| [set_formula2](/cells/python-net/ru/aspose.cells/validation/set_formula2/#str-bool-bool) | Устанавливает значение или выражение, связанное с этой проверкой.|
| [get_list_value](/cells/python-net/ru/aspose.cells/validation/get_list_value/#int-int) | Получите значение списка проверки для указанной ячейки.|
| [get_value](/cells/python-net/ru/aspose.cells/validation/get_value/#int-int-bool) | Получите значение проверки для конкретной ячейки.|
| [add_areas](/cells/python-net/ru/aspose.cells/validation/add_areas/#list-bool-bool) | Применяет проверку к заданным областям.|
| [remove_area](/cells/python-net/ru/aspose.cells/validation/remove_area/#aspose.cells.CellArea) | Удалите настройки проверки в диапазоне.|
| [remove_areas](/cells/python-net/ru/aspose.cells/validation/remove_areas/#list) | Удаляет эту проверку из заданных областей.|
| [remove_a_cell](/cells/python-net/ru/aspose.cells/validation/remove_a_cell/#int-int) | Удалите параметры проверки в ячейке.|
| [copy](/cells/python-net/ru/aspose.cells/validation/copy/#aspose.cells.Validation-aspose.cells.CopyOptions) | Проверка копирования.|



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
