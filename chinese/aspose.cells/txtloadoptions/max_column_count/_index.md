---
title: max_column_count属性
second_title: Aspose.Cells for Python via .NET API 参考文献
description:
type: docs
weight: 270
url: /zh/aspose.cells/txtloadoptions/max_column_count/
is_root: false
---
## max_column_count属性

一张工作表可导入的最大列数。

### 注意事项

超出此限制的列将被忽略
或根据 [`TxtLoadOptions.extend_to_next_sheet`](/cells/python-net/zh/aspose.cells/txtloadoptions#extend_to_next_sheet) 延长至下一张表。
此计数包括标题列（[`TxtLoadOptions.header_columns_count`](/cells/python-net/zh/aspose.cells/txtloadoptions#header_columns_count)）。
它的最大值是相应文件格式的列限制，例如对于 xlsx 文件，它是 16384。
如果未指定此属性或指定的值不是正数，则也将使用最大限制。
### 定义：
```python
@property
def max_column_count(self):
    ...
@max_column_count.setter
def max_column_count(self, value):
    ...
```

### 也可以看看
* 模块[`aspose.cells`](../../)
* 类 [`TxtLoadOptions`](/cells/python-net/zh/aspose.cells/txtloadoptions)
