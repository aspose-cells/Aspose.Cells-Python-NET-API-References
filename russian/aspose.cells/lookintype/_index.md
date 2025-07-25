---
title: LookInType перечисление
second_title: Aspose.Cells for Python via .NET API Ссылки
description:
type: docs
weight: 2270
url: /ru/aspose.cells/lookintype/
is_root: false
---
##  LookInType перечисление
Представляет собой образ по типу.



Тип LookInType предоставляет следующие элементы:

###  Поля
| Поле| Описание|
| :- | :- |
| FORMULAS | Находит искомый объект из формулы ([`Cell.formula`](/cells/python-net/ru/aspose.cells/cell#formula)), если ячейка является формулой,<br/>в противном случае находит из исходного значения ячейки (то же самое с [`LookInType.ORIGINAL_VALUES`](/cells/python-net/ru/aspose.cells/lookintype#ORIGINAL_VALUES)).|
| VALUES | Находит объект по исходному значению ячейки ([`Cell.value`](/cells/python-net/ru/aspose.cells/cell#value))<br/> и форматированное значение ([`Cell.string_value`](/cells/python-net/ru/aspose.cells/cell#string_value)).|
| VALUES_EXCLUDE_FORMULA_CELL | Игнорирует ячейки, содержащие формулы. Для ячеек, не содержащих формулы,<br/> то же самое с [`LookInType.VALUES`](/cells/python-net/ru/aspose.cells/lookintype#VALUES).|
| COMMENTS | Находит объекты только по комментариям к ячейке. Ячейки без комментариев игнорируются.|
| ONLY_FORMULAS | Игнорирует ячейки, не содержащие формул. Для ячеек, содержащих формулы,<br/> находит искомый объект по формуле ([`Cell.formula`](/cells/python-net/ru/aspose.cells/cell#formula)).|
| ORIGINAL_VALUES | Найти объект только по исходному значению ячейки.|
| FORMATTED_VALUES | Найти объект только по отформатированному значению ячейки ([`Cell.string_value`](/cells/python-net/ru/aspose.cells/cell#string_value)).|



###  Смотрите также
* модуль [`aspose.cells`](..)
