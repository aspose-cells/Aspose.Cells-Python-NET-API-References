---
title: preprocess_exported_value方法
second_title: Aspose.Cells for Python via .NET API 参考文献
description:
type: docs
weight: 20
url: /zh/aspose.cells/exporttableoptions/preprocess_exported_value/
is_root: false
---
##  preprocess_exported_value {#int-int-aspose.cells.CellValue}
预处理要导出的当前单元格的值。


### 退货

当前单元格是否已被替换为不同的类型和/或值。


```python
def preprocess_exported_value(self, cell_row, cell_column, value):
    ...
```


|范围|类型|描述|
| :- | :- | :- |
| cell_row | int |当前单元格的行索引|
| cell_column | int |单元格的列索引|
| value | [`CellValue`](/cells/python-net/zh/aspose.cells/cellvalue) |当前单元格的值和类型|
### 评论

行和列索引是单元格在工作表中的绝对索引，而不是导出表中的索引。
用户可以在该方法的重写实现中检查当前单元格的值，
如果当前单元格需要替换为其他类型和值，
这里的实现应该将预期的类型和值设置为 CellValue 对象并返回 true。
默认情况下，此方法不执行任何操作并返回 false。


### 也可以看看
* 模块[`aspose.cells`](../../)
* 类 [`ExportTableOptions`](/cells/python-net/zh/aspose.cells/exporttableoptions)
