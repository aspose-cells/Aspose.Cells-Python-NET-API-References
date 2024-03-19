---
title: register_add_in_function方法
second_title: Aspose.Cells for Python via .NET API 参考文献
description:
type: docs
weight: 180
url: /zh/aspose.cells/worksheetcollection/register_add_in_function/
is_root: false
---
##  register_add_in_function {#int-str}
将插件功能添加到工作簿中


### 退货

包含插件函数的插件文件的 URL


```python
def register_add_in_function(self, id, function_name):
    ...
```


|范围|类型|描述|
| :- | :- | :- |
| id | int |包含插件函数的数据的ID，<br/>可以通过对同一个插件文件第一次调用 [`WorksheetCollection.register_add_in_function`](/cells/python-net/zh/aspose.cells/worksheetcollection/register_add_in_function) 来获取。|
| function_name | str |插件函数名称|


##  register_add_in_function {#str-str-bool}
将插件功能添加到工作簿中


### 退货

包含给定插件函数的数据的 ID


```python
def register_add_in_function(self, add_in_file, function_name, lib):
    ...
```


|范围|类型|描述|
| :- | :- | :- |
| add_in_file | str |该文件包含插件函数|
| function_name | str |插件函数名称|
| lib | bool |给定的加载项文件是否位于工作簿加载项库的目录或子目录中。<br/>当给定的 addInFile 是相对路径时，此标志生效并产生影响：<br/> true 表示路径相对于加载项库，false 表示路径相对于此工作簿。|



### 也可以看看
* 模块[`aspose.cells`](../../)
* 类 [`WorksheetCollection`](/cells/python-net/zh/aspose.cells/worksheetcollection)
