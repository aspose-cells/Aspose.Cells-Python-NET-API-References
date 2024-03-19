---
title: SettableGlobalizationSettings класс
second_title: Aspose.Cells for Python via .NET API Рекомендации
description:
type: docs
weight: 1420
url: /ru/aspose.cells/settableglobalizationsettings/
is_root: false
---
##  SettableGlobalizationSettings класс
Реализация GlobalizationSettings, которая позволяет пользователю устанавливать/изменять предварительно определенные тексты.



**Наследование:** [`SettableGlobalizationSettings`](/cells/python-net/aspose.cells/settableglobalizationsettings) → 
[`GlobalizationSettings`](/cells/python-net/ru/aspose.cells/globalizationsettings)



Тип SettableGlobalizationSettings предоставляет следующие элементы:

###  Конструкторы
| Конструктор| Описание|
| :- | :- |
| [__init__](/cells/python-net/ru/aspose.cells/settableglobalizationsettings/__init__/#) | Создает новый экземпляр SettableGlobalizationSettings.|


###  Характеристики
| Свойство| Описание|
| :- | :- |
| [chart_settings](/cells/python-net/ru/aspose.cells/settableglobalizationsettings/chart_settings) | Получает или задает параметры глобализации для Chart.|
| [pivot_settings](/cells/python-net/ru/aspose.cells/settableglobalizationsettings/pivot_settings) | Получает или задает параметры глобализации для сводной таблицы.|
| [list_separator](/cells/python-net/ru/aspose.cells/settableglobalizationsettings/list_separator) | Получает разделитель для списка, параметров функции и т. д.|
| [row_separator_of_formula_array](/cells/python-net/ru/aspose.cells/settableglobalizationsettings/row_separator_of_formula_array) | Получает разделитель строк данных массива в формуле.|
| [column_separator_of_formula_array](/cells/python-net/ru/aspose.cells/settableglobalizationsettings/column_separator_of_formula_array) | Получает разделитель для элементов данных строки массива в формуле.|


###  Методы
| Метод| Описание|
| :- | :- |
| [get_pivot_total_name](/cells/python-net/ru/aspose.cells/settableglobalizationsettings/get_pivot_total_name/#) | Получает имя метки «Итого» в сводной таблице.<br/> Вам необходимо переопределить этот метод, если сводная таблица содержит два или более сводных поля в области данных.|
| [get_pivot_grand_total_name](/cells/python-net/ru/aspose.cells/settableglobalizationsettings/get_pivot_grand_total_name/#) | Получает имя метки «Общий итог» в сводной таблице.|
| [get_multiple_items_name](/cells/python-net/ru/aspose.cells/settableglobalizationsettings/get_multiple_items_name/#) | Получает имя метки «(Несколько элементов)» в сводной таблице.|
| [get_all_name](/cells/python-net/ru/aspose.cells/settableglobalizationsettings/get_all_name/#) | Получает имя метки «(Все)» в сводной таблице.|
| [get_protection_name_of_pivot_table](/cells/python-net/ru/aspose.cells/settableglobalizationsettings/get_protection_name_of_pivot_table/#) | Получает имя защиты в сводной таблице.|
| [get_column_labels_of_pivot_table](/cells/python-net/ru/aspose.cells/settableglobalizationsettings/get_column_labels_of_pivot_table/#) | Получает имя метки «Метки столбцов» в сводной таблице.|
| [get_row_labels_name_of_pivot_table](/cells/python-net/ru/aspose.cells/settableglobalizationsettings/get_row_labels_name_of_pivot_table/#) | Получает имя метки «Метки строк» в сводной таблице.|
| [get_empty_data_name](/cells/python-net/ru/aspose.cells/settableglobalizationsettings/get_empty_data_name/#) |Получает имя метки «(пусто)» в сводной таблице.|
| [get_data_field_header_name_of_pivot_table](/cells/python-net/ru/aspose.cells/settableglobalizationsettings/get_data_field_header_name_of_pivot_table/#) | Получает имя заголовка поля области значений в сводной таблице.|
| [get_sub_total_name](/cells/python-net/ru/aspose.cells/settableglobalizationsettings/get_sub_total_name/#aspose.cells.pivot.PivotFieldSubtotalType) | Получает имя типа [`PivotFieldSubtotalType`](/cells/python-net/ru/aspose.cells.pivot/pivotfieldsubtotaltype) в сводной таблице.|
| [get_total_name](/cells/python-net/ru/aspose.cells/settableglobalizationsettings/get_total_name/#aspose.cells.ConsolidationFunction) | Получает полное имя конкретной функции.|
| [get_grand_total_name](/cells/python-net/ru/aspose.cells/settableglobalizationsettings/get_grand_total_name/#aspose.cells.ConsolidationFunction) | Получает общее имя функции.|
| [get_default_sheet_name](/cells/python-net/ru/aspose.cells/settableglobalizationsettings/get_default_sheet_name/#) | Получает имя листа по умолчанию для автоматического добавления листа.<br/> По умолчанию — «Лист».|
| [get_table_row_type_of_headers](/cells/python-net/ru/aspose.cells/settableglobalizationsettings/get_table_row_type_of_headers/#) | Получает имя типа строк таблицы, состоящее из заголовка таблицы.<br/> По умолчанию используется «Заголовки», поэтому в формуле «#Заголовки» представляют собой заголовок таблицы.|
| [get_table_row_type_of_data](/cells/python-net/ru/aspose.cells/settableglobalizationsettings/get_table_row_type_of_data/#) | Получает имя типа строк таблицы, состоящее из области данных указанной таблицы.<br/> По умолчанию используется «Данные», поэтому в формуле «#Данные» представляет область данных таблицы.|
| [get_table_row_type_of_all](/cells/python-net/ru/aspose.cells/settableglobalizationsettings/get_table_row_type_of_all/#) | Получает имя типа строк таблицы, состоящее из всех строк в указанной таблице.|
| [get_table_row_type_of_totals](/cells/python-net/ru/aspose.cells/settableglobalizationsettings/get_table_row_type_of_totals/#) |Получает имя типа строк таблицы, состоящее из общей строки указанной таблицы.|
| [get_table_row_type_of_current](/cells/python-net/ru/aspose.cells/settableglobalizationsettings/get_table_row_type_of_current/#) | Получает имя типа строк таблицы, состоящее из текущей строки в указанной таблице.|
| [get_error_value_string](/cells/python-net/ru/aspose.cells/settableglobalizationsettings/get_error_value_string/#str) | Получает значение отображаемой строки для значения ошибки ячейки.|
| [get_boolean_value_string](/cells/python-net/ru/aspose.cells/settableglobalizationsettings/get_boolean_value_string/#bool) | Получает отображаемое строковое значение для логического значения ячейки.|
| [get_local_function_name](/cells/python-net/ru/aspose.cells/settableglobalizationsettings/get_local_function_name/#str) | Получает имя функции, зависящей от языкового стандарта, в соответствии с заданным стандартным именем функции.|
| [get_standard_function_name](/cells/python-net/ru/aspose.cells/settableglobalizationsettings/get_standard_function_name/#str) | Получает стандартное имя функции в соответствии с именем функции, зависящей от языкового стандарта.|
| [get_local_built_in_name](/cells/python-net/ru/aspose.cells/settableglobalizationsettings/get_local_built_in_name/#str) | Получает текст, зависящий от локали, для встроенного имени в соответствии с заданным стандартным текстом.|
| [get_standard_built_in_name](/cells/python-net/ru/aspose.cells/settableglobalizationsettings/get_standard_built_in_name/#str) | Получает стандартный текст встроенного имени в соответствии с текстом, зависящим от языкового стандарта.|
| [get_standard_header_footer_font_style_name](/cells/python-net/ru/aspose.cells/settableglobalizationsettings/get_standard_header_footer_font_style_name/#str) |Получает стандартное имя стиля английского шрифта (обычный, полужирный, курсив) для верхнего или нижнего колонтитула в соответствии с именем стиля шрифта данного языкового стандарта.|
| [get_comment_title_name](/cells/python-net/ru/aspose.cells/settableglobalizationsettings/get_comment_title_name/#aspose.cells.rendering.CommentTitleType) | Получает имя заголовка комментария, зависящее от языкового стандарта, в соответствии с типом заголовка комментария.|
| [compare](/cells/python-net/ru/aspose.cells/settableglobalizationsettings/compare/#str-str-bool) | Сравнивает два строковых значения в соответствии с определенными правилами сортировки.|
| [set_total_name](/cells/python-net/ru/aspose.cells/settableglobalizationsettings/set_total_name/#aspose.cells.ConsolidationFunction-str) | Устанавливает общее имя конкретной функции.|
| [set_grand_total_name](/cells/python-net/ru/aspose.cells/settableglobalizationsettings/set_grand_total_name/#aspose.cells.ConsolidationFunction-str) | Устанавливает общее имя конкретной функции.|
| [set_table_row_type_of_headers](/cells/python-net/ru/aspose.cells/settableglobalizationsettings/set_table_row_type_of_headers/#str) | Задает имя типа строк таблицы, состоящее из заголовка таблицы.|
| [set_table_row_type_of_data](/cells/python-net/ru/aspose.cells/settableglobalizationsettings/set_table_row_type_of_data/#str) | Устанавливает имя типа строк таблицы, состоящее из области данных указанной таблицы.|
| [set_table_row_type_of_all](/cells/python-net/ru/aspose.cells/settableglobalizationsettings/set_table_row_type_of_all/#str) | Задает имя типа строк таблицы, состоящее из всех строк в указанной таблице.|
| [set_table_row_type_of_totals](/cells/python-net/ru/aspose.cells/settableglobalizationsettings/set_table_row_type_of_totals/#str) | Задает имя типа строк таблицы, состоящее из общей строки указанной таблицы.|
| [set_table_row_type_of_current](/cells/python-net/ru/aspose.cells/settableglobalizationsettings/set_table_row_type_of_current/#str) | Устанавливает имя типа строк таблицы, состоящее из текущей строки в указанной таблице.|
| [set_boolean_value_string](/cells/python-net/ru/aspose.cells/settableglobalizationsettings/set_boolean_value_string/#bool-str) | Устанавливает отображаемое строковое значение для логического значения ячейки.|
| [set_local_function_name](/cells/python-net/ru/aspose.cells/settableglobalizationsettings/set_local_function_name/#str-str-bool) | Устанавливает имя функции, зависящее от локали, соответствующее заданному стандартному имени функции.|
| [set_standard_function_name](/cells/python-net/ru/aspose.cells/settableglobalizationsettings/set_standard_function_name/#str-str-bool) | Устанавливает имя функции, зависящее от локали, в соответствии с заданным стандартным именем функции.|
| [set_local_built_in_name](/cells/python-net/ru/aspose.cells/settableglobalizationsettings/set_local_built_in_name/#str-str-bool) |Устанавливает текст, зависящий от локали, для встроенного имени с заданным стандартным текстом имени.|
| [set_standard_built_in_name](/cells/python-net/ru/aspose.cells/settableglobalizationsettings/set_standard_built_in_name/#str-str-bool) | Устанавливает имя функции, зависящее от локали, в соответствии с заданным стандартным именем функции.|
| [set_list_separator](/cells/python-net/ru/aspose.cells/settableglobalizationsettings/set_list_separator/#char) | Устанавливает разделитель для списка, параметров функции и т. д.|
| [set_row_separator_of_formula_array](/cells/python-net/ru/aspose.cells/settableglobalizationsettings/set_row_separator_of_formula_array/#char) | Устанавливает разделитель строк в данных массива в формуле.|
| [set_column_separator_of_formula_array](/cells/python-net/ru/aspose.cells/settableglobalizationsettings/set_column_separator_of_formula_array/#char) | Устанавливает разделитель для элементов данных строки массива в формуле.|
| [set_standard_header_footer_font_style_name](/cells/python-net/ru/aspose.cells/settableglobalizationsettings/set_standard_header_footer_font_style_name/#str-str) | Устанавливает имя функции, зависящее от локали, в соответствии с заданным стандартным именем функции.|
| [set_comment_title_name](/cells/python-net/ru/aspose.cells/settableglobalizationsettings/set_comment_title_name/#aspose.cells.rendering.CommentTitleType-str) | Получает имя заголовка комментария, зависящее от языкового стандарта, в соответствии с типом заголовка комментария.|



###  Смотрите также
* модуль [`aspose.cells`](..)
* класс [`GlobalizationSettings`](/cells/python-net/ru/aspose.cells/globalizationsettings)
* класс [`PivotFieldSubtotalType`](/cells/python-net/ru/aspose.cells.pivot/pivotfieldsubtotaltype)
* класс [`SettableGlobalizationSettings`](/cells/python-net/ru/aspose.cells/settableglobalizationsettings)
