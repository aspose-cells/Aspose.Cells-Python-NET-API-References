---
title: sort方法
second_title: Aspose.Cells for Python via .NET API 参考文献
description:
type: docs
weight: 50
url: /zh/aspose.cells/datasorter/sort/
is_root: false
---
##  sort(self) {#}
对范围内的数据进行排序。


### 返回

已排序行/列的原始索引（绝对位置，例如，A 列为 0，B 列为 1，...）。
如果此排序操作不需要移动任何行/列，则返回 null。


```python

def sort(self):
    ...
```




##  sort(self, cells, area) {#aspose.cells.Cells-aspose.cells.CellArea}
对区域的数据进行排序。


### 返回

已排序行/列的原始索引（绝对位置，例如，A 列为 0，B 列为 1，...）。
如果此排序操作不需要移动任何行/列，则返回 null。


```python

def sort(self, cells, area):
    ...
```


|范围|类型|描述|
| :- | :- | :- |
| cells | [`Cells`](/cells/python-net/zh/aspose.cells/cells) |单元格包含数据区域。|
| area | [`CellArea`](/cells/python-net/zh/aspose.cells/cellarea) |需要排序的区域|


##  sort(self, cells, start_row, start_column, end_row, end_column) {#aspose.cells.Cells-int-int-int-int}
对区域的数据进行排序。


### 返回

已排序行/列的原始索引（绝对位置，例如，A 列为 0，B 列为 1，...）。
如果此排序操作不需要移动任何行/列，则返回 null。


```python

def sort(self, cells, start_row, start_column, end_row, end_column):
    ...
```


|范围|类型|描述|
| :- | :- | :- |
| cells | [`Cells`](/cells/python-net/zh/aspose.cells/cells) |单元格包含数据区域。|
| start_row | int |该区域的起始行。|
| start_column | int |区域的起始列。|
| end_row | int |该区域的最后一行。|
| end_column | int |该区域的最后一列。|



### 也可以看看
* 模块[`aspose.cells`](../../)
* 类 [`DataSorter`](/cells/python-net/zh/aspose.cells/datasorter)
