---
title: PivotItem класс
second_title: Aspose.Cells for Python via .NET API Ссылки
description:
type: docs
weight: 180
url: /ru/aspose.cells.pivot/pivotitem/
is_root: false
---
##  PivotItem класс
Представляет элемент в отчете PivotField.



Тип PivotItem предоставляет следующие элементы:

###  Характеристики
| Свойство| Описание|
| :- | :- |
| [is_hidden](/cells/python-net/ru/aspose.cells.pivot/pivotitem/is_hidden) | Возвращает и задает, скрыт ли элемент вращения.|
| [position](/cells/python-net/ru/aspose.cells.pivot/pivotitem/position) | Указание индекса позиции во всех элементах PivotItem, а не в элементах PivotItem одного и того же родительского узла.|
| [position_in_same_parent_node](/cells/python-net/ru/aspose.cells.pivot/pivotitem/position_in_same_parent_node) | Указание индекса позиции в PivotItems под тем же родительским узлом.|
| [is_hide_detail](/cells/python-net/ru/aspose.cells.pivot/pivotitem/is_hide_detail) | Возвращает и задает, скрывает ли элемент сводки детали.|
| [is_detail_hidden](/cells/python-net/ru/aspose.cells.pivot/pivotitem/is_detail_hidden) |Возвращает и задает, скрыты ли сведения об этом элементе сводки.|
| [is_calculated_item](/cells/python-net/ru/aspose.cells.pivot/pivotitem/is_calculated_item) | Указывает, является ли данный элемент сводки вычисляемым элементом формулы.|
| [is_formula](/cells/python-net/ru/aspose.cells.pivot/pivotitem/is_formula) | Указывает, является ли данный элемент сводки вычисляемым элементом формулы.|
| [is_missing](/cells/python-net/ru/aspose.cells.pivot/pivotitem/is_missing) | Указывает, удален ли элемент из источника данных.|
| [value](/cells/python-net/ru/aspose.cells.pivot/pivotitem/value) | Получает значение опорного элемента|
| [name](/cells/python-net/ru/aspose.cells.pivot/pivotitem/name) | Получает имя опорного элемента.|
| [index](/cells/python-net/ru/aspose.cells.pivot/pivotitem/index) | Получает индекс элемента сводки в поле кэша.|


###  Методы
| Метод| Описание|
| :- | :- |
| [`move(self, count, is_same_parent)`](/cells/python-net/ru/aspose.cells.pivot/pivotitem/move/#int-bool) | Перемещает элемент вверх или вниз|
| [`get_formula(self)`](/cells/python-net/ru/aspose.cells.pivot/pivotitem/get_formula/#) | Получает формулу этого вычисляемого элемента.<br/> Работает только в том случае, если этот элемент является расчетным.|
| [`get_string_value(self)`](/cells/python-net/ru/aspose.cells.pivot/pivotitem/get_string_value/#) | Получает строковое значение опорного элемента<br/> Если значение равно нулю, будет возвращено ""|
| [`get_double_value(self)`](/cells/python-net/ru/aspose.cells.pivot/pivotitem/get_double_value/#) | Получает двойное значение опорного элемента<br/> Если значение равно нулю или не является числом, будет возвращено 0.|
| [`get_date_time_value(self)`](/cells/python-net/ru/aspose.cells.pivot/pivotitem/get_date_time_value/#) | Получает значение даты и времени элемента сводной таблицы.<br/> Если значение равно null, будет возвращено DateTime.MinValue|



###  Смотрите также
* модуль [`aspose.cells.pivot`](..)
