---
title: CellArea类
second_title: Aspose.Cells for Python via .NET API 参考文献
description:
type: docs
weight: 120
url: /zh/aspose.cells/cellarea/
is_root: false
---
## CellArea类
代表一个细胞区域。



CellArea 类型公开以下成员：

### 构造函数
|构造函数|描述|
| :- | :- |
| [`__init__(self)`](/cells/python-net/zh/aspose.cells/cellarea/__init__/#) |构造一个新的 CellArea 实例|


### 属性
|属性|描述|
| :- | :- |
| [start_row](/cells/python-net/zh/aspose.cells/cellarea/start_row) |获取或设置此区域的起始行。|
| [end_row](/cells/python-net/zh/aspose.cells/cellarea/end_row) |获取或设置此区域的结束行。|
| [start_column](/cells/python-net/zh/aspose.cells/cellarea/start_column) |获取或设置该区域的起始列。|
| [end_column](/cells/python-net/zh/aspose.cells/cellarea/end_column) |获取或设置此区域的结束列。|


### 方法
|方法|描述|
| :- | :- |
| [`create_cell_area(, start_row, start_column, end_row, end_column)`](/cells/python-net/zh/aspose.cells/cellarea/create_cell_area/#int-int-int-int) |创建一个单元格区域。|
| [`create_cell_area(, start_cell_name, end_cell_name)`](/cells/python-net/zh/aspose.cells/cellarea/create_cell_area/#str-str) |创建一个单元格区域。|
| [`compare_to(self, obj)`](/cells/python-net/zh/aspose.cells/cellarea/compare_to/#any) |根据左上角比较两个 CellArea 对象。|



### 例子

```python
from aspose.cells import CellArea

# Create Cell Area
ca = CellArea()
ca.start_row = 0
ca.end_row = 0
ca.start_column = 0
ca.end_column = 0

```

### 也可以看看
* 模块[`aspose.cells`](..)
