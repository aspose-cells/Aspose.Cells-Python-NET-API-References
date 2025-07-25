---
title: add metod
second_title: Aspose.Cells for Python via .NET API Referenser
description:
type: docs
weight: 20
url: /sv/aspose.cells/formatconditioncollection/add/
is_root: false
---
##  add(self, cell_area, type, operator_type, formula1, formula2) {#aspose.cells.CellArea-aspose.cells.FormatConditionType-aspose.cells.OperatorType-str-str}
Lägger till ett formateringsvillkor och påverkat cellnummer till FormatConditions
FormatConditions kan innehålla upp till tre villkorliga format.
Referenser till andra ark är inte tillåtna i formler för villkorsstyrd formatering.


###  Returnerar

[0]:Formateringsvillkor objektindex;[1] Påverkat cellintervallindex.


```python

def add(self, cell_area, type, operator_type, formula1, formula2):
    ...
```


| Parameter| Typ| Beskrivning|
| :- | :- | :- |
| cell_area | [`CellArea`](/cells/python-net/sv/aspose.cells/cellarea) |Villkorligt formaterat cellområde.|
| type | [`FormatConditionType`](/cells/python-net/sv/aspose.cells/formatconditiontype) | Typ av villkorsstyrd formatering. Den kan vara en av medlemmarna i FormatConditionType.|
| operator_type | [`OperatorType`](/cells/python-net/sv/aspose.cells/operatortype) | Jämförelseoperatorn. Den kan vara en av medlemmarna i OperatorType.|
| formula1 | str | Värdet eller uttrycket som är associerat med villkorsstyrd formatering.|
| formula2 | str | Värdet eller uttrycket som är associerat med villkorsstyrd formatering|



###  Se även
* modul [`aspose.cells`](../../)
* klass [`FormatConditionCollection`](/cells/python-net/sv/aspose.cells/formatconditioncollection)
