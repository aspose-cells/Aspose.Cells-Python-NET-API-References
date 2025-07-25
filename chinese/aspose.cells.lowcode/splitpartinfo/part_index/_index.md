---
title: part_index属性
second_title: Aspose.Cells for Python via .NET API 参考文献
description:
type: docs
weight: 30
url: /zh/aspose.cells.lowcode/splitpartinfo/part_index/
is_root: false
---
## part_index属性

序列中当前部分的索引（从 0 开始）。
-1 表示没有多个部分，因此结果为单个。

### 注意事项

如果需要处理多张表，并且每张表都进行处理（拆分）
另外，每个工作表的零件索引始终从 0 开始。
例如，将工作簿转换为图像时，
它代表当前处理的工作表的输出页面索引。
-1 表示当前工作表只有一页。
### 定义：
```python
@property
def part_index(self):
    ...
```

### 也可以看看
* 模块[`aspose.cells.lowcode`](../../)
* 类 [`SplitPartInfo`](/cells/python-net/zh/aspose.cells.lowcode/splitpartinfo)
