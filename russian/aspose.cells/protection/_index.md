---
title: Protection класс
second_title: Aspose.Cells for Python via .NET API Ссылки
description:
type: docs
weight: 1150
url: /ru/aspose.cells/protection/
is_root: false
---
##  Protection класс
Представляет различные типы вариантов защиты, доступные для рабочего листа.



Тип Protection предоставляет следующие элементы:

###  Характеристики
| Свойство| Описание|
| :- | :- |
| [allow_deleting_column](/cells/python-net/ru/aspose.cells/protection/allow_deleting_column) | Указывает, разрешено ли удаление столбцов на защищенном листе.|
| [allow_deleting_row](/cells/python-net/ru/aspose.cells/protection/allow_deleting_row) | Указывает, разрешено ли удаление строк на защищенном листе.|
| [allow_filtering](/cells/python-net/ru/aspose.cells/protection/allow_filtering) | Указывает, разрешено ли пользователю использовать автофильтр, созданный до защиты листа.|
| [allow_formatting_cell](/cells/python-net/ru/aspose.cells/protection/allow_formatting_cell) | Указывает, разрешено ли форматирование ячеек на защищенном листе.|
| [allow_formatting_column](/cells/python-net/ru/aspose.cells/protection/allow_formatting_column) | Указывает, разрешено ли форматирование столбцов на защищенном листе.|
| [allow_formatting_row](/cells/python-net/ru/aspose.cells/protection/allow_formatting_row) |Указывает, разрешено ли форматирование строк на защищенном листе.|
| [allow_inserting_column](/cells/python-net/ru/aspose.cells/protection/allow_inserting_column) | Указывает, разрешена ли вставка столбцов на защищенном листе.|
| [allow_inserting_hyperlink](/cells/python-net/ru/aspose.cells/protection/allow_inserting_hyperlink) | Указывает, разрешена ли вставка гиперссылок на защищенный лист.|
| [allow_inserting_row](/cells/python-net/ru/aspose.cells/protection/allow_inserting_row) | Указывает, разрешена ли вставка строк на защищенном листе.|
| [allow_sorting](/cells/python-net/ru/aspose.cells/protection/allow_sorting) | Указывает, разрешена ли опция сортировки на защищенном листе.|
| [allow_using_pivot_table](/cells/python-net/ru/aspose.cells/protection/allow_using_pivot_table) | Указывает, разрешено ли пользователю манипулировать сводными таблицами на защищенном листе.|
| [allow_editing_content](/cells/python-net/ru/aspose.cells/protection/allow_editing_content) | Указывает, разрешено ли пользователю редактировать содержимое заблокированных ячеек на защищенном листе.|
| [allow_editing_object](/cells/python-net/ru/aspose.cells/protection/allow_editing_object) | Указывает, разрешено ли пользователю манипулировать объектами чертежей на защищенном листе.|
| [allow_editing_scenario](/cells/python-net/ru/aspose.cells/protection/allow_editing_scenario) | Указывает, разрешено ли пользователю редактировать сценарии на защищенном листе.|
| [allow_selecting_locked_cell](/cells/python-net/ru/aspose.cells/protection/allow_selecting_locked_cell) | Указывает, разрешено ли пользователю выбирать заблокированные ячейки на защищенном листе.|
| [allow_selecting_unlocked_cell](/cells/python-net/ru/aspose.cells/protection/allow_selecting_unlocked_cell) | Указывает, разрешено ли пользователю выбирать разблокированные ячейки на защищенном листе.|
| [password](/cells/python-net/ru/aspose.cells/protection/password) | Представляет собой пароль для защиты рабочего листа.|
| [is_protected_with_password](/cells/python-net/ru/aspose.cells/protection/is_protected_with_password) | Указывает, защищены ли рабочие листы паролем.|


###  Методы
| Метод| Описание|
| :- | :- |
| [`copy(self, source)`](/cells/python-net/ru/aspose.cells/protection/copy/#aspose.cells.protection) |Информация о защите от копирования.|
| [`verify_password(self, password)`](/cells/python-net/ru/aspose.cells/protection/verify_password/#str) | Проверяет пароль.|
| [`get_password_hash(self)`](/cells/python-net/ru/aspose.cells/protection/get_password_hash/#) | Получает хеш текущего пароля.|



###  Пример

```python
from aspose.cells import Workbook

# Instantiating a Workbook object
workbook = Workbook()
worksheet = workbook.worksheets[0]
# Allowing users to select locked cells of the worksheet
worksheet.protection.allow_selecting_locked_cell = True
# Allowing users to select unlocked cells of the worksheet
worksheet.protection.allow_selecting_unlocked_cell = True

```

###  Смотрите также
* модуль [`aspose.cells`](..)
