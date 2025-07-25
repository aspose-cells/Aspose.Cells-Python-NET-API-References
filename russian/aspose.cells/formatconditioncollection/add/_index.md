---
title: add метод
second_title: Aspose.Cells for Python via .NET API Ссылки
description:
type: docs
weight: 20
url: /ru/aspose.cells/formatconditioncollection/add/
is_root: false
---
##  add(self, cell_area, type, operator_type, formula1, formula2) {#aspose.cells.CellArea-aspose.cells.FormatConditionType-aspose.cells.OperatorType-str-str}
Добавляет условие форматирования и диапазон ячеек, на которые оно распространяется, в FormatConditions.
FormatConditions может содержать до трех условных форматов.
В формулах условного форматирования не допускаются ссылки на другие листы.


###  Возврат

[0]:Индекс объекта условия форматирования;[1] Индекс ранга затронутой ячейки.


```python

def add(self, cell_area, type, operator_type, formula1, formula2):
    ...
```


| Параметр| Тип| Описание|
| :- | :- | :- |
| cell_area | [`CellArea`](/cells/python-net/ru/aspose.cells/cellarea) |Условно отформатированный диапазон ячеек.|
| type | [`FormatConditionType`](/cells/python-net/ru/aspose.cells/formatconditiontype) | Тип условного форматирования. Может быть одним из членов FormatConditionType.|
| operator_type | [`OperatorType`](/cells/python-net/ru/aspose.cells/operatortype) | Оператор сравнения. Может быть одним из членов OperatorType.|
| formula1 | str | Значение или выражение, связанное с условным форматированием.|
| formula2 | str | Значение или выражение, связанное с условным форматированием|



###  Смотрите также
* модуль [`aspose.cells`](../../)
* класс [`FormatConditionCollection`](/cells/python-net/ru/aspose.cells/formatconditioncollection)
