---
title: merged_cells_shrink_type属性
second_title: Aspose.Cells for Python via .NET API 参考文献
description:
type: docs
weight: 70
url: /zh/aspose.cells/deleteblankoptions/merged_cells_shrink_type/
is_root: false
---
## merged_cells_shrink_type属性

指示删除空白行/列时如何处理合并单元格。

### 注意事项

对于 [`MergedCellsShrinkType.KEEP_HEADER_ONLY`](/cells/python-net/zh/aspose.cells/mergedcellsshrinktype#KEEP_HEADER_ONLY)，除左上角的非空白单元格外，其中的所有单元格都将被视为空白。这是此属性的默认值。

对于 [`MergedCellsShrinkType.NONE`](/cells/python-net/zh/aspose.cells/mergedcellsshrinktype#NONE)，其中的所有单元格都将被视为非空白。

对于 [`MergedCellsShrinkType.SHRINK_TO_FIT`](/cells/python-net/zh/aspose.cells/mergedcellsshrinktype#SHRINK_TO_FIT)，内容显示区域之外的所有单元格都将被视为空白。
### 定义：
```python
@property
def merged_cells_shrink_type(self):
    ...
@merged_cells_shrink_type.setter
def merged_cells_shrink_type(self, value):
    ...
```

### 也可以看看
* 模块[`aspose.cells`](../../)
* 类 [`DeleteBlankOptions`](/cells/python-net/zh/aspose.cells/deleteblankoptions)
* 类 [`MergedCellsShrinkType`](/cells/python-net/zh/aspose.cells/mergedcellsshrinktype)
