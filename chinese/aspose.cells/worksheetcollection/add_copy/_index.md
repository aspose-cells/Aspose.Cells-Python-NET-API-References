---
title: add_copy方法
second_title: Aspose.Cells for Python via .NET API 参考文献
description:
type: docs
weight: 30
url: /zh/aspose.cells/worksheetcollection/add_copy/
is_root: false
---
##  add_copy {#str}
将工作表添加到集合并从现有工作表复制数据。


### 退货

[`Worksheet`](/cells/python-net/zh/aspose.cells/worksheet) 对象索引。


```python
def add_copy(self, sheet_name):
    ...
```


|范围|类型|描述|
| :- | :- | :- |
| sheet_name | str |源工作表的名称。|
### 例外情况
|例外|描述|
| :- | :- |
| [`CellsException`](/cells/python-net/zh/aspose.cells/cellsexception) |指定无效的工作表名称。|




##  add_copy {#int}
将工作表添加到集合并从现有工作表复制数据。


### 退货

[`Worksheet`](/cells/python-net/zh/aspose.cells/worksheet) 对象索引。


```python
def add_copy(self, sheet_index):
    ...
```


|范围|类型|描述|
| :- | :- | :- |
| sheet_index | int |源工作表索引。|


##  add_copy {#list-list}
复制一组工作表。



```python
def add_copy(self, source, dest_sheet_names):
    ...
```


|范围|类型|描述|
| :- | :- | :- |
| source | list |源工作表。|
| dest_sheet_names | list |复制的工作表的名称。|



### 也可以看看
* 模块[`aspose.cells`](../../)
* 类 [`CellsException`](/cells/python-net/zh/aspose.cells/cellsexception)
* 类 [`Worksheet`](/cells/python-net/zh/aspose.cells/worksheet)
* 类 [`WorksheetCollection`](/cells/python-net/zh/aspose.cells/worksheetcollection)
