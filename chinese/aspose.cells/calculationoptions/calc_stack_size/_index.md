---
title: calc_stack_size属性
second_title: Aspose.Cells for Python via .NET API 参考文献
description:
type: docs
weight: 30
url: /zh/aspose.cells/calculationoptions/calc_stack_size/
is_root: false
---
## calc_stack_size属性

用于递归计算单元格的堆栈大小。默认值为 200。

### 评论

当依赖树中有大量单元格需要递归计算时，
计算过程中可能会引发StackOverflowException。
如果是这样，用户应该为此属性指定较小的值。
对于这种情况，用户应根据实际的公式和数据确定该属性的合适值。
但值太小可能会导致公式计算性能下降，且值小于 2
将无法计算依赖于另一个公式的公式。因此，如果指定值小于 2，
它将被重置为 2。
### 定义：
```python
@property
def calc_stack_size(self):
    ...
@calc_stack_size.setter
def calc_stack_size(self, value):
    ...
```

### 也可以看看
* 模块[`aspose.cells`](../../)
* 类 [`CalculationOptions`](/cells/python-net/zh/aspose.cells/calculationoptions)
