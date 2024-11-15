﻿---
title: CellValueFormatStrategy enumeration
second_title: Aspose.Cells for Python via .NET API References
description: 
type: docs
weight: 1970
url: /aspose.cells/cellvalueformatstrategy/
is_root: false
---

## CellValueFormatStrategy enumeration

Specifies how to apply style for the value of the cell.



The CellValueFormatStrategy type exposes the following members:

### Fields
| Field | Description |
| :- | :- |
| NONE | Not formatted. |
| CELL_STYLE | Only formatted with the cell's original style. |
| DISPLAY_STYLE | Formatted with the cell's displayed style. |
| DISPLAY_STRING | Gets the displayed string shown in ms excel.<br/>The main difference from [`CellValueFormatStrategy.DISPLAY_STYLE`](/cells/python-net/aspose.cells/cellvalueformatstrategy#DISPLAY_STYLE) is this option also considers the effect of column width.<br/>If the column width is too small to show the formatted string completely,<br/>"#" may be shown, just like what ms excel does. |



### See Also
* module [`aspose.cells`](..)
