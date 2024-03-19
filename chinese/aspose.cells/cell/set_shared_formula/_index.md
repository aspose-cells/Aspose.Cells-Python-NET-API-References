---
title: set_shared_formula方法
second_title: Aspose.Cells for Python via .NET API 参考文献
description:
type: docs
weight: 350
url: /zh/aspose.cells/cell/set_shared_formula/
is_root: false
---
##  set_shared_formula {#str-int-int}
将共享公式设置为一系列单元格。



```python
def set_shared_formula(self, shared_formula, row_number, column_number):
    ...
```


|范围|类型|描述|
| :- | :- | :- |
| shared_formula | str |共享公式。|
| row_number | int |填充公式的行数。|
| column_number | int |用于填充公式的列数。|
### 评论



##  set_shared_formula {#str-int-int-aspose.cells.FormulaParseOptions}

将共享公式设置为一系列单元格。



```python
def set_shared_formula(self, shared_formula, row_number, column_number, options):
    ...
```


|范围|类型|描述|
| :- | :- | :- |
| shared_formula | str |共享公式。|
| row_number | int |填充公式的行数。|
| column_number | int |用于填充公式的列数。|
| options | [`FormulaParseOptions`](/cells/python-net/zh/aspose.cells/formulaparseoptions) |用于解析公式的选项。|


##  set_shared_formula {#str-int-int-bool-bool}
将公式设置为单元格区域。



```python
def set_shared_formula(self, shared_formula, row_number, column_number, is_r1c1, is_local):
    ...
```


|范围|类型|描述|
| :- | :- | :- |
| shared_formula | str |共享公式。|
| row_number | int |填充公式的行数。|
| column_number | int |用于填充公式的列数。|
| is_r1c1 | bool |式子是否为R1C1式|
| is_local | bool |公式是否采用区域设置格式|
### 评论

注意：该类现已过时。反而，
请使用 Cell.SetSharedFormula(string,int,int,FormulaParseOptions)。
该房产将于 2019 年 12 月起 12 个月后被移除。
Aspose 对于给您带来的任何不便，我们深表歉意。

##  set_shared_formula {#str-int-int-aspose.cells.FormulaParseOptions-list}
将共享公式设置为一系列单元格。



```python
def set_shared_formula(self, shared_formula, row_number, column_number, options, values):
    ...
```


|范围|类型|描述|
| :- | :- | :- |
| shared_formula | str |共享公式。|
| row_number | int |填充公式的行数。|
| column_number | int |用于填充公式的列数。|
| options | [`FormulaParseOptions`](/cells/python-net/zh/aspose.cells/formulaparseoptions) |用于解析公式的选项。|
| values | list |具有给定共享公式的单元格的值|



### 也可以看看
* 模块[`aspose.cells`](../../)
* 类 [`Cell`](/cells/python-net/zh/aspose.cells/cell)
