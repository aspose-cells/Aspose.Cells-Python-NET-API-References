---
title: RowCollection类
second_title: Aspose.Cells for Python via .NET API 参考文献
description:
type: docs
weight: 1350
url: /zh/aspose.cells/rowcollection/
is_root: false
---
## RowCollection类
收集代表工作表中各个行的 [`Row`](/cells/python-net/zh/aspose.cells/row) 对象。



RowCollection 类型公开以下成员：

### 特性
|属性|描述|
| :- | :- |
| [count](/cells/python-net/zh/aspose.cells/rowcollection/count) |获取此集合中的行数。|



通过给定的行索引获取 [`Row`](/cells/python-net/zh/aspose.cells/row) 对象。如果给定行索引的 Row 对象之前不存在，则将实例化该对象。
### 索引器
|名称|描述|
| :- | :- |
| [index] |  |


### 方法
|方法|描述|
| :- | :- |
| [get_enumerator](/cells/python-net/zh/aspose.cells/rowcollection/get_enumerator/#bool-bool) |获取一个枚举器，该枚举器迭代此集合中的行|
| [get_row_by_index](/cells/python-net/zh/aspose.cells/rowcollection/get_row_by_index/#int) |按列表中的位置获取行对象。|
| [clear](/cells/python-net/zh/aspose.cells/rowcollection/clear/#) |清除所有行和单元格。|
| [remove_at](/cells/python-net/zh/aspose.cells/rowcollection/remove_at/#int) |删除此集合中指定索引（位置）处的行项目。|



### 例子

```python
from aspose.cells import Workbook

# Instantiating a Workbook object
workbook = Workbook()
# Obtaining the reference of the first worksheet
worksheet = workbook.worksheets[0]
# Get first row
row = worksheet.cells.rows[0]

```

### 也可以看看
* 模块[`aspose.cells`](..)
* 类 [`Row`](/cells/python-net/zh/aspose.cells/row)
