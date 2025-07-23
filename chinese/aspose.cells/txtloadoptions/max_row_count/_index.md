---
title: max_row_count属性
second_title: Aspose.Cells for Python via .NET API 参考文献
description:
type: docs
weight: 280
url: /zh/aspose.cells/txtloadoptions/max_row_count/
is_root: false
---
## max_row_count属性

一张工作表可导入的最大行数。

### 注意事项

超出此限制的行将被忽略
或根据 [`TxtLoadOptions.extend_to_next_sheet`](/cells/python-net/zh/aspose.cells/txtloadoptions#extend_to_next_sheet) 延长至下一张表。
此计数包括标题行（[`TxtLoadOptions.header_rows_count`](/cells/python-net/zh/aspose.cells/txtloadoptions#header_rows_count)）。
其允许的最大值为相应文件格式的行限制，例如对于 xlsx 文件，其允许的最大值为 1048576。
如果未指定此属性或指定的值不是正数，则也将使用最大限制。
### 定义：
```python
@property
def max_row_count(self):
    ...
@max_row_count.setter
def max_row_count(self, value):
    ...
```

### 也可以看看
* 模块[`aspose.cells`](../../)
* 类 [`TxtLoadOptions`](/cells/python-net/zh/aspose.cells/txtloadoptions)
