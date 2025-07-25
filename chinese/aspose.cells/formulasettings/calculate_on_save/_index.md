---
title: calculate_on_save属性
second_title: Aspose.Cells for Python via .NET API 参考文献
description:
type: docs
weight: 40
url: /zh/aspose.cells/formulasettings/calculate_on_save/
is_root: false
---
## calculate_on_save属性

指示在手动计算模式下，保存文档之前是否重新计算工作簿。

### 注意事项

此属性仅用于将设置保存到结果电子表格文件
以便其他应用程序（例如 ms excel）在加载和操作结果文件时可以采取相应的行动。
出于对大多数用户应用程序性能的考虑，我们不会自动计算工作簿中的任何公式，
无论该属性设置了什么值。
### 定义：
```python
@property
def calculate_on_save(self):
    ...
@calculate_on_save.setter
def calculate_on_save(self, value):
    ...
```

### 也可以看看
* 模块[`aspose.cells`](../../)
* 类 [`FormulaSettings`](/cells/python-net/zh/aspose.cells/formulasettings)
