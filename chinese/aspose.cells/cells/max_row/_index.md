---
title: max_row属性
second_title: Aspose.Cells for Python via .NET API 参考文献
description:
type: docs
weight: 1150
url: /zh/aspose.cells/cells/max_row/
is_root: false
---
## max_row属性

包含数据或样式的单元格的最大行索引。

### 注意事项

如果工作表中没有包含数据或样式的单元格，则返回 -1。
此属性需要动态迭代和检查单元格和行，
所以这是一个耗时的过程，不应该重复调用，
例如直接将其用作循环中的条件。
### 定义：
```python
@property
def max_row(self):
    ...
```

### 也可以看看
* 模块[`aspose.cells`](../../)
* 类 [`Cells`](/cells/python-net/zh/aspose.cells/cells)
