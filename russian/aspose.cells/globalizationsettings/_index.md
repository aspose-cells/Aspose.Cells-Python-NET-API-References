---
title: GlobalizationSettings класс
second_title: Aspose.Cells for Python via .NET API Ссылки
description:
type: docs
weight: 740
url: /ru/aspose.cells/globalizationsettings/
is_root: false
---
##  GlobalizationSettings класс
Представляет настройки глобализации.



Тип GlobalizationSettings предоставляет следующие элементы:

###  Конструкторы
| Конструктор| Описание|
| :- | :- |
| [`__init__(self)`](/cells/python-net/ru/aspose.cells/globalizationsettings/__init__/#) | Создает новый экземпляр GlobalizationSettings|


###  Характеристики
| Свойство| Описание|
| :- | :- |
| [chart_settings](/cells/python-net/ru/aspose.cells/globalizationsettings/chart_settings) | Получает или задает параметры глобализации для Chart.|
| [pivot_settings](/cells/python-net/ru/aspose.cells/globalizationsettings/pivot_settings) | Получает или задает параметры глобализации для сводной таблицы.|
| [list_separator](/cells/python-net/ru/aspose.cells/globalizationsettings/list_separator) | Получает разделитель для списка, параметров функции и т. д.|
| [row_separator_of_formula_array](/cells/python-net/ru/aspose.cells/globalizationsettings/row_separator_of_formula_array) | Получает разделитель строк в массиве данных в формуле.|
| [column_separator_of_formula_array](/cells/python-net/ru/aspose.cells/globalizationsettings/column_separator_of_formula_array) |Возвращает разделитель для элементов в строках данных массива в формуле.|


###  Методы
| Метод| Описание|
| :- | :- |
| [`get_pivot_total_name(self)`](/cells/python-net/ru/aspose.cells/globalizationsettings/get_pivot_total_name/#) | Получает имя метки «Итого» в сводной таблице.<br/> Вам необходимо переопределить этот метод, если сводная таблица содержит два или более сводных полей в области данных.|
| [`get_pivot_grand_total_name(self)`](/cells/python-net/ru/aspose.cells/globalizationsettings/get_pivot_grand_total_name/#) | Получает имя метки «Общий итог» в сводной таблице.|
| [`get_multiple_items_name(self)`](/cells/python-net/ru/aspose.cells/globalizationsettings/get_multiple_items_name/#) | Получает имя метки «(Несколько элементов)» в сводной таблице.|
| [`get_all_name(self)`](/cells/python-net/ru/aspose.cells/globalizationsettings/get_all_name/#) | Получает имя метки «(Все)» в сводной таблице.|
| [`get_protection_name_of_pivot_table(self)`](/cells/python-net/ru/aspose.cells/globalizationsettings/get_protection_name_of_pivot_table/#) | Получает имя защиты в сводной таблице.|
| [`get_column_labels_of_pivot_table(self)`](/cells/python-net/ru/aspose.cells/globalizationsettings/get_column_labels_of_pivot_table/#) | Получает имя метки «Метки столбцов» в сводной таблице.|
| [`get_row_labels_name_of_pivot_table(self)`](/cells/python-net/ru/aspose.cells/globalizationsettings/get_row_labels_name_of_pivot_table/#) | Получает имя метки «Метки строк» в сводной таблице.|
| [`get_empty_data_name(self)`](/cells/python-net/ru/aspose.cells/globalizationsettings/get_empty_data_name/#) | Получает имя метки «(пусто)» в сводной таблице.|
| [`get_data_field_header_name_of_pivot_table(self)`](/cells/python-net/ru/aspose.cells/globalizationsettings/get_data_field_header_name_of_pivot_table/#) | Возвращает имя заголовка поля области значений в сводной таблице.|
| [`get_sub_total_name(self, sub_total_type)`](/cells/python-net/ru/aspose.cells/globalizationsettings/get_sub_total_name/#aspose.cells.pivot.pivotfieldsubtotaltype) | Получает имя типа [`PivotFieldSubtotalType`](/cells/python-net/ru/aspose.cells.pivot/pivotfieldsubtotaltype) в сводной таблице.|
| [`get_total_name(self, function_type)`](/cells/python-net/ru/aspose.cells/globalizationsettings/get_total_name/#aspose.cells.consolidationfunction) | Получает полное имя функции.|
| [`get_grand_total_name(self, function_type)`](/cells/python-net/ru/aspose.cells/globalizationsettings/get_grand_total_name/#aspose.cells.consolidationfunction) | Получает общее имя функции.|
| [`get_default_sheet_name(self)`](/cells/python-net/ru/aspose.cells/globalizationsettings/get_default_sheet_name/#) |Получает имя листа по умолчанию для автоматического добавления листа.<br/> По умолчанию — «Лист».|
| [`get_table_row_type_of_headers(self)`](/cells/python-net/ru/aspose.cells/globalizationsettings/get_table_row_type_of_headers/#) | Возвращает имя типа строк таблицы, состоящее из заголовка таблицы.<br/> По умолчанию используется «Заголовки», поэтому в формуле «#Заголовки» представляет заголовок таблицы.|
| [`get_table_row_type_of_data(self)`](/cells/python-net/ru/aspose.cells/globalizationsettings/get_table_row_type_of_data/#) | Возвращает имя типа строк таблицы, состоящей из области данных указанной таблицы.<br/> По умолчанию используется значение «Данные», поэтому в формуле «#Данные» представляет область данных таблицы.|
| [`get_table_row_type_of_all(self)`](/cells/python-net/ru/aspose.cells/globalizationsettings/get_table_row_type_of_all/#) | Возвращает имя типа строк таблицы, состоящей из всех строк в указанной таблице.<br/> По умолчанию установлено значение «Все», поэтому в формуле «#Все» представляет все строки в указанной таблице.|
| [`get_table_row_type_of_totals(self)`](/cells/python-net/ru/aspose.cells/globalizationsettings/get_table_row_type_of_totals/#) | Возвращает имя типа строк таблицы, состоящее из общей строки указанной таблицы.<br/> По умолчанию установлено значение «Итого», поэтому в формуле «#Итого» представляет собой общую строку указанной таблицы.|
| [`get_table_row_type_of_current(self)`](/cells/python-net/ru/aspose.cells/globalizationsettings/get_table_row_type_of_current/#) | Возвращает имя типа строк таблицы, состоящей из текущей строки в указанной таблице.<br/>По умолчанию используется значение «Эта строка», поэтому в формуле «#Эта строка» представляет текущую строку в указанной таблице.|
| [`get_error_value_string(self, err)`](/cells/python-net/ru/aspose.cells/globalizationsettings/get_error_value_string/#str) | Получает отображаемое строковое значение для значения ошибки ячейки.|
| [`get_boolean_value_string(self, bv)`](/cells/python-net/ru/aspose.cells/globalizationsettings/get_boolean_value_string/#bool) | Получает отображаемое строковое значение для логического значения ячейки.|
| [`get_local_function_name(self, standard_name)`](/cells/python-net/ru/aspose.cells/globalizationsettings/get_local_function_name/#str) | Получает имя функции, зависящее от локали, в соответствии с заданным стандартным именем функции.|
| [`get_standard_function_name(self, local_name)`](/cells/python-net/ru/aspose.cells/globalizationsettings/get_standard_function_name/#str) | Получает стандартное имя функции в соответствии с заданным именем функции, зависящим от локали.|
| [`get_local_built_in_name(self, standard_name)`](/cells/python-net/ru/aspose.cells/globalizationsettings/get_local_built_in_name/#str) | Получает зависящий от локали текст для встроенного Имени в соответствии с заданным стандартным текстом.|
| [`get_standard_built_in_name(self, local_name)`](/cells/python-net/ru/aspose.cells/globalizationsettings/get_standard_built_in_name/#str) | Получает стандартный текст встроенного Имени в соответствии с заданным зависящим от локали текстом.|
| [`get_standard_header_footer_font_style_name(self, localfont_style_name)`](/cells/python-net/ru/aspose.cells/globalizationsettings/get_standard_header_footer_font_style_name/#str) | Получает стандартное название стиля английского шрифта (обычный, полужирный, курсив) для верхнего/нижнего колонтитула в соответствии с заданным названием стиля шрифта локали.|
| [`get_comment_title_name(self, type)`](/cells/python-net/ru/aspose.cells/globalizationsettings/get_comment_title_name/#aspose.cells.rendering.commenttitletype) | Получает название заголовка комментария, зависящее от локали, в соответствии с типом заголовка комментария.|
| [`compare(self, v1, v2, ignore_case)`](/cells/python-net/ru/aspose.cells/globalizationsettings/compare/#str-str-bool) | Сравнивает два строковых значения в соответствии с определенными правилами сортировки.|



###  Смотрите также
* модуль [`aspose.cells`](..)
* класс [`PivotFieldSubtotalType`](/cells/python-net/ru/aspose.cells.pivot/pivotfieldsubtotaltype)
