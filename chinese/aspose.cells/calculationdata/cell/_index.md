---
title: cell属性
second_title: Aspose.Cells for Python via .NET API 参考文献
description:
type: docs
weight: 70
url: /zh/aspose.cells/calculationdata/cell/
is_root: false
---
## cell属性

获取函数所在的Cell对象。

### 评论

当计算公式而不将其设置为cell时，
例如[`Worksheet.calculate_formula`](/cells/python-net/zh/aspose.cells/worksheet/calculate_formula)，
公式将按照设置为 cell A1 的方式进行计算，
所以 [`CalculationData.cell_row`](/cells/python-net/zh/aspose.cells/calculationdata#cell_row) 和 [`CalculationData.cell_column`](/cells/python-net/zh/aspose.cells/calculationdata#cell_column) 都是 0。
但是，工作表中的cell A1可能尚未实例化。
因此，对于这种情况，该属性将为空。
### 定义：
```python
@property
def cell(self):
    ...
```

### 也可以看看
* 模块[`aspose.cells`](../../)
* 类 [`CalculationData`](/cells/python-net/zh/aspose.cells/calculationdata)
* 类 [`Cell`](/cells/python-net/zh/aspose.cells/cell)
