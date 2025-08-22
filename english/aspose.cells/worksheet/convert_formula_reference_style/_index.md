---
title: convert_formula_reference_style method
second_title: Aspose.Cells for Python via .NET API References
description: 
type: docs
weight: 120
url: /aspose.cells/worksheet/convert_formula_reference_style/
is_root: false
---

## convert_formula_reference_style(self, formula, to_r1c1, base_cell_row, base_cell_column) {#System.String-bool-int-int}

Converts the formula reference style.


### Returns 


The converted formula.


```python

def convert_formula_reference_style(self, formula, to_r1c1, base_cell_row, base_cell_column):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| formula | System.String | The formula to be converted. |
| to_r1c1 | bool | Which reference style to convert the formula to.<br/>If the original formula is of A1 reference style,<br/>then this value should be true so the formula will be converted from A1 to R1C1 reference style;<br/>If the original formula is of R1C1 reference style,<br/>then this value should be false so the formula will be converted from R1C1 to A1 reference style; |
| base_cell_row | int | The row index of the base cell. |
| base_cell_column | int | The column index of the base cell. |



### See Also
* module [`aspose.cells`](../../)
* class [`Worksheet`](/cells/python-net/aspose.cells/worksheet)
