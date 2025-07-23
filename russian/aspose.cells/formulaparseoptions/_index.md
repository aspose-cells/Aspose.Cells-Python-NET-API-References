---
title: FormulaParseOptions класс
second_title: Aspose.Cells for Python via .NET API Ссылки
description:
type: docs
weight: 720
url: /ru/aspose.cells/formulaparseoptions/
is_root: false
---
##  FormulaParseOptions класс
Представляет параметры при разборе формулы.



Тип FormulaParseOptions предоставляет следующие элементы:

###  Конструкторы
| Конструктор| Описание|
| :- | :- |
| [`__init__(self)`](/cells/python-net/ru/aspose.cells/formulaparseoptions/__init__/#) | Создает новый экземпляр FormulaParseOptions|


###  Характеристики
| Свойство| Описание|
| :- | :- |
| [locale_dependent](/cells/python-net/ru/aspose.cells/formulaparseoptions/locale_dependent) | Отформатирована ли формула в соответствии с региональными настройками. Значение по умолчанию — false.|
| [r1c1_style](/cells/python-net/ru/aspose.cells/formulaparseoptions/r1c1_style) | Соответствует ли формула стилю ссылки R1C1. Значение по умолчанию — false.|
| [check_add_in](/cells/python-net/ru/aspose.cells/formulaparseoptions/check_add_in) | Проверять ли надстройки в существующих внешних ссылках текущей книги на наличие определяемой пользователем функции без внешней ссылки.<br/> Значение по умолчанию — true (если определяемая пользователем функция соответствует одному дополнению в существующих внешних ссылках, то принять его за дополнение).|
| [parse](/cells/python-net/ru/aspose.cells/formulaparseoptions/parse) | Анализирует ли заданную формулу. Значение по умолчанию — true.<br/>Если значение равно false, то заданная строка формулы будет сохранена в ячейке до тех пор, пока пользователь не вызовет другие методы для ее анализа.<br/>или проанализированные данные формулы требуются для других операций, таких как вычисление формул.|
| [custom_function_definition](/cells/python-net/ru/aspose.cells/formulaparseoptions/custom_function_definition) | Определение для разбора пользовательских функций.|



###  Смотрите также
* модуль [`aspose.cells`](..)
