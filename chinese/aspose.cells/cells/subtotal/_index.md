---
title: subtotal方法
second_title: Aspose.Cells for Python via .NET API 参考文献
description:
type: docs
weight: 910
url: /zh/aspose.cells/cells/subtotal/
is_root: false
---
##  subtotal {#aspose.cells.CellArea-int-aspose.cells.ConsolidationFunction-list}
创建范围的小计。



```python
def subtotal(self, ca, group_by, function, total_list):
    ...
```


|范围|类型|描述|
| :- | :- | :- |
| ca | [`CellArea`](/cells/python-net/zh/aspose.cells/cellarea) |范围|
| group_by | int |分组依据的字段，作为从零开始的整数偏移量|
| function | [`ConsolidationFunction`](/cells/python-net/zh/aspose.cells/consolidationfunction) |小计功能。|
| total_list | list |从零开始的字段偏移量数组，指示添加小计的字段。|


##  subtotal {#aspose.cells.CellArea-int-aspose.cells.ConsolidationFunction-list-bool-bool-bool}
创建范围的小计。



```python
def subtotal(self, ca, group_by, function, total_list, replace, page_breaks, summary_below_data):
    ...
```


|范围|类型|描述|
| :- | :- | :- |
| ca | [`CellArea`](/cells/python-net/zh/aspose.cells/cellarea) |范围|
| group_by | int |分组依据的字段，作为从零开始的整数偏移量|
| function | [`ConsolidationFunction`](/cells/python-net/zh/aspose.cells/consolidationfunction) |小计功能。|
| total_list | list |从零开始的字段偏移量数组，指示添加小计的字段。|
| replace | bool |是否替换当前小计|
| page_breaks | bool |组间是否添加分页符|
| summary_below_data | bool |是否在数据下方添加摘要。|



### 也可以看看
* 模块[`aspose.cells`](../../)
* 类 [`Cells`](/cells/python-net/zh/aspose.cells/cells)
