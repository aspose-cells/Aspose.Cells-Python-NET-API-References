---
title: SpreadsheetLocker класс
second_title: Aspose.Cells for Python via .NET API Ссылки
description:
type: docs
weight: 170
url: /ru/aspose.cells.lowcode/spreadsheetlocker/
is_root: false
---
##  SpreadsheetLocker класс
Низкокодовый API для блокировки файла электронной таблицы.



Тип SpreadsheetLocker предоставляет следующие элементы:

###  Методы
| Метод| Описание|
| :- | :- |
| [`process(, template_file, result_file, open_password, write_password)`](/cells/python-net/ru/aspose.cells.lowcode/spreadsheetlocker/process/#str-str-str-str) | Блокирует файл электронной таблицы с указанными настройками.|
| [`process(, load_options, save_options, open_password, write_password)`](/cells/python-net/ru/aspose.cells.lowcode/spreadsheetlocker/process/#aspose.cells.lowcode.lowcodeloadoptions-aspose.cells.lowcode.lowcodesaveoptions-str-str) | Блокирует файл электронной таблицы с указанными настройками.|
| [`process(, load_options, save_options, open_password, write_password, workbook_password, workbook_type)`](/cells/python-net/ru/aspose.cells.lowcode/spreadsheetlocker/process/#aspose.cells.lowcode.lowcodeloadoptions-aspose.cells.lowcode.lowcodesaveoptions-str-str-str-aspose.cells.protectiontype) | Блокирует файл электронной таблицы с указанными настройками.|
| [`process(, load_options, save_options, provider)`](/cells/python-net/ru/aspose.cells.lowcode/spreadsheetlocker/process/#aspose.cells.lowcode.lowcodeloadoptions-aspose.cells.lowcode.lowcodesaveoptions-aspose.cells.lowcode.abstractlowcodeprotectionprovider) | Блокирует файл электронной таблицы с указанными настройками.|



###  Пример

```python
from aspose.cells.lowcode import SpreadsheetLocker

SpreadsheetLocker.process("template.xlsx", "locked.xlsx", "mypassword", "mypassword")

```

###  Смотрите также
* модуль [`aspose.cells.lowcode`](..)
