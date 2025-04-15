---
title: process method
second_title: Aspose.Cells for Python via .NET API References
description: 
type: docs
weight: 20
url: /aspose.cells.lowcode/spreadsheetlocker/process/
is_root: false
---

## process(, load_options, save_options, provider) {#aspose.cells.lowcode.LowCodeLoadOptions-aspose.cells.lowcode.LowCodeSaveOptions-aspose.cells.lowcode.AbstractLowCodeProtectionProvider}

Locks spreadsheet file with specified settings.



```python

@staticmethod
def process(load_options, save_options, provider):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| load_options | [`LowCodeLoadOptions`](/cells/python-net/aspose.cells.lowcode/lowcodeloadoptions) | Options for input and loading |
| save_options | [`LowCodeSaveOptions`](/cells/python-net/aspose.cells.lowcode/lowcodesaveoptions) | Options for output and saving |
| provider | [`AbstractLowCodeProtectionProvider`](/cells/python-net/aspose.cells.lowcode/abstractlowcodeprotectionprovider) | Implementation to provide protections settings |


## process(, template_file, result_file, open_password, write_password) {#str-str-str-str}

Locks spreadsheet file with specified settings.



```python

@staticmethod
def process(template_file, result_file, open_password, write_password):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| template_file | str | The template file to be locked |
| result_file | str | The resultant file |
| open_password | str | Password for file encryption |
| write_password | str | Password for protection of modifying spreadsheet |


## process(, load_options, save_options, open_password, write_password) {#aspose.cells.lowcode.LowCodeLoadOptions-aspose.cells.lowcode.LowCodeSaveOptions-str-str}

Locks spreadsheet file with specified settings.



```python

@staticmethod
def process(load_options, save_options, open_password, write_password):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| load_options | [`LowCodeLoadOptions`](/cells/python-net/aspose.cells.lowcode/lowcodeloadoptions) | Options for input and loading |
| save_options | [`LowCodeSaveOptions`](/cells/python-net/aspose.cells.lowcode/lowcodesaveoptions) | Options for output and saving |
| open_password | str | Password for file encryption |
| write_password | str | Password for protection of modifying spreadsheet |


## process(, load_options, save_options, open_password, write_password, workbook_password, workbook_type) {#aspose.cells.lowcode.LowCodeLoadOptions-aspose.cells.lowcode.LowCodeSaveOptions-str-str-str-aspose.cells.ProtectionType}

Locks spreadsheet file with specified settings.



```python

@staticmethod
def process(load_options, save_options, open_password, write_password, workbook_password, workbook_type):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| load_options | [`LowCodeLoadOptions`](/cells/python-net/aspose.cells.lowcode/lowcodeloadoptions) | Options for input and loading |
| save_options | [`LowCodeSaveOptions`](/cells/python-net/aspose.cells.lowcode/lowcodesaveoptions) | Options for output and saving |
| open_password | str | Password for file encryption |
| write_password | str | Password for protection of modifying spreadsheet |
| workbook_password | str | Password for protection of the workbook |
| workbook_type | [`ProtectionType`](/cells/python-net/aspose.cells/protectiontype) | Protection type to protect the workbook |



### See Also
* module [`aspose.cells.lowcode`](../../)
* class [`SpreadsheetLocker`](/cells/python-net/aspose.cells.lowcode/spreadsheetlocker)
