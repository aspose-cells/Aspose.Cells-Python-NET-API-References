---
title: refer_to_sheet_with_same_name属性
second_title: Aspose.Cells for Python via .NET API 参考文献
description:
type: docs
weight: 90
url: /zh/aspose.cells/copyoptions/refer_to_sheet_with_same_name/
is_root: false
---
## refer_to_sheet_with_same_name属性

在 ms excel 中，将一个工作表复制到另一个工作表时，复制引用其他工作表的公式时，
复制的公式应参考源工作簿。
然而，在某些情况下，用户可能需要复制的公式引用具有相同名称的工作表
在同一工作簿中，例如在执行此复制操作之前已复制过这些工作表，
那么这个属性应该保持为真。

### 注意事项

默认值为 true。
### 定义：
```python
@property
def refer_to_sheet_with_same_name(self):
    ...
@refer_to_sheet_with_same_name.setter
def refer_to_sheet_with_same_name(self, value):
    ...
```

### 也可以看看
* 模块[`aspose.cells`](../../)
* 类 [`CopyOptions`](/cells/python-net/zh/aspose.cells/copyoptions)
