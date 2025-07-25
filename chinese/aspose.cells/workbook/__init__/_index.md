---
title: Workbook 施工人员
second_title: Aspose.Cells for Python via .NET API 参考文献
description:
type: docs
weight: 10
url: /zh/aspose.cells/workbook/__init__/
is_root: false
---
##  \_\_init\_\_（自身）{#}
初始化 [`Workbook`](/cells/python-net/zh/aspose.cells/workbook) 类的新实例。



```python

def __init__(self):
    ...
```


### 注意事项

默认文件格式类型为Xlsx。如需创建其他类型的文件，请使用Workbook(FileFormatType)。
### 例子


下面的代码显示如何使用 Workbook 构造函数创建和初始化类的新实例。

```python
from aspose.cells import Workbook

workbook = Workbook()

```


##  \_\_init\_\_（自身，文件格式类型）{#aspose.cells.FileFormatType}
初始化 [`Workbook`](/cells/python-net/zh/aspose.cells/workbook) 类的新实例。



```python

def __init__(self, file_format_type):
    ...
```


|范围|类型|描述|
| :- | :- | :- |
| file_format_type | [`FileFormatType`](/cells/python-net/zh/aspose.cells/fileformattype) |新的文件格式。|
### 注意事项

默认文件格式类型为Excel97To2003。
### 例子


以下代码显示如何使用 Workbook 构造函数创建并初始化具有各种文件格式类型的类的新实例。

```python
from aspose.cells import FileFormatType, Workbook

workbook = Workbook(FileFormatType.XLSX)

```


##  \_\_init\_\_（自身，文件）{#str}
初始化[`Workbook`](/cells/python-net/zh/aspose.cells/workbook)类的新实例并打开一个文件。



```python

def __init__(self, file):
    ...
```


|范围|类型|描述|
| :- | :- | :- |
| file | str |文件名。|


##  \_\_init\_\_（自身，流）{#io.RawIOBase}
初始化[`Workbook`](/cells/python-net/zh/aspose.cells/workbook)类的新实例并打开一个流。



```python

def __init__(self, stream):
    ...
```


|范围|类型|描述|
| :- | :- | :- |
| stream | io.RawIOBase |溪流。|


##  \_\_init\_\_（自身，文件，load_options）{#str-aspose.cells.LoadOptions}
初始化[`Workbook`](/cells/python-net/zh/aspose.cells/workbook)类的新实例并打开一个文件。



```python

def __init__(self, file, load_options):
    ...
```


|范围|类型|描述|
| :- | :- | :- |
| file | str |文件名。|
| load_options | [`LoadOptions`](/cells/python-net/zh/aspose.cells/loadoptions) |加载选项|


## \_\_init\_\_（自身，流，加载选项）{#io.RawIOBase-aspose.cells.LoadOptions}
初始化[`Workbook`](/cells/python-net/zh/aspose.cells/workbook)类的新实例并打开流。



```python

def __init__(self, stream, load_options):
    ...
```


|范围|类型|描述|
| :- | :- | :- |
| stream | io.RawIOBase |溪流。|
| load_options | [`LoadOptions`](/cells/python-net/zh/aspose.cells/loadoptions) |加载选项|



### 也可以看看
* 模块[`aspose.cells`](../../)
* 类 [`Workbook`](/cells/python-net/zh/aspose.cells/workbook)
