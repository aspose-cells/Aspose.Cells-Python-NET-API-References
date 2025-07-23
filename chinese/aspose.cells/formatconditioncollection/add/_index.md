---
title: add方法
second_title: Aspose.Cells for Python via .NET API 参考文献
description:
type: docs
weight: 20
url: /zh/aspose.cells/formatconditioncollection/add/
is_root: false
---
##  add(self, cell_area, type, operator_type, formula1, formula2) {#aspose.cells.CellArea-aspose.cells.FormatConditionType-aspose.cells.OperatorType-str-str}
向 FormatConditions 添加格式化条件和受影响的单元格范围
FormatConditions 最多可以包含三种条件格式。
条件格式的公式中不允许引用其他工作表。


### 返回

[0]:格式化条件对象索引；[1] 受影响的单元格范围索引。


```python

def add(self, cell_area, type, operator_type, formula1, formula2):
    ...
```


|范围|类型|描述|
| :- | :- | :- |
| cell_area | [`CellArea`](/cells/python-net/zh/aspose.cells/cellarea) |条件格式化的单元格范围。|
| type | [`FormatConditionType`](/cells/python-net/zh/aspose.cells/formatconditiontype) |条件格式的类型。它可以是 FormatConditionType 的成员之一。|
| operator_type | [`OperatorType`](/cells/python-net/zh/aspose.cells/operatortype) |比较运算符。它可以是 OperatorType 的成员之一。|
| formula1 | str |与条件格式相关的值或表达式。|
| formula2 | str |与条件格式相关的值或表达式|



### 也可以看看
* 模块[`aspose.cells`](../../)
* 类 [`FormatConditionCollection`](/cells/python-net/zh/aspose.cells/formatconditioncollection)
