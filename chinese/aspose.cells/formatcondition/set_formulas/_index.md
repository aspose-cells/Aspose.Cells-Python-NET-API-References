---
title: set_formulas方法
second_title: Aspose.Cells for Python via .NET API 参考资料
description:
type: docs
weight: 60
url: /zh/aspose.cells/formatcondition/set_formulas/
is_root: false
---
##  set_formulas(formula1, formula2, is_r1c1, is_local) {#str-str-bool-bool}
设置与此格式条件关联的值或表达式。



```python
def set_formulas(self, formula1, formula2, is_r1c1, is_local):
    ...
```


|范围|类型|描述|
| :- | :- | :- |
| formula1 | str |与此格式条件关联的值或表达式。<br/>如果输入值以'='开头，则将其作为公式。否则它将被视为纯值（文本、数字、布尔值）。<br/>对于以'='开头的文本值，用户可以将其作为公式输入，格式为："=\"=...\""。|
| formula2 | str |与此格式条件关联的值或表达式。输入格式同公式1|
| is_r1c1 | bool |公式是否为R1C1公式。|
| is_local | bool |公式是否为区域设置格式。|



### 也可以看看
* 模块 [aspose.cells](../../)
* 类 [FormatCondition](/cells/python-net/zh/aspose.cells/formatcondition)
