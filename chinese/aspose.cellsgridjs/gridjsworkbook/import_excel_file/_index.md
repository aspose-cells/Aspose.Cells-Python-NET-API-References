---
title: import_excel_file方法
second_title: Aspose.Cells.GridJs for Python via .NET API 参考文献
description:
type: docs
weight: 110
url: /zh/aspose.cellsgridjs/gridjsworkbook/import_excel_file/
is_root: false
---
##  import_excel_file {#str}

从文件路径导入 Excel 文件。



```python
def import_excel_file(self, file_name):
    ...
```


|范围|类型|描述|
| :- | :- | :- |
| file_name | str |文件的完整路径。|


##  import_excel_file {#str-str}

从文件路径导入 Excel 文件。



```python
def import_excel_file(self, uid, file_name):
    ...
```


|范围|类型|描述|
| :- | :- | :- |
| uid | str |文件缓存的唯一id，如果设置为null，则会自动生成。|
| file_name | str |文件的完整路径。|


##  import_excel_file {#io.RawIOBase-aspose.cellsgridjs.GridLoadFormat}

以加载格式从文件流导入 Excel 文件。



```python
def import_excel_file(self, filestream, format):
    ...
```


|范围|类型|描述|
| :- | :- | :- |
| filestream | io.RawIOBase | Excel 文件的流。|
| format | [`GridLoadFormat`](/cells/python-net/zh/aspose.cellsgridjs/gridloadformat) | Excel 文件的 LoadFormat。|


##  import_excel_file {#str-str-str}

从文件路径和打开密码导入 Excel 文件。



```python
def import_excel_file(self, uid, file_name, password):
    ...
```


|范围|类型|描述|
| :- | :- | :- |
| uid | str |文件缓存的唯一id，如果设置为null，则会自动生成。|
| file_name | str |文件的完整路径。|
| password | str | Excel文件的打开密码。如果没有设置密码，该值可以为空。|


##  import_excel_file {#str-io.RawIOBase-aspose.cellsgridjs.GridLoadFormat}

从文件流导入 Excel 文件。



```python
def import_excel_file(self, uid, filestream, format):
    ...
```


|范围|类型|描述|
| :- | :- | :- |
| uid | str |文件缓存的唯一id，如果设置为null，则会自动生成。|
| filestream | io.RawIOBase | Excel 文件的流。|
| format | [`GridLoadFormat`](/cells/python-net/zh/aspose.cellsgridjs/gridloadformat) | Excel 文件的 LoadFormat。|


##  import_excel_file {#io.RawIOBase-aspose.cellsgridjs.GridLoadFormat-str}

从文件流导入 Excel 文件，并带有加载格式和打开密码。



```python
def import_excel_file(self, filestream, format, password):
    ...
```


|范围|类型|描述|
| :- | :- | :- |
| filestream | io.RawIOBase | Excel 文件的流。|
| format | [`GridLoadFormat`](/cells/python-net/zh/aspose.cellsgridjs/gridloadformat) | Excel 文件的 LoadFormat。|
| password | str | Excel文件的打开密码。如果没有设置密码，该值可以为空。|


##  import_excel_file {#str-io.RawIOBase-aspose.cellsgridjs.GridLoadFormat-str}

从文件流导入 Excel 文件，并带有加载格式和打开密码。



```python
def import_excel_file(self, uid, filestream, format, password):
    ...
```


|范围|类型|描述|
| :- | :- | :- |
| uid | str |文件缓存的唯一id，如果设置为null，则会自动生成。|
| filestream | io.RawIOBase | Excel 文件的流。|
| format | [`GridLoadFormat`](/cells/python-net/zh/aspose.cellsgridjs/gridloadformat) | Excel 文件的 LoadFormat。|
| password | str | Excel文件的打开密码。如果没有设置密码，该值可以为空|



### 也可以看看
* 模块[`aspose.cellsgridjs`](../../)
* 类 [`GridJsWorkbook`](/cells/python-net/zh/aspose.cellsgridjs/gridjsworkbook)
