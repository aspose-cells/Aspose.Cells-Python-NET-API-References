---
title: detect_file_format方法
second_title: Aspose.Cells for Python via .NET API 参考文献
description:
type: docs
weight: 20
url: /zh/aspose.cells/fileformatutil/detect_file_format/
is_root: false
---
##  detect_file_format（，流）{#io.RawIOBase}
检测并返回有关流中存储的 Excel 格式的信息。


### 返回

包含检测到的信息的 [`FileFormatInfo`](/cells/python-net/zh/aspose.cells/fileformatinfo) 对象。


```python

@staticmethod
def detect_file_format(stream):
    ...
```


|范围|类型|描述|
| :- | :- | :- |
| stream | io.RawIOBase |  |


##  detect_file_format（，文件路径）{#str}
检测并返回有关文件中存储的 Excel 格式的信息。


### 返回

包含检测到的信息的 [`FileFormatInfo`](/cells/python-net/zh/aspose.cells/fileformatinfo) 对象。


```python

@staticmethod
def detect_file_format(file_path):
    ...
```


|范围|类型|描述|
| :- | :- | :- |
| file_path | str |文件路径。|


##  detect_file_format（，流，密码）{#io.RawIOBase-str}
检测并返回有关流中存储的 Excel 格式的信息。


### 返回

包含检测到的信息的 [`FileFormatInfo`](/cells/python-net/zh/aspose.cells/fileformatinfo) 对象。


```python

@staticmethod
def detect_file_format(stream, password):
    ...
```


|范围|类型|描述|
| :- | :- | :- |
| stream | io.RawIOBase |  |
| password | str |加密 ooxml 文件的密码。|


##  detect_file_format（，文件路径，密码）{#str-str}
检测并返回有关文件中存储的 Excel 格式的信息。


### 返回

包含检测到的信息的 [`FileFormatInfo`](/cells/python-net/zh/aspose.cells/fileformatinfo) 对象。


```python

@staticmethod
def detect_file_format(file_path, password):
    ...
```


|范围|类型|描述|
| :- | :- | :- |
| file_path | str |文件路径。|
| password | str |加密 ooxml 文件的密码。|



### 也可以看看
* 模块[`aspose.cells`](../../)
* 类 [`FileFormatInfo`](/cells/python-net/zh/aspose.cells/fileformatinfo)
* 类 [`FileFormatUtil`](/cells/python-net/zh/aspose.cells/fileformatutil)
