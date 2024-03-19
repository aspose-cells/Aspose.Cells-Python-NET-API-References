---
title: extend_to_next_sheet属性
second_title: Aspose.Cells for Python via .NET API 参考文献
description:
type: docs
weight: 120
url: /zh/aspose.cells/txtloadoptions/extend_to_next_sheet/
is_root: false
---
## extend_to_next_sheet属性

当数据行或列超过限制时是否将数据扩展到下一张表。
默认为 false。

### 评论

如果此属性为 true，则额外的数据将被放入当前工作表后面的下一个工作表中
（如果当前工作表是最后一张，新工作表将附加到当前工作簿）。
如果该属性为 false，则超出限制的数据将被忽略。
### 定义：
```python
@property
def extend_to_next_sheet(self):
    ...
@extend_to_next_sheet.setter
def extend_to_next_sheet(self, value):
    ...
```

### 也可以看看
* 模块[`aspose.cells`](../../)
* 类 [`TxtLoadOptions`](/cells/python-net/zh/aspose.cells/txtloadoptions)
