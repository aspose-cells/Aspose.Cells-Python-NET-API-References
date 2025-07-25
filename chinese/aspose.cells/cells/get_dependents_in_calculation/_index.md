---
title: get_dependents_in_calculation方法
second_title: Aspose.Cells for Python via .NET API 参考文献
description:
type: docs
weight: 400
url: /zh/aspose.cells/cells/get_dependents_in_calculation/
is_root: false
---
##  get_dependents_in_calculation(self, row, column, recursive) {#int-int-bool}
获取计算结果依赖于特定单元格的所有单元格。


### 返回

枚举器枚举所有受抚养人（Cell 个对象）


```python

def get_dependents_in_calculation(self, row, column, recursive):
    ...
```


|范围|类型|描述|
| :- | :- | :- |
| row | int |特定单元格的行索引|
| column | int |特定单元格的列索引。|
| recursive | bool |是否返回那些不直接引用特定单元格的依赖项<br/>而是参考该细胞的其他叶子。|
### 注意事项

要使用此方法，请确保工作簿已设置真值
[`FormulaSettings.enable_calculation_chain`](/cells/python-net/zh/aspose.cells/formulasettings#enable_calculation_chain) 并且已经根据此设置进行了全面计算。
如果没有对该单元格的公式引用，则返回 null。
欲了解更多详情和示例，请参阅[`Cell.get_dependents_in_calculation`](/cells/python-net/zh/aspose.cells/cell/get_dependents_in_calculation)


### 也可以看看
* 模块[`aspose.cells`](../../)
* 类 [`Cells`](/cells/python-net/zh/aspose.cells/cells)
