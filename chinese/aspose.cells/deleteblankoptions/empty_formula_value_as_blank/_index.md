---
title: empty_formula_value_as_blank属性
second_title: Aspose.Cells for Python via .NET API 参考文献
description:
type: docs
weight: 40
url: /zh/aspose.cells/deleteblankoptions/empty_formula_value_as_blank/
is_root: false
---
## empty_formula_value_as_blank属性

当公式计算结果为空或空字符串时，是否将其中一个单元格视为空白。
默认值为 false。

### 注意事项

一般情况下，用户在删除该属性为真的操作之前，应确保公式已经计算完毕。
否则，所有通过正常 API（例如 [`Cell.formula`](/cells/python-net/zh/aspose.cells/cell#formula)）新创建的公式将被视为空白，并可能被删除
因为在计算之前他们的计算结果都是空的。
### 定义：
```python
@property
def empty_formula_value_as_blank(self):
    ...
@empty_formula_value_as_blank.setter
def empty_formula_value_as_blank(self, value):
    ...
```

### 也可以看看
* 模块[`aspose.cells`](../../)
* 类 [`DeleteBlankOptions`](/cells/python-net/zh/aspose.cells/deleteblankoptions)
