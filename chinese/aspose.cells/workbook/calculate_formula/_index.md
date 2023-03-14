---
title: calculate_formula方法
second_title: Aspose.Cells for Python via .NET API 参考资料
description:
type: docs
weight: 40
url: /zh/aspose.cells/workbook/calculate_formula/
is_root: false
---
##  calculate_formula() {#}
计算公式的结果。



```python
def calculate_formula(self):
    ...
```


### 评论

对于所有支持的公式，请参阅 https://docs.aspose.com/display/cellsnet/Supported+Formula+Functions 上的列表

##  calculate_formula(ignore_error) {#bool}

计算公式的结果。



```python
def calculate_formula(self, ignore_error):
    ...
```


|范围|类型|描述|
| :- | :- | :- |
| ignore_error | bool |指示是否隐藏计算公式中的错误。错误可能是不支持的功能、外部链接等。|


##  calculate_formula(options) {#CalculationOptions}
计算本工作簿中的公式。



```python
def calculate_formula(self, options):
    ...
```


|范围|类型|描述|
| :- | :- | :- |
| options | [CalculationOptions](/cells/python-net/zh/aspose.cells/calculationoptions) |计算选项|


##  calculate_formula(ignore_error, custom_function) {#bool-ICustomFunction}
计算公式的结果。



```python
def calculate_formula(self, ignore_error, custom_function):
    ...
```


|范围|类型|描述|
| :- | :- | :- |
| ignore_error | bool |指示是否隐藏计算公式中的错误。错误可能是不支持的功能、外部链接等。|
| custom_function | [ICustomFunction](/cells/python-net/zh/aspose.cells/icustomfunction) |自定义公式计算功能，扩展计算引擎。|
### 评论

注意：该成员现已过时。反而，
请使用 CalculateFormula(CalculationOptions) 方法。
自 2020 年 8 月起，此方法将在 12 个月后被删除。
Aspose 对您可能遇到的任何不便深表歉意。


### 也可以看看
* 模块 [aspose.cells](../../)
* 类 [Workbook](/cells/python-net/zh/aspose.cells/workbook)
