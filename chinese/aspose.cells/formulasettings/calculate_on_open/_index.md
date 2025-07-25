---
title: calculate_on_open属性
second_title: Aspose.Cells for Python via .NET API 参考文献
description:
type: docs
weight: 30
url: /zh/aspose.cells/formulasettings/calculate_on_open/
is_root: false
---
## calculate_on_open属性

指示打开工作簿时应用程序是否需要执行完整计算。

### 注意事项

此属性仅用于将设置保存到结果电子表格文件
以便其他应用程序（例如 ms excel）在加载结果文件时可以采取相应的行动。
出于对大多数用户应用程序性能的考虑，我们不会自动计算工作簿中的任何公式，
无论该属性设置了什么值。
### 定义：
```python
@property
def calculate_on_open(self):
    ...
@calculate_on_open.setter
def calculate_on_open(self, value):
    ...
```

### 也可以看看
* 模块[`aspose.cells`](../../)
* 类 [`FormulaSettings`](/cells/python-net/zh/aspose.cells/formulasettings)
