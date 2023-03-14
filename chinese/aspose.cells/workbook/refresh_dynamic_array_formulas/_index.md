---
title: refresh_dynamic_array_formulas方法
second_title: Aspose.Cells for Python via .NET API 参考资料
description:
type: docs
weight: 270
url: /zh/aspose.cells/workbook/refresh_dynamic_array_formulas/
is_root: false
---
##  refresh_dynamic_array_formulas(calculate) {#bool}
刷新动态数组公式（根据当前数据溢出到相邻单元格的新范围）
工作簿中的其他公式即使被动态数组公式使用也不会递归计算。



```python
def refresh_dynamic_array_formulas(self, calculate):
    ...
```


|范围|类型|描述|
| :- | :- | :- |
| calculate | bool |是否计算和更新那些动态数组公式的单元格值|


##  refresh_dynamic_array_formulas(calculate, copts) {#bool-CalculationOptions}
刷新动态数组公式（根据当前数据溢出到相邻单元格的新范围）



```python
def refresh_dynamic_array_formulas(self, calculate, copts):
    ...
```


|范围|类型|描述|
| :- | :- | :- |
| calculate | bool |是否计算和更新那些动态数组公式的单元格值|
| copts | [CalculationOptions](/cells/python-net/zh/aspose.cells/calculationoptions) |计算公式的选项|



### 也可以看看
* 模块 [aspose.cells](../../)
* 类 [Workbook](/cells/python-net/zh/aspose.cells/workbook)
