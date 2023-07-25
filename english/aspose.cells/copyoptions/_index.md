﻿---
title: CopyOptions class
second_title: Aspose.Cells for Python via .NET API References
description: 
type: docs
weight: 360
url: /aspose.cells/copyoptions/
is_root: false
---

## CopyOptions class

Represents the copy options.



The CopyOptions type exposes the following members:

### Constructors
| Constructor | Description |
| :- | :- |
| [__init__](/cells/python-net/aspose.cells/copyoptions/__init__/#) | CopyOptions constructor. |


### Properties
| Property | Description |
| :- | :- |
| [keep_macros](/cells/python-net/aspose.cells/copyoptions/keep_macros) | Indicates whether keeping macros; |
| [extend_to_adjacent_range](/cells/python-net/aspose.cells/copyoptions/extend_to_adjacent_range) | Indicates whether extend ranges when copying the range to adjacent range. |
| [copy_names](/cells/python-net/aspose.cells/copyoptions/copy_names) | Indicates whether copying the names. |
| [copy_invalid_formulas_as_values](/cells/python-net/aspose.cells/copyoptions/copy_invalid_formulas_as_values) | If the formula is not valid for the dest destination, only copy values. |
| [column_character_width](/cells/python-net/aspose.cells/copyoptions/column_character_width) | Indicates whether copying column width in unit of characters. |
| [refer_to_sheet_with_same_name](/cells/python-net/aspose.cells/copyoptions/refer_to_sheet_with_same_name) | In ms excel, when copying formulas which refer to other worksheets while copying a worksheet to another one,<br/>the copied formulas should refer to source workbook.<br/>However, for some situations user may need the copied formulas refer to worksheets with the same name<br/>in the same workbook, such as when those worksheets have been copied before this copy operation,<br/>then this property should be kept as true. |
| [refer_to_destination_sheet](/cells/python-net/aspose.cells/copyoptions/refer_to_destination_sheet) | When copying the range in the same file and the chart refers to the source sheet,<br/>False means the copied chart's data source will not be changed.<br/>True means the copied chart's data source refers to the destination sheet. |



### See Also
* module [`aspose.cells`](..)
