---
title: AbstractFormulaChangeMonitor class
second_title: Aspose.Cells for Python via .NET API References
description: 
type: docs
weight: 40
url: /aspose.cells/abstractformulachangemonitor/
is_root: false
---

## AbstractFormulaChangeMonitor class

Monitor for user to track the change of formulas during certain operations.



The AbstractFormulaChangeMonitor type exposes the following members:

### Methods
| Method | Description |
| :- | :- |
| [`on_cell_formula_changed(self, sheet_index, row_index, column_index)`](/cells/python-net/aspose.cells/abstractformulachangemonitor/on_cell_formula_changed/#int-int-int) | The event that will be triggered when the formula in a cell is changed. |
| [`on_format_condition_formula_changed(self, fc)`](/cells/python-net/aspose.cells/abstractformulachangemonitor/on_format_condition_formula_changed/#aspose.cells.formatcondition) | The event that will be triggered when the formula of FormatCondition is changed. |



### Remarks 


For example, while deleting/inserting range of cells,
formulas of other cells may be changed because of the shift of references.
Please note, methods in the monitor may be invoked multiple times
for one object which contains the formula.

### See Also
* module [`aspose.cells`](..)
