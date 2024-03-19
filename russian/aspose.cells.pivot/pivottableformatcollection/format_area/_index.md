---
title: format_area метод
second_title: Aspose.Cells for Python via .NET API Рекомендации
description:
type: docs
weight: 50
url: /ru/aspose.cells.pivot/pivottableformatcollection/format_area/
is_root: false
---
##  format_area {#aspose.cells.pivot.PivotFieldType-int-aspose.cells.pivot.PivotFieldSubtotalType-aspose.cells.pivot.PivotTableSelectionType-bool-bool-aspose.cells.Style}
Форматирует выбранную область.


###  Возврат




```python
def format_area(self, axis_type, field_position, subtotal_type, selection_type, is_grand_row, is_grand_column, style):
    ...
```


| Параметр| Тип| Описание|
| :- | :- | :- |
| axis_type | [`PivotFieldType`](/cells/python-net/ru/aspose.cells.pivot/pivotfieldtype) | Область сводной таблицы, к которой применяется это правило.|
| field_position | int | Положение поля внутри оси, к которой применяется это правило.|
| subtotal_type | [`PivotFieldSubtotalType`](/cells/python-net/ru/aspose.cells.pivot/pivotfieldsubtotaltype) | Тип фильтра промежуточного итога сводного поля|
| selection_type | [`PivotTableSelectionType`](/cells/python-net/ru/aspose.cells.pivot/pivottableselectiontype) | Указывает, как выбирать данные.|
| is_grand_row | bool | Указывает, выбираются ли строки общего итога.|
| is_grand_column | bool | Указывает, выбираются ли столбцы общего итога.|
| style | [`Style`](/cells/python-net/ru/aspose.cells/style) | Стиль, применяемый к области сводной таблицы.|



###  Смотрите также
* модуль [`aspose.cells.pivot`](../../)
* класс [`PivotTableFormatCollection`](/cells/python-net/ru/aspose.cells.pivot/pivottableformatcollection)
