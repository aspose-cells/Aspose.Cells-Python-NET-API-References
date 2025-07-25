---
title: set_array_formula方法
second_title: Aspose.Cells for Python via .NET API 参考文献
description:
type: docs
weight: 320
url: /zh/aspose.cells/cell/set_array_formula/
is_root: false
---
##  set_array_formula(self, array_formula, row_number, column_number) {#str-int-int}
将数组公式（在 ms excel 中通过 CTRL+SHIFT+ENTER 输入的传统数组公式）设置为单元格范围。



```python

def set_array_formula(self, array_formula, row_number, column_number):
    ...
```


|范围|类型|描述|
| :- | :- | :- |
| array_formula | str |数组公式。|
| row_number | int |填充数组公式结果的行数。|
| column_number | int |填充数组公式结果的列数。|


##  set_array_formula(self, array_formula, row_number, column_number, options) {#str-int-int-aspose.cells.FormulaParseOptions}
将数组公式设置为单元格区域。



```python

def set_array_formula(self, array_formula, row_number, column_number, options):
    ...
```


|范围|类型|描述|
| :- | :- | :- |
| array_formula | str |数组公式。|
| row_number | int |填充数组公式结果的行数。|
| column_number | int |填充数组公式结果的列数。|
| options | [`FormulaParseOptions`](/cells/python-net/zh/aspose.cells/formulaparseoptions) |解析公式的选项。|


##  set_array_formula(self, array_formula, row_number, column_number, is_r1c1, is_local) {#str-int-int-bool-bool}
将数组公式设置为单元格区域。



```python

def set_array_formula(self, array_formula, row_number, column_number, is_r1c1, is_local):
    ...
```


|范围|类型|描述|
| :- | :- | :- |
| array_formula | str |数组公式。|
| row_number | int |填充数组公式结果的行数。|
| column_number | int |填充数组公式结果的列数。|
| is_r1c1 | bool |公式是否为R1C1公式|
| is_local | bool |公式是否采用区域格式|
### 注意事项

注意：此类现已过时。取而代之的是
请使用Cell.SetArrayFormula(string,int,int,FormulaParseOptions)。
该房产将于 2019 年 12 月起 12 个月后被移除。
Aspose 对于您所遇到的不便深表歉意。

##  set_array_formula(self, array_formula, row_number, column_number, options, values) {#str-int-int-aspose.cells.FormulaParseOptions-list}
将数组公式设置为单元格区域。



```python

def set_array_formula(self, array_formula, row_number, column_number, options, values):
    ...
```


|范围|类型|描述|
| :- | :- | :- |
| array_formula | str |数组公式。|
| row_number | int |填充数组公式结果的行数。|
| column_number | int |填充数组公式结果的列数。|
| options | [`FormulaParseOptions`](/cells/python-net/zh/aspose.cells/formulaparseoptions) |解析公式的选项。|
| values | list |具有给定数组公式的单元格的值|



### 也可以看看
* 模块[`aspose.cells`](../../)
* 类 [`Cell`](/cells/python-net/zh/aspose.cells/cell)
