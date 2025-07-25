---
title: PivotArea класс
second_title: Aspose.Cells for Python via .NET API Ссылки
description:
type: docs
weight: 20
url: /ru/aspose.cells.pivot/pivotarea/
is_root: false
---
##  PivotArea класс
Представляет выбранную область сводной таблицы.



Тип PivotArea предоставляет следующие элементы:

###  Конструкторы
| Конструктор| Описание|
| :- | :- |
| [`__init__(self, table)`](/cells/python-net/ru/aspose.cells.pivot/pivotarea/__init__/#aspose.cells.pivot.pivottable) | Представляет выбранную область сводной таблицы.|


###  Характеристики
| Свойство| Описание|
| :- | :- |
| [filters](/cells/python-net/ru/aspose.cells.pivot/pivotarea/filters) | Получает все фильтры для этой PivotArea.|
| [only_data](/cells/python-net/ru/aspose.cells.pivot/pivotarea/only_data) |Указывает, отображаются ли только значения данных (в области данных представления) для элемента<br/> выбраны и не включают метки элементов.|
| [only_label](/cells/python-net/ru/aspose.cells.pivot/pivotarea/only_label) | Указывает, выбраны ли только метки данных для выбранного элемента.|
| [is_row_grand_included](/cells/python-net/ru/aspose.cells.pivot/pivotarea/is_row_grand_included) | Указывает, включен ли общий итог строки.|
| [is_column_grand_included](/cells/python-net/ru/aspose.cells.pivot/pivotarea/is_column_grand_included) | Указывает, включен ли общий итог столбца.|
| [axis_type](/cells/python-net/ru/aspose.cells.pivot/pivotarea/axis_type) | Возвращает и задает область сводной таблицы, к которой применяется это правило.|
| [rule_type](/cells/python-net/ru/aspose.cells.pivot/pivotarea/rule_type) | Получает и задает тип правила выбора.|
| [is_outline](/cells/python-net/ru/aspose.cells.pivot/pivotarea/is_outline) | Указывает, относится ли правило к области, находящейся в режиме контура.|


###  Методы
| Метод| Описание|
| :- | :- |
| [`select_field(self, axis_type, field_name)`](/cells/python-net/ru/aspose.cells.pivot/pivotarea/select_field/#aspose.cells.pivot.pivotfieldtype-str) | Выберите поле в регионе в качестве области.|
| [`select_field(self, axis_type, field)`](/cells/python-net/ru/aspose.cells.pivot/pivotarea/select_field/#aspose.cells.pivot.pivotfieldtype-aspose.cells.pivot.pivotfield) | Выберите поле в регионе в качестве области.|
| [`select(self, axis_type, field_position, selection_type)`](/cells/python-net/ru/aspose.cells.pivot/pivotarea/select/#aspose.cells.pivot.pivotfieldtype-int-aspose.cells.pivot.pivottableselectiontype) | Выберите область с фильтрами.|
| [`get_cell_areas(self)`](/cells/python-net/ru/aspose.cells.pivot/pivotarea/get_cell_areas/#) | Получает области ячеек этой опорной области.|



###  Смотрите также
* модуль [`aspose.cells.pivot`](..)
