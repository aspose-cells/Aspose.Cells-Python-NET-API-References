---
title: PivotFilterCollection класс
second_title: Aspose.Cells for Python via .NET API Ссылки
description:
type: docs
weight: 150
url: /ru/aspose.cells.pivot/pivotfiltercollection/
is_root: false
---
##  PivotFilterCollection класс
Представляет коллекцию всех объектов PivotFilter.



Тип PivotFilterCollection предоставляет следующие элементы:

###  Характеристики
| Свойство| Описание|
| :- | :- |
| [capacity](/cells/python-net/ru/aspose.cells.pivot/pivotfiltercollection/capacity) | Возвращает или задает количество элементов, которые может содержать список массива.|


###  Методы
| Метод| Описание|
| :- | :- |
| [`copy_to(self, array)`](/cells/python-net/ru/aspose.cells.pivot/pivotfiltercollection/copy_to/#list) |Копирует весь список массивов в совместимый одномерный список массивов, начиная с начала целевого списка массивов.|
| [`copy_to(self, index, array, array_index, count)`](/cells/python-net/ru/aspose.cells.pivot/pivotfiltercollection/copy_to/#int-list-int-int) | Копирует диапазон элементов из списка массивов в совместимый список одномерных массивов, начиная с указанного индекса целевого списка массивов.|
| [`index_of(self, item, index)`](/cells/python-net/ru/aspose.cells.pivot/pivotfiltercollection/index_of/#aspose.cells.pivot.pivotfilter-int) | Выполняет поиск указанного объекта и возвращает индекс (начиная с нуля) первого вхождения в диапазоне элементов списка массива, который простирается от указанного индекса до последнего элемента.|
| [`index_of(self, item, index, count)`](/cells/python-net/ru/aspose.cells.pivot/pivotfiltercollection/index_of/#aspose.cells.pivot.pivotfilter-int-int) | Выполняет поиск указанного объекта и возвращает отсчитываемый от нуля индекс первого вхождения в диапазоне элементов списка массива, который начинается с указанного индекса и содержит указанное количество элементов.|
| [`last_index_of(self, item)`](/cells/python-net/ru/aspose.cells.pivot/pivotfiltercollection/last_index_of/#aspose.cells.pivot.pivotfilter) | Выполняет поиск указанного объекта и возвращает нулевой индекс последнего вхождения во всем списке массива.|
| [`last_index_of(self, item, index)`](/cells/python-net/ru/aspose.cells.pivot/pivotfiltercollection/last_index_of/#aspose.cells.pivot.pivotfilter-int) |Выполняет поиск указанного объекта и возвращает отсчитываемый от нуля индекс последнего вхождения в диапазоне элементов списка массива, который простирается от первого элемента до указанного индекса.|
| [`last_index_of(self, item, index, count)`](/cells/python-net/ru/aspose.cells.pivot/pivotfiltercollection/last_index_of/#aspose.cells.pivot.pivotfilter-int-int) | Выполняет поиск указанного объекта и возвращает отсчитываемый от нуля индекс последнего вхождения в диапазоне элементов списка массива, который содержит указанное количество элементов и заканчивается на указанном индексе.|
| [`add(self, field_index, type)`](/cells/python-net/ru/aspose.cells.pivot/pivotfiltercollection/add/#int-aspose.cells.pivot.pivotfiltertype) | Добавляет объект PivotFilter к определенному типу|
| [`add_top_10_filter(self, base_field_index, value_field_index, type, is_top, item_count)`](/cells/python-net/ru/aspose.cells.pivot/pivotfiltercollection/add_top_10_filter/#int-int-aspose.cells.pivot.pivotfiltertype-bool-int) | Фильтрует по значениям поля сводных данных.|
| [`add_value_filter(self, base_field_index, value_field_index, type, value1, value2)`](/cells/python-net/ru/aspose.cells.pivot/pivotfiltercollection/add_value_filter/#int-int-aspose.cells.pivot.pivotfiltertype-float-float) | Фильтрует по значениям поля сводных данных.|
| [`add_label_filter(self, base_field_index, type, label1, label2)`](/cells/python-net/ru/aspose.cells.pivot/pivotfiltercollection/add_label_filter/#int-aspose.cells.pivot.pivotfiltertype-str-str) | Фильтрует по заголовкам поля сводной строки или столбца.|
| [`add_date_filter(self, base_field_index, type, date_time1, date_time2)`](/cells/python-net/ru/aspose.cells.pivot/pivotfiltercollection/add_date_filter/#int-aspose.cells.pivot.pivotfiltertype-datetime-datetime) | Фильтрует по настройке даты сводного поля строки или столбца.|
| [`clear_filter(self, field_index)`](/cells/python-net/ru/aspose.cells.pivot/pivotfiltercollection/clear_filter/#int) | Очистить PivotFilter из определенного PivotField|
| [`binary_search(self, item)`](/cells/python-net/ru/aspose.cells.pivot/pivotfiltercollection/binary_search/#aspose.cells.pivot.pivotfilter) | Выполняет поиск элемента во всем отсортированном списке массивов, используя компаратор по умолчанию, и возвращает индекс элемента, отсчитываемый от нуля.|



###  Смотрите также
* модуль [`aspose.cells.pivot`](..)
