---
title: NaryEquationNode класс
second_title: Aspose.Cells for Python via .NET API Ссылки
description:
type: docs
weight: 150
url: /ru/aspose.cells.drawing.equations/naryequationnode/
is_root: false
---
##  NaryEquationNode класс
Этот класс определяет уравнение n-арного оператора, состоящее из n-арного оператора, основания (или операнда) и необязательных верхней и нижней границ.



**Наследование:** [`NaryEquationNode`](/cells/python-net/ru/aspose.cells.drawing.equations/naryequationnode)



Тип NaryEquationNode предоставляет следующие элементы:

###  Характеристики
| Свойство| Описание|
| :- | :- |
| [type](/cells/python-net/ru/aspose.cells.drawing.equations/naryequationnode/type) |  |
| [start_index](/cells/python-net/ru/aspose.cells.drawing.equations/naryequationnode/start_index) |  |
| [length](/cells/python-net/ru/aspose.cells.drawing.equations/naryequationnode/length) |  |
| [font](/cells/python-net/ru/aspose.cells.drawing.equations/naryequationnode/font) |  |
| [text_options](/cells/python-net/ru/aspose.cells.drawing.equations/naryequationnode/text_options) |  |
| [equation_type](/cells/python-net/ru/aspose.cells.drawing.equations/naryequationnode/equation_type) |  |
| [is_hide_subscript](/cells/python-net/ru/aspose.cells.drawing.equations/naryequationnode/is_hide_subscript) | Отображать ли нижнюю границу|
| [is_hide_superscript](/cells/python-net/ru/aspose.cells.drawing.equations/naryequationnode/is_hide_superscript) | Отображать ли верхнюю границу|
| [limit_location](/cells/python-net/ru/aspose.cells.drawing.equations/naryequationnode/limit_location) | Этот атрибут определяет расположение пределов в n-арных операторах. Пределы могут быть либо центрированы выше и ниже n-арного оператора, либо расположены справа от него.|
| [nary_operator](/cells/python-net/ru/aspose.cells.drawing.equations/naryequationnode/nary_operator) | n-арный оператор, например "∑".<br/>Настоятельно рекомендуется использовать атрибут NaryOperatorType для задания n-арного оператора.<br/> Используйте эту настройку свойства, если вы не можете найти нужный вам символ в известном типе.|
| [nary_operator_type](/cells/python-net/ru/aspose.cells.drawing.equations/naryequationnode/nary_operator_type) | n-арный оператор, например "∑"|
| [nary_grow](/cells/python-net/ru/aspose.cells.drawing.equations/naryequationnode/nary_grow) | Этот атрибут определяет свойство роста n-арных операторов на уровне документа. При отключении n-арные операторы, такие как интегралы и суммирования, не увеличиваются в размерах до высоты операнда. При включении n-арный оператор увеличивается вертикально до высоты операнда.|


###  Методы
| Метод| Описание|
| :- | :- |
| [`add_child(self, equation_type)`](/cells/python-net/ru/aspose.cells.drawing.equations/naryequationnode/add_child/#aspose.cells.drawing.equations.equationnodetype) |  |
| [`add_child(self, node)`](/cells/python-net/ru/aspose.cells.drawing.equations/naryequationnode/add_child/#equationnode) |  |
| [`remove_child(self, node)`](/cells/python-net/ru/aspose.cells.drawing.equations/naryequationnode/remove_child/#equationnode) |  |
| [`remove_child(self, index)`](/cells/python-net/ru/aspose.cells.drawing.equations/naryequationnode/remove_child/#int) |  |
| [`set_word_art_style(self, style)`](/cells/python-net/ru/aspose.cells.drawing.equations/naryequationnode/set_word_art_style/#aspose.cells.drawing.presetwordartstyle) |  |
| [`to_la_te_x(self)`](/cells/python-net/ru/aspose.cells.drawing.equations/naryequationnode/to_la_te_x/#) |  |
| [`to_math_ml(self)`](/cells/python-net/ru/aspose.cells.drawing.equations/naryequationnode/to_math_ml/#) |  |
| [`insert_child(self, index, equation_type)`](/cells/python-net/ru/aspose.cells.drawing.equations/naryequationnode/insert_child/#int-aspose.cells.drawing.equations.equationnodetype) |  |
| [`insert_after(self, equation_type)`](/cells/python-net/ru/aspose.cells.drawing.equations/naryequationnode/insert_after/#aspose.cells.drawing.equations.equationnodetype) |  |
| [`insert_before(self, equation_type)`](/cells/python-net/ru/aspose.cells.drawing.equations/naryequationnode/insert_before/#aspose.cells.drawing.equations.equationnodetype) |  |
| [`get_child(self, index)`](/cells/python-net/ru/aspose.cells.drawing.equations/naryequationnode/get_child/#int) |  |
| [`remove(self)`](/cells/python-net/ru/aspose.cells.drawing.equations/naryequationnode/remove/#) |  |
| [`remove_all_children(self)`](/cells/python-net/ru/aspose.cells.drawing.equations/naryequationnode/remove_all_children/#) |  |
| [`create_node(, equation_type, workbook, parent)`](/cells/python-net/ru/aspose.cells.drawing.equations/naryequationnode/create_node/#aspose.cells.drawing.equations.equationnodetype-aspose.cells.workbook-equationnode) |  |



###  Смотрите также
* модуль [`aspose.cells.drawing.equations`](..)
* класс [`NaryEquationNode`](/cells/python-net/ru/aspose.cells.drawing.equations/naryequationnode)
