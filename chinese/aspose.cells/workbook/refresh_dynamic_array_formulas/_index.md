---
title: refresh_dynamic_array_formulas方法
second_title: Aspose.Cells for Python via .NET API 参考文献
description:
type: docs
weight: 290
url: /zh/aspose.cells/workbook/refresh_dynamic_array_formulas/
is_root: false
---
##  refresh_dynamic_array_formulas(self, calculate) {#bool}
刷新动态数组公式（根据当前数据溢出到相邻单元格的新范围）
工作簿中的其他公式即使被动态数组公式使用，也不会被递归计算。



```python

def refresh_dynamic_array_formulas(self, calculate):
    ...
```


|范围|类型|描述|
| :- | :- | :- |
| calculate | bool |是否计算并更新这些动态数组公式的单元格值|


##  refresh_dynamic_array_formulas(self, calculate, copts) {#bool-aspose.cells.CalculationOptions}
刷新动态数组公式（根据当前数据溢出到相邻单元格的新范围）



```python

def refresh_dynamic_array_formulas(self, calculate, copts):
    ...
```


|范围|类型|描述|
| :- | :- | :- |
| calculate | bool |是否计算并更新这些动态数组公式的单元格值|
| copts | [`CalculationOptions`](/cells/python-net/zh/aspose.cells/calculationoptions) |计算公式的选项|
### 注意事项

出于性能考虑，我们不会自动刷新所有动态数组公式
当公式本身或其引用的数据发生变化时。
因此用户需要在那些可能影响动态数组公式的操作之后手动调用此方法，
例如导入/设置单元格值、插入/删除行/列/范围等。

对于大多数带有函数的公式，计算溢出范围也需要计算公式，
因此一般来说，“计算”标志的真实值是首选。
如果公式很简单，例如区域引用或数组（例如“=C1:E5”、“={1,2;3,4}”...），
区域或数组上的简单函数（例如“=ABS(C1:E5)”、“=1+{1,2;3,4}”...），
所有公式都将稍后计算（例如 [`Workbook.calculate_formula`](/cells/python-net/zh/aspose.cells/workbook/calculate_formula)），
然后对“计算”标志使用假值可以避免重复计算，从而提高性能。


### 也可以看看
* 模块[`aspose.cells`](../../)
* 类 [`Workbook`](/cells/python-net/zh/aspose.cells/workbook)
