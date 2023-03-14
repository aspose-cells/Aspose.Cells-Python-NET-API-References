---
title: add метод
second_title: Aspose.Cells for Python via .NET API
description:
type: docs
weight: 20
url: /ru/aspose.cells/formatconditioncollection/add/
is_root: false
---
##  add(cell_area, type, operator_type, formula1, formula2) {#CellArea-FormatConditionType-OperatorType-str-str}
Добавляет условие форматирования и диапазон ячеек в FormatConditions.
FormatConditions может содержать до трех условных форматов.
Ссылки на другие листы в формулах условного форматирования не допускаются.


###  Возвращает

[0]: индекс объекта условия форматирования; [1] индекс ранга ячейки.


```python
def add(self, cell_area, type, operator_type, formula1, formula2):
    ...
```


| Параметр| Тип| Описание|
| :- | :- | :- |
| cell_area | [CellArea](/cells/python-net/ru/aspose.cells/cellarea) |Диапазон ячеек с условным форматированием.|
| type | [FormatConditionType](/cells/python-net/ru/aspose.cells/formatconditiontype) | Тип условного форматирования. Может быть одним из членов FormatConditionType.|
| operator_type | [OperatorType](/cells/python-net/ru/aspose.cells/operatortype) | Оператор сравнения. Он может быть одним из членов OperatorType.|
| formula1 | str | Значение или выражение, связанное с условным форматированием.|
| formula2 | str | Значение или выражение, связанное с условным форматированием|



###  Смотрите также
* модуль [aspose.cells](../../)
* класс [FormatConditionCollection](/cells/python-net/ru/aspose.cells/formatconditioncollection)
