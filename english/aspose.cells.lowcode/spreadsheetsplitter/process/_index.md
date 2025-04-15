---
title: process method
second_title: Aspose.Cells for Python via .NET API References
description: 
type: docs
weight: 20
url: /aspose.cells.lowcode/spreadsheetsplitter/process/
is_root: false
---

## process(, options) {#aspose.cells.lowcode.LowCodeSplitOptions}

Splits spreadsheet file into multiple parts.



```python

@staticmethod
def process(options):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| options | [`LowCodeSplitOptions`](/cells/python-net/aspose.cells.lowcode/lowcodesplitoptions) | Options for splitting spreadsheet |


## process(, template_file, result_file) {#str-str}

Splits given template file into multiple parts.



```python

@staticmethod
def process(template_file, result_file):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| template_file | str | The template file to be split |
| result_file | str | The resultant file(name pattern) |
### Remarks

The output files will be build from the specified resultant file by
appending sequence number of the sheet and split part.
For example, if the specified output file is Split.xlsx, then the generated
files will be Split_0_0.xlsx, Split_0_1.xlsx, ..., Split_1_0.xlsx, ...


### See Also
* module [`aspose.cells.lowcode`](../../)
* class [`SpreadsheetSplitter`](/cells/python-net/aspose.cells.lowcode/spreadsheetsplitter)
