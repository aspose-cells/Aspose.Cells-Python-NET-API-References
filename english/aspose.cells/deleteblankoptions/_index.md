---
title: DeleteBlankOptions class
second_title: Aspose.Cells for Python via .NET API References
description: 
type: docs
weight: 460
url: /aspose.cells/deleteblankoptions/
is_root: false
---

## DeleteBlankOptions class

Represents the setting of deleting blank cells/rows/columns.



**Inheritance:** [`DeleteBlankOptions`](/cells/python-net/aspose.cells/deleteblankoptions) → 
[`DeleteOptions`](/cells/python-net/aspose.cells/deleteoptions)



The DeleteBlankOptions type exposes the following members:

### Constructors
| Constructor | Description |
| :- | :- |
| [`__init__(self)`](/cells/python-net/aspose.cells/deleteblankoptions/__init__/#) | Constructs a new instance of DeleteBlankOptions |


### Properties
| Property | Description |
| :- | :- |
| [update_reference](/cells/python-net/aspose.cells/deleteblankoptions/update_reference) | Indicates if update references in other worksheets. |
| [formula_change_monitor](/cells/python-net/aspose.cells/deleteblankoptions/formula_change_monitor) | Gets/sets the monitor for tracking changes caused by the deletion. |
| [empty_string_as_blank](/cells/python-net/aspose.cells/deleteblankoptions/empty_string_as_blank) | Indicates whether one cell will be taken as blank when its value is an empty string.<br/>Default value is true. |
| [empty_formula_value_as_blank](/cells/python-net/aspose.cells/deleteblankoptions/empty_formula_value_as_blank) | Whether one cell will be taken as blank when it is a formula and the calculated result is null or empty string.<br/>Default value is false. |
| [drawings_as_blank](/cells/python-net/aspose.cells/deleteblankoptions/drawings_as_blank) | Indicates whether drawing related objects such as picture, shape, chart... will be taken as blank.<br/>Default value is true. |
| [merged_cells_shrink_type](/cells/python-net/aspose.cells/deleteblankoptions/merged_cells_shrink_type) | Indicates how to process merged cells when deleting blank rows/columns. |
| [start_index](/cells/python-net/aspose.cells/deleteblankoptions/start_index) | Specifies the start row/column index of the range to check and delete blank row/column. |
| [end_index](/cells/python-net/aspose.cells/deleteblankoptions/end_index) | Specifies the end row/column index(inclusive) of the range to check and delete blank rows/columns.<br/>Default value is -1 and -1 means the maximum range of all objects(cells, drawings, ...) that need to be checked. |



### See Also
* module [`aspose.cells`](..)
* class [`DeleteBlankOptions`](/cells/python-net/aspose.cells/deleteblankoptions)
* class [`DeleteOptions`](/cells/python-net/aspose.cells/deleteoptions)
