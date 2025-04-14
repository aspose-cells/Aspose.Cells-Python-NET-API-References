---
title: AbstractLowCodeSaveOptionsProvider class
second_title: Aspose.Cells for Python via .NET API References
description: 
type: docs
weight: 30
url: /aspose.cells.lowcode/abstractlowcodesaveoptionsprovider/
is_root: false
---

## AbstractLowCodeSaveOptionsProvider class

Implementation to provide multiple save options for processes
that require multiple outputs. For example,
[`SpreadsheetSplitter`](/cells/python-net/aspose.cells.lowcode/spreadsheetsplitter) feature requires multiple destinations
to save the split files.



The AbstractLowCodeSaveOptionsProvider type exposes the following members:

### Methods
| Method | Description |
| :- | :- |
| [`get_save_options(self, part)`](/cells/python-net/aspose.cells.lowcode/abstractlowcodesaveoptionsprovider/get_save_options/#aspose.cells.lowcode.splitpartinfo) | Gets the save options from which to get the output settings for currently split part.<br/>Returning null denotes to skip given part. |
| [`finish(self, part)`](/cells/python-net/aspose.cells.lowcode/abstractlowcodesaveoptionsprovider/finish/#aspose.cells.lowcode.lowcodesaveoptions) | Releases resources after processing currently split part. |



### See Also
* module [`aspose.cells.lowcode`](..)
* class [`SpreadsheetSplitter`](/cells/python-net/aspose.cells.lowcode/spreadsheetsplitter)
