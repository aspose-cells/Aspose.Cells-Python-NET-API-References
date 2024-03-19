---
title: CellsHelper класс
second_title: Aspose.Cells for Python via .NET API Рекомендации
description:
type: docs
weight: 240
url: /ru/aspose.cells/cellshelper/
is_root: false
---
##  CellsHelper класс
Предоставляет вспомогательные функции.



Тип CellsHelper предоставляет следующие элементы:

###  Характеристики
| Свойство| Описание|
| :- | :- |
| [significant_digits](/cells/python-net/ru/aspose.cells/cellshelper/significant_digits) | Получает и задает количество значащих цифр.<br/> Значение по умолчанию — 17.|
| [dpi](/cells/python-net/ru/aspose.cells/cellshelper/dpi) | Получает DPI машины.|
| [startup_path](/cells/python-net/ru/aspose.cells/cellshelper/startup_path) | Получает или задает путь запуска, на который ссылаются некоторые внешние ссылки на формулы.|
| [alt_start_path](/cells/python-net/ru/aspose.cells/cellshelper/alt_start_path) | Получает или задает альтернативный путь запуска, на который ссылаются некоторые внешние ссылки на формулы.|
| [library_path](/cells/python-net/ru/aspose.cells/cellshelper/library_path) | Получает или задает путь к библиотеке, на которую ссылаются некоторые внешние ссылки на формулы.|
| [custom_implementation_factory](/cells/python-net/ru/aspose.cells/cellshelper/custom_implementation_factory) | Получает или задает фабрику для создания экземпляров со специальной реализацией.|
| [is_cloud_platform](/cells/python-net/ru/aspose.cells/cellshelper/is_cloud_platform) | Установите для этого свойства значение True при работе на облачной платформе, например Azure, AWSLambda и т. д.|


###  Методы
| Метод| Описание|
| :- | :- |
| [create_safe_sheet_name](/cells/python-net/ru/aspose.cells/cellshelper/create_safe_sheet_name/#str) | Проверяет заданное имя листа и при необходимости создает допустимое.<br/>Если заданное имя листа соответствует правилам имени листа Excel, верните его.<br/>В противном случае строка будет усечена, если длина превышает предел.<br/>и недопустимые символы будут заменены на ' ', а затем вернут перестроенное строковое значение.|
| [create_safe_sheet_name](/cells/python-net/ru/aspose.cells/cellshelper/create_safe_sheet_name/#str-char) | Проверяет заданное имя листа и при необходимости создает допустимое.<br/>Если заданное имя листа соответствует правилам имени листа Excel, верните его.<br/>В противном случае строка будет усечена, если длина превышает предел.<br/> и недопустимые символы будут заменены заданным символом, а затем вернут перестроенное строковое значение.|
| [get_text_width](/cells/python-net/ru/aspose.cells/cellshelper/get_text_width/#str-aspose.cells.Font-float) | Получить ширину текста в пунктах.|
| [get_version](/cells/python-net/ru/aspose.cells/cellshelper/get_version/#) | Получите релизную версию.|
| [cell_name_to_index](/cells/python-net/ru/aspose.cells/cellshelper/cell_name_to_index/#str-any-any) | Получает индексы строк и столбцов ячейки в соответствии с ее именем.|
| [cell_index_to_name](/cells/python-net/ru/aspose.cells/cellshelper/cell_index_to_name/#int-int) | Получает имя ячейки в соответствии с индексами ее строк и столбцов.|
| [column_index_to_name](/cells/python-net/ru/aspose.cells/cellshelper/column_index_to_name/#int) | Получает имя столбца в соответствии с индексом столбца.|
| [column_name_to_index](/cells/python-net/ru/aspose.cells/cellshelper/column_name_to_index/#str) | Получает индекс столбца в соответствии с именем столбца.|
| [row_index_to_name](/cells/python-net/ru/aspose.cells/cellshelper/row_index_to_name/#int) | Получает имя строки в соответствии с индексом строки.|
| [row_name_to_index](/cells/python-net/ru/aspose.cells/cellshelper/row_name_to_index/#str) | Получает индекс строки в соответствии с именем строки.|
| [convert_r1c1_formula_to_a1](/cells/python-net/ru/aspose.cells/cellshelper/convert_r1c1_formula_to_a1/#str-int-int) | Преобразует формулу ячейки r1c1 в формулу A1.|
| [convert_a1_formula_to_r1c1](/cells/python-net/ru/aspose.cells/cellshelper/convert_a1_formula_to_r1c1/#str-int-int) | Преобразует формулу A1 ячейки в формулу r1c1.|
| [get_date_time_from_double](/cells/python-net/ru/aspose.cells/cellshelper/get_date_time_from_double/#float-bool) | Преобразуйте двойное значение в значение даты и времени.|
| [get_double_from_date_time](/cells/python-net/ru/aspose.cells/cellshelper/get_double_from_date_time/#DateTime-bool) | Преобразуйте дату и время в двойное значение.|
| [get_used_colors](/cells/python-net/ru/aspose.cells/cellshelper/get_used_colors/#aspose.cells.Workbook) | Получает все использованные цвета в книге.|
| [add_add_in_function](/cells/python-net/ru/aspose.cells/cellshelper/add_add_in_function/#str-int-int-list-aspose.cells.ParameterType) | Добавьте дополнительную функцию.|
| [merge_files](/cells/python-net/ru/aspose.cells/cellshelper/merge_files/#list-str-str) | Объединяет несколько больших файлов xls в файл xls.|
| [need_quote_in_formula](/cells/python-net/ru/aspose.cells/cellshelper/need_quote_in_formula/#str) |Указывает, следует ли заключать имя листа в одинарные кавычки.|
| [init_for_dot_net_core](/cells/python-net/ru/aspose.cells/cellshelper/init_for_dot_net_core/#) | Выполните инициализацию программы .NetCore.<br/> Мы предлагаем вам сначала вызывать этот метод для всех инициализаций .NetCore.<br/>Например:<br/>CellsHelper.InitForDotNetCore();<br/> Рабочая книга wb = новая рабочая книга();|



###  Смотрите также
* модуль [`aspose.cells`](..)
