---
title: CellsHelper класс
second_title: Aspose.Cells for Python via .NET API Ссылки
description:
type: docs
weight: 210
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
| [dpi](/cells/python-net/ru/aspose.cells/cellshelper/dpi) | Получает DPI устройства.|
| [startup_path](/cells/python-net/ru/aspose.cells/cellshelper/startup_path) | Возвращает или задает путь запуска, на который ссылаются некоторые внешние формулы.|
| [alt_start_path](/cells/python-net/ru/aspose.cells/cellshelper/alt_start_path) | Возвращает или задает альтернативный путь запуска, на который ссылаются некоторые внешние ссылки формул.|
| [library_path](/cells/python-net/ru/aspose.cells/cellshelper/library_path) |Возвращает или задает путь к библиотеке, на которую ссылаются некоторые внешние формулы.|
| [custom_implementation_factory](/cells/python-net/ru/aspose.cells/cellshelper/custom_implementation_factory) | Возвращает или задает фабрику для создания экземпляров со специальной реализацией.|
| [is_cloud_platform](/cells/python-net/ru/aspose.cells/cellshelper/is_cloud_platform) | Установите это свойство в значение True при работе на облачной платформе, например: Azure, AWSLambda и т. д.|


###  Методы
| Метод| Описание|
| :- | :- |
| [`create_safe_sheet_name(, name_proposal)`](/cells/python-net/ru/aspose.cells/cellshelper/create_safe_sheet_name/#str) | Проверяет указанное имя листа и при необходимости создает допустимое.<br/>Если заданное имя листа соответствует правилам именования листов Excel, то вернуть его.<br/>В противном случае строка будет обрезана, если длина превысит лимит.<br/> и недопустимые символы будут заменены на « », а затем вернется восстановленное строковое значение.|
| [`create_safe_sheet_name(, name_proposal, replace_char)`](/cells/python-net/ru/aspose.cells/cellshelper/create_safe_sheet_name/#str-char) | Проверяет указанное имя листа и при необходимости создает допустимое.<br/>Если заданное имя листа соответствует правилам именования листов Excel, то вернуть его.<br/>В противном случае строка будет обрезана, если длина превысит лимит.<br/> и недопустимые символы будут заменены заданным символом, а затем вернется восстановленное строковое значение.|
| [`get_text_width(, text, font, scaling)`](/cells/python-net/ru/aspose.cells/cellshelper/get_text_width/#str-aspose.cells.font-float) | Получить ширину текста в пунктах.|
| [`get_version()`](/cells/python-net/ru/aspose.cells/cellshelper/get_version/#) | Получите релизную версию.|
| [`cell_name_to_index(, cell_name, row, column)`](/cells/python-net/ru/aspose.cells/cellshelper/cell_name_to_index/#str-any-any) | Получает индексы строк и столбцов ячейки в соответствии с ее именем.|
| [`cell_index_to_name(, row, column)`](/cells/python-net/ru/aspose.cells/cellshelper/cell_index_to_name/#int-int) | Получает имя ячейки в соответствии с индексами ее строки и столбца.|
| [`column_index_to_name(, column)`](/cells/python-net/ru/aspose.cells/cellshelper/column_index_to_name/#int) | Получает имя столбца в соответствии с индексом столбца.|
| [`column_name_to_index(, column_name)`](/cells/python-net/ru/aspose.cells/cellshelper/column_name_to_index/#str) | Получает индекс столбца в соответствии с именем столбца.|
| [`row_index_to_name(, row)`](/cells/python-net/ru/aspose.cells/cellshelper/row_index_to_name/#int) | Получает имя строки в соответствии с индексом строки.|
| [`row_name_to_index(, row_name)`](/cells/python-net/ru/aspose.cells/cellshelper/row_name_to_index/#str) | Получает индекс строки в соответствии с именем строки.|
| [`convert_r1c1_formula_to_a1(, r_1c1_formula, row, column)`](/cells/python-net/ru/aspose.cells/cellshelper/convert_r1c1_formula_to_a1/#str-int-int) | Преобразует формулу r1c1 ячейки в формулу A1.|
| [`convert_a1_formula_to_r1c1(, formula, row, column)`](/cells/python-net/ru/aspose.cells/cellshelper/convert_a1_formula_to_r1c1/#str-int-int) |Преобразует формулу A1 ячейки в формулу r1c1.|
| [`get_date_time_from_double(, double_value, date1904)`](/cells/python-net/ru/aspose.cells/cellshelper/get_date_time_from_double/#float-bool) | Преобразовать значение double в значение даты и времени.|
| [`get_double_from_date_time(, date_time, date1904)`](/cells/python-net/ru/aspose.cells/cellshelper/get_double_from_date_time/#datetime-bool) | Преобразовать дату и время в значение двойной точности.|
| [`get_used_colors(, workbook)`](/cells/python-net/ru/aspose.cells/cellshelper/get_used_colors/#aspose.cells.workbook) | Получает все использованные цвета в рабочей книге.|
| [`add_add_in_function(, function, min_count_of_parameters, max_count_of_parameters, paramers_type, function_value_type)`](/cells/python-net/ru/aspose.cells/cellshelper/add_add_in_function/#str-int-int-list-aspose.cells.parametertype) | Добавить дополнительную функцию.|
| [`merge_files(, files, cached_file, dest_file)`](/cells/python-net/ru/aspose.cells/cellshelper/merge_files/#list-str-str) | Объединяет несколько больших xls-файлов в один xls-файл.|
| [`get_cache_folder()`](/cells/python-net/ru/aspose.cells/cellshelper/get_cache_folder/#) | Получает папку для временных файлов, которые могут использоваться в качестве кэша данных.|
| [`set_cache_folder(, cache)`](/cells/python-net/ru/aspose.cells/cellshelper/set_cache_folder/#str) | Задает папку для временных файлов, которые могут использоваться в качестве кэша данных.|
| [`need_quote_in_formula(, sheet_name)`](/cells/python-net/ru/aspose.cells/cellshelper/need_quote_in_formula/#str) | Указывает, следует ли заключать имя листа в одинарные кавычки.|
| [`init_for_dot_net_core()`](/cells/python-net/ru/aspose.cells/cellshelper/init_for_dot_net_core/#) | Выполните инициализацию программы .NetCore.<br/> Мы рекомендуем вам сначала вызывать этот метод для всех инициализаций .NetCore.<br/>Например:<br/>CellsHelper.InitForDotNetCore();<br/> Рабочая книга wb = новая рабочая книга();|



###  Смотрите также
* модуль [`aspose.cells`](..)
