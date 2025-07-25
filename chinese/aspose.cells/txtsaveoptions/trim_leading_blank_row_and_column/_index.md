---
title: trim_leading_blank_row_and_column属性
second_title: Aspose.Cells for Python via .NET API 参考文献
description:
type: docs
weight: 230
url: /zh/aspose.cells/txtsaveoptions/trim_leading_blank_row_and_column/
is_root: false
---
## trim_leading_blank_row_and_column属性

指示是否应像 MS Excel 一样修剪前导空白行和列。
默认为真。

### 注意事项

与 ms excel 中的规则相同，如果行/列具有自定义样式，则不会将其视为空白，
即使它不包含任何单元格数据。
当使用 LightCells 模式保存时，此选项不起作用。
用户应通过实施 [`TxtSaveOptions.LightCellsDataProvider`](/cells/python-net/zh/aspose.cells/txtsaveoptions) 来控制输出范围
或致电 [`TxtSaveOptions.export_area`](/cells/python-net/zh/aspose.cells/txtsaveoptions#export_area)
### 定义：
```python
@property
def trim_leading_blank_row_and_column(self):
    ...
@trim_leading_blank_row_and_column.setter
def trim_leading_blank_row_and_column(self, value):
    ...
```

### 也可以看看
* 模块[`aspose.cells`](../../)
* 类 [`TxtSaveOptions`](/cells/python-net/zh/aspose.cells/txtsaveoptions)
