---
title: register_add_in_function方法
second_title: Aspose.Cells for Python via .NET API 参考文献
description:
type: docs
weight: 180
url: /zh/aspose.cells/worksheetcollection/register_add_in_function/
is_root: false
---
##  register_add_in_function(self, id, function_name) {#int-str}
在工作簿中添加插件功能


### 返回

包含插件函数的插件文件的URL


```python

def register_add_in_function(self, id, function_name):
    ...
```


|范围|类型|描述|
| :- | :- | :- |
| id | int |包含插件函数的数据的ID，<br/>可以通过对同一个插件文件第一次调用 [`WorksheetCollection.register_add_in_function`](/cells/python-net/zh/aspose.cells/worksheetcollection/register_add_in_function) 来获取。|
| function_name | str |插件函数名称|


##  register_add_in_function(self, add_in_file, function_name, lib) {#str-str-bool}
在工作簿中添加插件功能


### 返回

包含指定插件函数的数据ID


```python

def register_add_in_function(self, add_in_file, function_name, lib):
    ...
```


|范围|类型|描述|
| :- | :- | :- |
| add_in_file | str |该文件包含插件函数|
| function_name | str |插件函数名称|
| lib | bool |给定的插件文件是否位于 Workbook 插件库的目录或子目录中。<br/>当给定的 addInFile 为相对路径时，此标志生效并产生差异：<br/> true 表示该路径与加载项库相关，false 表示该路径与此工作簿相关。|



### 也可以看看
* 模块[`aspose.cells`](../../)
* 类 [`WorksheetCollection`](/cells/python-net/zh/aspose.cells/worksheetcollection)
