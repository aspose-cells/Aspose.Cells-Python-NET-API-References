---
title: DeleteBlankOptions class
second_title: Aspose.Cells for Python via .NET API References
description: 
type: docs
weight: 500
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
| [__init__](/cells/python-net/aspose.cells/deleteblankoptions/__init__/#) | Constructs a new instance of DeleteBlankOptions |


### Properties
| Property | Description |
| :- | :- |
| [update_reference](/cells/python-net/aspose.cells/deleteblankoptions/update_reference) | Indicates if update references in other worksheets. |
| [empty_string_as_blank](/cells/python-net/aspose.cells/deleteblankoptions/empty_string_as_blank) | Whether one cell will be taken as blank when its value is empty string.<br/>Default value is true. |
| [empty_formula_value_as_blank](/cells/python-net/aspose.cells/deleteblankoptions/empty_formula_value_as_blank) | Whether one cell will be taken as blank when it is formula and the calculated result is null or empty string.<br/>Default value is false. |
| [drawings_as_blank](/cells/python-net/aspose.cells/deleteblankoptions/drawings_as_blank) | Whether drawing related objects such as picture, shape, chart... will be taken as blank.<br/>Default value is true. |
| [merged_cells_shrink_type](/cells/python-net/aspose.cells/deleteblankoptions/merged_cells_shrink_type) | Indicates how to process merged cells when deleting blank rows/columns.<br/><br/>For [`MergedCellsShrinkType.KEEP_HEADER_ONLY`](/cells/python-net/aspose.cells/mergedcellsshrinktype#KEEP_HEADER_ONLY), all cells in it will be taken as blank except the non-blank top-left cell. It is the default value of this property.<br/><br/>For [`MergedCellsShrinkType.NONE`](/cells/python-net/aspose.cells/mergedcellsshrinktype#NONE), all cells in it will be taken as non-blank.<br/><br/>For [`MergedCellsShrinkType.SHRINK_TO_FIT`](/cells/python-net/aspose.cells/mergedcellsshrinktype#SHRINK_TO_FIT), all cells outside the content display area will be taken as blank. |
| [start_index](/cells/python-net/aspose.cells/deleteblankoptions/start_index) | Specifies the start row/column index of the range to check and delete blank rows/columns. |
| [end_index](/cells/python-net/aspose.cells/deleteblankoptions/end_index) | Specifies the end row/column index(inclusive) of the range to check and delete blank rows/columns.<br/>Default value is -1 and -1 means the maximum range of all objects(cells, drawings, ...) that need to be checked. |



### See Also
* module [`aspose.cells`](..)
* class [`DeleteBlankOptions`](/cells/python-net/aspose.cells/deleteblankoptions)
* class [`DeleteOptions`](/cells/python-net/aspose.cells/deleteoptions)
