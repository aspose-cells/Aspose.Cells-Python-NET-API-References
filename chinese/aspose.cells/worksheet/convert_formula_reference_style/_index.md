---
title: convert_formula_reference_style方法
second_title: Aspose.Cells for Python via .NET API 参考文献
description:
type: docs
weight: 120
url: /zh/aspose.cells/worksheet/convert_formula_reference_style/
is_root: false
---
##  convert_formula_reference_style {#str-bool-int-int}
转换公式参考样式。


### 退货

转换后的公式。


```python
def convert_formula_reference_style(self, formula, to_r1c1, base_cell_row, base_cell_column):
    ...
```


|范围|类型|描述|
| :- | :- | :- |
| formula | str |要转换的公式。|
| to_r1c1 | bool |将公式转换为哪种参考样式。<br/>如果原公式是A1参考样式，<br/>那么该值应该为 true，因此公式将从 A1 转换为 R1C1 参考样式；<br/>如果原公式是R1C1参考样式，<br/>那么该值应该为 false，因此公式将从 R1C1 转换为 A1 参考样式；|
| base_cell_row | int |基本单元格的行索引。|
| base_cell_column | int |基本单元格的列索引。|



### 也可以看看
* 模块[`aspose.cells`](../../)
* 类 [`Worksheet`](/cells/python-net/zh/aspose.cells/worksheet)
