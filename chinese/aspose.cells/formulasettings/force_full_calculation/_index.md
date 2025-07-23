---
title: force_full_calculation属性
second_title: Aspose.Cells for Python via .NET API 参考文献
description:
type: docs
weight: 90
url: /zh/aspose.cells/formulasettings/force_full_calculation/
is_root: false
---
## force_full_calculation属性

指示每次触发计算时是否计算所有公式。

### 注意事项

此属性仅用于将设置保存到结果电子表格文件
以便其他应用程序（例如 ms excel）在加载和操作结果文件时可以采取相应的行动。
出于对大多数用户应用程序性能的考虑，我们不会自动计算工作簿中的任何公式，
无论该属性设置了什么值。
### 定义：
```python
@property
def force_full_calculation(self):
    ...
@force_full_calculation.setter
def force_full_calculation(self, value):
    ...
```

### 也可以看看
* 模块[`aspose.cells`](../../)
* 类 [`FormulaSettings`](/cells/python-net/zh/aspose.cells/formulasettings)
