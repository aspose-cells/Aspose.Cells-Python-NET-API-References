---
title: calculation_mode属性
second_title: Aspose.Cells for Python via .NET API 参考文献
description:
type: docs
weight: 60
url: /zh/aspose.cells/formulasettings/calculation_mode/
is_root: false
---
## calculation_mode属性

获取或设置 MS Excel 中工作簿计算的模式。

### 注意事项

此属性仅用于将设置保存到结果电子表格文件
以便其他应用程序（例如 ms excel）在加载和操作结果文件时可以采取相应的行动。
出于大多数用户应用程序的性能考虑，我们不会自动计算工作簿中的任何公式，
无论该属性设置了什么模式。
如果用户需要计算公式，请始终根据需要调用不同对象上的方法：
[`Workbook.calculate_formula`](/cells/python-net/aspose.cells/workbook/calculate_formula), [`Worksheet.calculate_formula`](/cells/python-net/aspose.cells/worksheet/calculate_formula),
[`Cell.calculate`](/cells/python-net/zh/aspose.cells/cell/calculate)，...等等
### 定义：
```python
@property
def calculation_mode(self):
    ...
@calculation_mode.setter
def calculation_mode(self, value):
    ...
```

### 也可以看看
* 模块[`aspose.cells`](../../)
* 类 [`CalcModeType`](/cells/python-net/zh/aspose.cells/calcmodetype)
* 类 [`FormulaSettings`](/cells/python-net/zh/aspose.cells/formulasettings)
