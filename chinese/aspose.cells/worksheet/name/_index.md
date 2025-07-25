---
title: name属性
second_title: Aspose.Cells for Python via .NET API 参考文献
description:
type: docs
weight: 680
url: /zh/aspose.cells/worksheet/name/
is_root: false
---
## name属性

获取或设置工作表的 name。

### 注意事项

工作表 name 的最大长度为 31。并且您不能将相同的 name（不区分大小写）分配给两个工作表。
例如，不能将“SheetName1”设置为第一个工作表，而将“SHEETNAME1”设置为第二个工作表。
### 定义：
```python
@property
def name(self):
    ...
@name.setter
def name(self, value):
    ...
```

### 也可以看看
* 模块[`aspose.cells`](../../)
* 类 [`Worksheet`](/cells/python-net/zh/aspose.cells/worksheet)
