---
title: refresh_dynamic_array_formulas方法
second_title: Aspose.Cells for Python via .NET API 参考文献
description:
type: docs
weight: 270
url: /zh/aspose.cells/workbook/refresh_dynamic_array_formulas/
is_root: false
---
##  refresh_dynamic_array_formulas {#bool}
刷新动态数组公式（根据当前数据溢出到新的相邻单元格范围）
工作簿中的其他公式即使被动态数组公式使用，也不会进行递归计算。



```python
def refresh_dynamic_array_formulas(self, calculate):
    ...
```


|范围|类型|描述|
| :- | :- | :- |
| calculate | bool |是否计算和更新这些动态数组公式的单元格值|


##  refresh_dynamic_array_formulas {#bool-aspose.cells.CalculationOptions}
刷新动态数组公式（根据当前数据溢出到新的相邻单元格范围）



```python
def refresh_dynamic_array_formulas(self, calculate, copts):
    ...
```


|范围|类型|描述|
| :- | :- | :- |
| calculate | bool |是否计算和更新这些动态数组公式的单元格值|
| copts | [`CalculationOptions`](/cells/python-net/zh/aspose.cells/calculationoptions) |计算公式的选项|
### 评论

出于性能考虑，我们不会自动刷新所有动态数组公式
当公式本身或其引用的数据发生更改时。
所以用户需要在那些可能影响动态数组公式的操作之后手动调用该方法，
例如导入/设置单元格值、插入/删除行/列/范围等。

对于大多数带函数的公式来说，计算溢出范围还需要计算公式，
因此，一般来说，“计算”标志的真实值是首选。
如果公式很简单，例如范围引用或数组（例如“=C1:E5”、“={1,2;3,4}”，...），
范围或数组上的简单函数（例如“=ABS(C1:E5)”、“=1+{1,2;3,4}”，...），
所有公式将在稍后计算（例如[`Workbook.calculate_formula`](/cells/python-net/zh/aspose.cells/workbook/calculate_formula)），
然后使用 false vlaue 作为“计算”标志可以避免重复计算，从而提高性能。


### 也可以看看
* 模块[`aspose.cells`](../../)
* 类 [`Workbook`](/cells/python-net/zh/aspose.cells/workbook)
