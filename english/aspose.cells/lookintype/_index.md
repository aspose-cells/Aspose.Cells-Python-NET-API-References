---
title: LookInType enumeration
second_title: Aspose.Cells for Python via .NET API References
description: 
type: docs
weight: 2450
url: /aspose.cells/lookintype/
is_root: false
---

## LookInType enumeration

Represents look in type.



The LookInType type exposes the following members:

### Fields
| Field | Description |
| :- | :- |
| FORMULAS | Finds the searched object from formula([`Cell.formula`](/cells/python-net/aspose.cells/cell#formula)) if the cell is formula,<br/>otherwise finds from cell's original value(same with [`LookInType.ORIGINAL_VALUES`](/cells/python-net/aspose.cells/lookintype#ORIGINAL_VALUES)). |
| VALUES | Finds object from cell's original value([`Cell.value`](/cells/python-net/aspose.cells/cell#value))<br/>and formatted value([`Cell.string_value`](/cells/python-net/aspose.cells/cell#string_value)). |
| VALUES_EXCLUDE_FORMULA_CELL | Ignores cells that are formula. For those cells that are not formula,<br/>it is same with [`LookInType.VALUES`](/cells/python-net/aspose.cells/lookintype#VALUES). |
| COMMENTS | Finds object from cell's comment only. Ignores those cells that have no comment. |
| ONLY_FORMULAS | Ignores cells that are not formula. For those cells that are formula,<br/>finds the searched object from formula([`Cell.formula`](/cells/python-net/aspose.cells/cell#formula)). |
| ORIGINAL_VALUES | Find object from cell's original value only. |
| FORMATTED_VALUES | Find object from cell's formatted value([`Cell.string_value`](/cells/python-net/aspose.cells/cell#string_value)) only. |



### See Also
* module [`aspose.cells`](..)
