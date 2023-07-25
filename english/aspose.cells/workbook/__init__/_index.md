﻿---
title: Workbook constructor
second_title: Aspose.Cells for Python via .NET API References
description: 
type: docs
weight: 10
url: /aspose.cells/workbook/__init__/
is_root: false
---

## __init__ {#}

Initializes a new instance of the [`Workbook`](/cells/python-net/aspose.cells/workbook) class.



```python
def __init__(self):
    ...
```


### Remarks

The default file format type is Xlsx. If you want to create other types of files, please use Workbook(FileFormatType).
### Example 


The following code shows how to use the Workbook constructor to create and initialize a new instance of the class.

```python
from aspose.cells import Workbook

workbook = Workbook()

```


## __init__ {#aspose.cells.FileFormatType}

Initializes a new instance of the [`Workbook`](/cells/python-net/aspose.cells/workbook) class.



```python
def __init__(self, file_format_type):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| file_format_type | [`FileFormatType`](/cells/python-net/aspose.cells/fileformattype) | The new file format. |
### Remarks

The default file format type is Excel97To2003.
### Example 


The following code shows how to use the Workbook constructor to create and initialize a new instance of the class with various file format type.

```python
from aspose.cells import FileFormatType, Workbook

workbook = Workbook(FileFormatType.XLSX)

```


## __init__ {#str}

Initializes a new instance of the [`Workbook`](/cells/python-net/aspose.cells/workbook) class and open a file.



```python
def __init__(self, file):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| file | str | The file name. |


## __init__ {#io.RawIOBase}

Initializes a new instance of the [`Workbook`](/cells/python-net/aspose.cells/workbook) class and open a stream.



```python
def __init__(self, stream):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| stream | io.RawIOBase | The stream. |


## __init__ {#str-aspose.cells.LoadOptions}

Initializes a new instance of the [`Workbook`](/cells/python-net/aspose.cells/workbook) class and open a file.



```python
def __init__(self, file, load_options):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| file | str | The file name. |
| load_options | [`LoadOptions`](/cells/python-net/aspose.cells/loadoptions) | The load options |


## __init__ {#io.RawIOBase-aspose.cells.LoadOptions}

Initializes a new instance of the [`Workbook`](/cells/python-net/aspose.cells/workbook) class and open stream.



```python
def __init__(self, stream, load_options):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| stream | io.RawIOBase | The stream. |
| load_options | [`LoadOptions`](/cells/python-net/aspose.cells/loadoptions) | The load options |



### See Also
* module [`aspose.cells`](../../)
* class [`Workbook`](/cells/python-net/aspose.cells/workbook)
