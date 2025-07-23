---
title: UnionRange класс
second_title: Aspose.Cells for Python via .NET API Ссылки
description:
type: docs
weight: 1510
url: /ru/aspose.cells/unionrange/
is_root: false
---
##  UnionRange класс
Представляет собой союзный ареал.



Тип UnionRange предоставляет следующие элементы:

###  Характеристики
| Свойство| Описание|
| :- | :- |
| [first_row](/cells/python-net/ru/aspose.cells/unionrange/first_row) | Получает индекс первой строки диапазона.|
| [first_column](/cells/python-net/ru/aspose.cells/unionrange/first_column) | Получает индекс первого столбца диапазона.|
| [row_count](/cells/python-net/ru/aspose.cells/unionrange/row_count) | Получает количество строк в диапазоне.|
| [column_count](/cells/python-net/ru/aspose.cells/unionrange/column_count) | Получает количество строк в диапазоне.|
| [value](/cells/python-net/ru/aspose.cells/unionrange/value) | Получает и задает значения диапазона.|
| [name](/cells/python-net/ru/aspose.cells/unionrange/name) | Получает или задает имя диапазона.|
| [refers_to](/cells/python-net/ru/aspose.cells/unionrange/refers_to) | Получает диапазон, на который ссылается.|
| [has_range](/cells/python-net/ru/aspose.cells/unionrange/has_range) | Указывает, есть ли у этого значения диапазон.|
| [hyperlinks](/cells/python-net/ru/aspose.cells/unionrange/hyperlinks) | Получает все гиперссылки в диапазоне.|
| [cell_count](/cells/python-net/ru/aspose.cells/unionrange/cell_count) | Получает все количество ячеек в диапазоне.|
| [range_count](/cells/python-net/ru/aspose.cells/unionrange/range_count) |Получает количество диапазонов.|
| [ranges](/cells/python-net/ru/aspose.cells/unionrange/ranges) | Получает все диапазоны объединения.|


###  Методы
| Метод| Описание|
| :- | :- |
| [`set_outline_borders(self, border_styles, border_colors)`](/cells/python-net/ru/aspose.cells/unionrange/set_outline_borders/#list-aspose.pydrawing.color[]) | Устанавливает границы линий вокруг диапазона ячеек.|
| [`set_outline_borders(self, border_style, border_color)`](/cells/python-net/ru/aspose.cells/unionrange/set_outline_borders/#aspose.cells.cellbordertype-aspose.pydrawing.color) | Устанавливает границы контура вокруг диапазона ячеек с одинаковым стилем и цветом границ.|
| [`intersect(self, range)`](/cells/python-net/ru/aspose.cells/unionrange/intersect/#str) | Пересекает другой диапазон.|
| [`intersect(self, union_range)`](/cells/python-net/ru/aspose.cells/unionrange/intersect/#aspose.cells.unionrange) | Пересекает другой диапазон.|
| [`intersect(self, ranges)`](/cells/python-net/ru/aspose.cells/unionrange/intersect/#list) | Пересекает другой диапазон.|
| [`union(self, range)`](/cells/python-net/ru/aspose.cells/unionrange/union/#str) | Союз другого диапазона.|
| [`union(self, union_range)`](/cells/python-net/ru/aspose.cells/unionrange/union/#aspose.cells.unionrange) | Союз другого диапазона.|
| [`union(self, ranges)`](/cells/python-net/ru/aspose.cells/unionrange/union/#list) | Объединение диапазонов.|
| [`merge(self)`](/cells/python-net/ru/aspose.cells/unionrange/merge/#) |Объединяет ряд ячеек в одну ячейку.|
| [`un_merge(self)`](/cells/python-net/ru/aspose.cells/unionrange/un_merge/#) | Разделяет объединенные ячейки данного диапазона.|
| [`put_value(self, string_value, is_converted, set_style)`](/cells/python-net/ru/aspose.cells/unionrange/put_value/#str-bool-bool) | Помещает значение в диапазон, при необходимости значение будет преобразовано в другой тип данных, а числовой формат ячейки будет сброшен.|
| [`set_style(self, style)`](/cells/python-net/ru/aspose.cells/unionrange/set_style/#aspose.cells.style) | Задает стиль диапазона.|
| [`apply_style(self, style, flag)`](/cells/python-net/ru/aspose.cells/unionrange/apply_style/#aspose.cells.style-aspose.cells.styleflag) | Применяет форматы для всего диапазона.|
| [`copy(self, range, options)`](/cells/python-net/ru/aspose.cells/unionrange/copy/#aspose.cells.unionrange-aspose.cells.pasteoptions) | Копирование диапазона с использованием опций специальной вставки.|



###  Смотрите также
* модуль [`aspose.cells`](..)
