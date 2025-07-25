---
title: is_triple_state属性
second_title: Aspose.Cells for Python via .NET API 参考文献
description:
type: docs
weight: 170
url: /zh/aspose.cells.drawing.activexcontrols/checkboxactivexcontrol/is_triple_state/
is_root: false
---
## is_triple_state属性

指示指定的控件将如何显示空值。

### 注意事项

|环境|描述|
| :- | :- |
|真的|控件将循环切换“是”、“否”和“Null”值的状态。当控件的 Value 属性设置为 Null 时，该控件将显示为暗淡（灰色）。|
|错误的|（默认）控件将循环切换“是”和“否”值的状态。空值将按“否”值显示。|
### 定义：
```python
@property
def is_triple_state(self):
    ...
@is_triple_state.setter
def is_triple_state(self, value):
    ...
```

### 也可以看看
* 模块[`aspose.cells.drawing.activexcontrols`](../../)
* 类 [`CheckBoxActiveXControl`](/cells/python-net/zh/aspose.cells.drawing.activexcontrols/checkboxactivexcontrol)
