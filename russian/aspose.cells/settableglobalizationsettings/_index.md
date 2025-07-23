---
title: SettableGlobalizationSettings класс
second_title: Aspose.Cells for Python via .NET API Ссылки
description:
type: docs
weight: 1310
url: /ru/aspose.cells/settableglobalizationsettings/
is_root: false
---
##  SettableGlobalizationSettings класс
Реализация GlobalizationSettings, которая позволяет пользователю задавать/изменять предопределенные тексты.



**Наследование:** [`SettableGlobalizationSettings`](/cells/python-net/aspose.cells/settableglobalizationsettings) → 
[`GlobalizationSettings`](/cells/python-net/ru/aspose.cells/globalizationsettings)



Тип SettableGlobalizationSettings предоставляет следующие элементы:

###  Конструкторы
| Конструктор| Описание|
| :- | :- |
| [`__init__(self)`](/cells/python-net/ru/aspose.cells/settableglobalizationsettings/__init__/#) | Создает новый экземпляр SettableGlobalizationSettings|


###  Характеристики
| Свойство| Описание|
| :- | :- |
| [chart_settings](/cells/python-net/ru/aspose.cells/settableglobalizationsettings/chart_settings) | Получает или задает параметры глобализации для Chart.|
| [pivot_settings](/cells/python-net/ru/aspose.cells/settableglobalizationsettings/pivot_settings) | Получает или задает параметры глобализации для сводной таблицы.|
| [list_separator](/cells/python-net/ru/aspose.cells/settableglobalizationsettings/list_separator) | Получает разделитель для списка, параметров функции и т. д.|
| [row_separator_of_formula_array](/cells/python-net/ru/aspose.cells/settableglobalizationsettings/row_separator_of_formula_array) | Получает разделитель строк в массиве данных в формуле.|
| [column_separator_of_formula_array](/cells/python-net/ru/aspose.cells/settableglobalizationsettings/column_separator_of_formula_array) |Возвращает разделитель для элементов в строках данных массива в формуле.|


###  Методы
| Метод| Описание|
| :- | :- |
| [`get_pivot_total_name(self)`](/cells/python-net/ru/aspose.cells/settableglobalizationsettings/get_pivot_total_name/#) | Получает имя метки «Итого» в сводной таблице.<br/> Вам необходимо переопределить этот метод, если сводная таблица содержит два или более сводных полей в области данных.|
| [`get_pivot_grand_total_name(self)`](/cells/python-net/ru/aspose.cells/settableglobalizationsettings/get_pivot_grand_total_name/#) | Получает имя метки «Общий итог» в сводной таблице.|
| [`get_multiple_items_name(self)`](/cells/python-net/ru/aspose.cells/settableglobalizationsettings/get_multiple_items_name/#) | Получает имя метки «(Несколько элементов)» в сводной таблице.|
| [`get_all_name(self)`](/cells/python-net/ru/aspose.cells/settableglobalizationsettings/get_all_name/#) | Получает имя метки «(Все)» в сводной таблице.|
| [`get_protection_name_of_pivot_table(self)`](/cells/python-net/ru/aspose.cells/settableglobalizationsettings/get_protection_name_of_pivot_table/#) | Получает имя защиты в сводной таблице.|
| [`get_column_labels_of_pivot_table(self)`](/cells/python-net/ru/aspose.cells/settableglobalizationsettings/get_column_labels_of_pivot_table/#) | Получает имя метки «Метки столбцов» в сводной таблице.|
| [`get_row_labels_name_of_pivot_table(self)`](/cells/python-net/ru/aspose.cells/settableglobalizationsettings/get_row_labels_name_of_pivot_table/#) | Получает имя метки «Метки строк» в сводной таблице.|
| [`get_empty_data_name(self)`](/cells/python-net/ru/aspose.cells/settableglobalizationsettings/get_empty_data_name/#) | Получает имя метки «(пусто)» в сводной таблице.|
| [`get_data_field_header_name_of_pivot_table(self)`](/cells/python-net/ru/aspose.cells/settableglobalizationsettings/get_data_field_header_name_of_pivot_table/#) | Возвращает имя заголовка поля области значений в сводной таблице.|
| [`get_sub_total_name(self, sub_total_type)`](/cells/python-net/ru/aspose.cells/settableglobalizationsettings/get_sub_total_name/#aspose.cells.pivot.pivotfieldsubtotaltype) | Получает имя типа [`PivotFieldSubtotalType`](/cells/python-net/ru/aspose.cells.pivot/pivotfieldsubtotaltype) в сводной таблице.|
| [`get_total_name(self, function_type)`](/cells/python-net/ru/aspose.cells/settableglobalizationsettings/get_total_name/#aspose.cells.consolidationfunction) | Получает полное имя определенной функции.|
| [`get_grand_total_name(self, function_type)`](/cells/python-net/ru/aspose.cells/settableglobalizationsettings/get_grand_total_name/#aspose.cells.consolidationfunction) | Получает общее имя функции.|
| [`get_default_sheet_name(self)`](/cells/python-net/ru/aspose.cells/settableglobalizationsettings/get_default_sheet_name/#) |Получает имя листа по умолчанию для автоматического добавления листа.<br/> По умолчанию — «Лист».|
| [`get_table_row_type_of_headers(self)`](/cells/python-net/ru/aspose.cells/settableglobalizationsettings/get_table_row_type_of_headers/#) | Возвращает имя типа строк таблицы, состоящее из заголовка таблицы.<br/> По умолчанию используется «Заголовки», поэтому в формуле «#Заголовки» представляет заголовок таблицы.|
| [`get_table_row_type_of_data(self)`](/cells/python-net/ru/aspose.cells/settableglobalizationsettings/get_table_row_type_of_data/#) | Возвращает имя типа строк таблицы, состоящей из области данных указанной таблицы.<br/> По умолчанию используется значение «Данные», поэтому в формуле «#Данные» представляет область данных таблицы.|
| [`get_table_row_type_of_all(self)`](/cells/python-net/ru/aspose.cells/settableglobalizationsettings/get_table_row_type_of_all/#) | Возвращает имя типа строк таблицы, состоящей из всех строк в указанной таблице.|
| [`get_table_row_type_of_totals(self)`](/cells/python-net/ru/aspose.cells/settableglobalizationsettings/get_table_row_type_of_totals/#) | Возвращает имя типа строк таблицы, состоящее из общей строки указанной таблицы.|
| [`get_table_row_type_of_current(self)`](/cells/python-net/ru/aspose.cells/settableglobalizationsettings/get_table_row_type_of_current/#) |Возвращает имя типа строк таблицы, состоящей из текущей строки в указанной таблице.|
| [`get_error_value_string(self, err)`](/cells/python-net/ru/aspose.cells/settableglobalizationsettings/get_error_value_string/#str) | Получает отображаемое строковое значение для значения ошибки ячейки.|
| [`get_boolean_value_string(self, bv)`](/cells/python-net/ru/aspose.cells/settableglobalizationsettings/get_boolean_value_string/#bool) | Получает отображаемое строковое значение для логического значения ячейки.|
| [`get_local_function_name(self, standard_name)`](/cells/python-net/ru/aspose.cells/settableglobalizationsettings/get_local_function_name/#str) | Получает имя функции, зависящее от локали, в соответствии с заданным стандартным именем функции.|
| [`get_standard_function_name(self, local_name)`](/cells/python-net/ru/aspose.cells/settableglobalizationsettings/get_standard_function_name/#str) | Получает стандартное имя функции в соответствии с заданным именем функции, зависящим от локали.|
| [`get_local_built_in_name(self, standard_name)`](/cells/python-net/ru/aspose.cells/settableglobalizationsettings/get_local_built_in_name/#str) | Получает зависящий от локали текст для встроенного Имени в соответствии с заданным стандартным текстом.|
| [`get_standard_built_in_name(self, local_name)`](/cells/python-net/ru/aspose.cells/settableglobalizationsettings/get_standard_built_in_name/#str) | Получает стандартный текст встроенного Имени в соответствии с заданным зависящим от локали текстом.|
| [`get_standard_header_footer_font_style_name(self, localfont_style_name)`](/cells/python-net/ru/aspose.cells/settableglobalizationsettings/get_standard_header_footer_font_style_name/#str) | Получает стандартное название стиля английского шрифта (обычный, полужирный, курсив) для верхнего/нижнего колонтитула в соответствии с заданным названием стиля шрифта локали.|
| [`get_comment_title_name(self, type)`](/cells/python-net/ru/aspose.cells/settableglobalizationsettings/get_comment_title_name/#aspose.cells.rendering.commenttitletype) | Получает название заголовка комментария, зависящее от локали, в соответствии с типом заголовка комментария.|
| [`compare(self, v1, v2, ignore_case)`](/cells/python-net/ru/aspose.cells/settableglobalizationsettings/compare/#str-str-bool) | Сравнивает два строковых значения в соответствии с определенными правилами сортировки.|
| [`set_total_name(self, function_type, name)`](/cells/python-net/ru/aspose.cells/settableglobalizationsettings/set_total_name/#aspose.cells.consolidationfunction-str) | Задает общее имя конкретной функции.|
| [`set_grand_total_name(self, function_type, name)`](/cells/python-net/ru/aspose.cells/settableglobalizationsettings/set_grand_total_name/#aspose.cells.consolidationfunction-str) | Задает общее итоговое имя определенной функции.|
| [`set_table_row_type_of_headers(self, name)`](/cells/python-net/ru/aspose.cells/settableglobalizationsettings/set_table_row_type_of_headers/#str) | Задает имя типа строк таблицы, состоящее из заголовка таблицы.|
| [`set_table_row_type_of_data(self, name)`](/cells/python-net/ru/aspose.cells/settableglobalizationsettings/set_table_row_type_of_data/#str) | Задает имя типа строк таблицы, состоящей из области данных указанной таблицы.|
| [`set_table_row_type_of_all(self, name)`](/cells/python-net/ru/aspose.cells/settableglobalizationsettings/set_table_row_type_of_all/#str) | Задает имя типа строк таблицы, состоящей из всех строк в указанной таблице.|
| [`set_table_row_type_of_totals(self, name)`](/cells/python-net/ru/aspose.cells/settableglobalizationsettings/set_table_row_type_of_totals/#str) | Задает имя типа строк таблицы, состоящее из общей строки указанной таблицы.|
| [`set_table_row_type_of_current(self, name)`](/cells/python-net/ru/aspose.cells/settableglobalizationsettings/set_table_row_type_of_current/#str) | Задает имя типа строк таблицы, состоящей из текущей строки в указанной таблице.|
| [`set_boolean_value_string(self, bv, name)`](/cells/python-net/ru/aspose.cells/settableglobalizationsettings/set_boolean_value_string/#bool-str) | Задает отображаемое строковое значение для логического значения ячейки.|
| [`set_local_function_name(self, standard_name, local_name, bidirectional)`](/cells/python-net/ru/aspose.cells/settableglobalizationsettings/set_local_function_name/#str-str-bool) | Устанавливает имя функции, зависящее от локали, соответствующее заданному стандартному имени функции.|
| [`set_standard_function_name(self, local_name, standard_name, bidirectional)`](/cells/python-net/ru/aspose.cells/settableglobalizationsettings/set_standard_function_name/#str-str-bool) | Устанавливает имя функции, зависящее от локали, в соответствии с заданным стандартным именем функции.|
| [`set_local_built_in_name(self, standard_name, local_name, bidirectional)`](/cells/python-net/ru/aspose.cells/settableglobalizationsettings/set_local_built_in_name/#str-str-bool) | Устанавливает зависящий от локали текст для встроенного имени с заданным стандартным текстом имени.|
| [`set_standard_built_in_name(self, local_name, standard_name, bidirectional)`](/cells/python-net/ru/aspose.cells/settableglobalizationsettings/set_standard_built_in_name/#str-str-bool) | Устанавливает имя функции, зависящее от локали, в соответствии с заданным стандартным именем функции.|
| [`set_list_separator(self, c)`](/cells/python-net/ru/aspose.cells/settableglobalizationsettings/set_list_separator/#char) |Устанавливает разделитель для списка, параметров функции и т. д.|
| [`set_row_separator_of_formula_array(self, c)`](/cells/python-net/ru/aspose.cells/settableglobalizationsettings/set_row_separator_of_formula_array/#char) | Устанавливает разделитель строк в массиве данных в формуле.|
| [`set_column_separator_of_formula_array(self, c)`](/cells/python-net/ru/aspose.cells/settableglobalizationsettings/set_column_separator_of_formula_array/#char) | Устанавливает разделитель для элементов в строках данных массива в формуле.|
| [`set_standard_header_footer_font_style_name(self, localfont_style_name, standard_name)`](/cells/python-net/ru/aspose.cells/settableglobalizationsettings/set_standard_header_footer_font_style_name/#str-str) | Устанавливает имя функции, зависящее от локали, в соответствии с заданным стандартным именем функции.|
| [`set_comment_title_name(self, type, name)`](/cells/python-net/ru/aspose.cells/settableglobalizationsettings/set_comment_title_name/#aspose.cells.rendering.commenttitletype-str) | Получает название заголовка комментария, зависящее от локали, в соответствии с типом заголовка комментария.|



###  Смотрите также
* модуль [`aspose.cells`](..)
* класс [`GlobalizationSettings`](/cells/python-net/ru/aspose.cells/globalizationsettings)
* класс [`PivotFieldSubtotalType`](/cells/python-net/ru/aspose.cells.pivot/pivotfieldsubtotaltype)
* класс [`SettableGlobalizationSettings`](/cells/python-net/ru/aspose.cells/settableglobalizationsettings)
