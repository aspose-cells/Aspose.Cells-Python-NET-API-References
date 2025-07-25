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

当数据的行数或列数超出限制时，是否将数据扩展到下一张表。
默认为 false。

### 注意事项

如果此属性为真，则额外的数据将放入当前工作表后面的下一张工作表中
（如果当前工作表是最后一张，新工作表将附加到当前工作簿）。
如果该属性为false，则超出限制的数据将被忽略。
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
