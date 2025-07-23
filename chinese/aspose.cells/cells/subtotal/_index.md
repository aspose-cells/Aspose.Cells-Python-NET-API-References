---
title: subtotal方法
second_title: Aspose.Cells for Python via .NET API 参考文献
description:
type: docs
weight: 930
url: /zh/aspose.cells/cells/subtotal/
is_root: false
---
##  subtotal(self, ca, group_by, function, total_list) {#aspose.cells.CellArea-int-aspose.cells.ConsolidationFunction-list}
为该范围创建小计。



```python

def subtotal(self, ca, group_by, function, total_list):
    ...
```


|范围|类型|描述|
| :- | :- | :- |
| ca | [`CellArea`](/cells/python-net/zh/aspose.cells/cellarea) |范围|
| group_by | int |分组字段，以零为基础的整数偏移量|
| function | [`ConsolidationFunction`](/cells/python-net/zh/aspose.cells/consolidationfunction) |小计函数。|
| total_list | list |从零开始的字段偏移量数组，指示要添加小计的字段。|


##  subtotal(self, ca, group_by, function, total_list, replace, page_breaks, summary_below_data) {#aspose.cells.CellArea-int-aspose.cells.ConsolidationFunction-list-bool-bool-bool}
为该范围创建小计。



```python

def subtotal(self, ca, group_by, function, total_list, replace, page_breaks, summary_below_data):
    ...
```


|范围|类型|描述|
| :- | :- | :- |
| ca | [`CellArea`](/cells/python-net/zh/aspose.cells/cellarea) |范围|
| group_by | int |分组字段，以零为基础的整数偏移量|
| function | [`ConsolidationFunction`](/cells/python-net/zh/aspose.cells/consolidationfunction) |小计函数。|
| total_list | list |从零开始的字段偏移量数组，指示要添加小计的字段。|
| replace | bool |指示是否替换当前的小计|
| page_breaks | bool |指示是否在组之间添加分页符|
| summary_below_data | bool |指示是否在数据下方添加摘要。|



### 也可以看看
* 模块[`aspose.cells`](../../)
* 类 [`Cells`](/cells/python-net/zh/aspose.cells/cells)
