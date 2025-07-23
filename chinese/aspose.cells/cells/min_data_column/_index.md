---
title: min_data_column属性
second_title: Aspose.Cells for Python via .NET API 参考文献
description:
type: docs
weight: 1190
url: /zh/aspose.cells/cells/min_data_column/
is_root: false
---
## min_data_column属性

包含数据的单元格的最小列索引。

### 注意事项

如果没有包含数据的单元格，则返回 -1。
此属性需要动态迭代并检查工作表中的所有单元格，
所以这是一个耗时的过程，不应该重复调用，
例如直接将其用作循环中的条件。
### 定义：
```python
@property
def min_data_column(self):
    ...
```

### 也可以看看
* 模块[`aspose.cells`](../../)
* 类 [`Cells`](/cells/python-net/zh/aspose.cells/cells)
