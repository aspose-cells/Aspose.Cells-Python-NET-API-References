---
title: put_value方法
second_title: Aspose.Cells for Python via .NET API 参考文献
description:
type: docs
weight: 290
url: /zh/aspose.cells/cell/put_value/
is_root: false
---
##  put_value(self, bool_value) {#bool}
将布尔值放入单元格。



```python

def put_value(self, bool_value):
    ...
```


|范围|类型|描述|
| :- | :- | :- |
| bool_value | bool |  |


##  put_value(self, int_value) {#int}
将整数值放入单元格。



```python

def put_value(self, int_value):
    ...
```


|范围|类型|描述|
| :- | :- | :- |
| int_value | int |输入值|


##  put_value(self, double_value) {#float}
将双精度值放入单元格。



```python

def put_value(self, double_value):
    ...
```


|范围|类型|描述|
| :- | :- | :- |
| double_value | float |输入值|


##  put_value(self, string_value) {#str}
将字符串值放入单元格。



```python

def put_value(self, string_value):
    ...
```


|范围|类型|描述|
| :- | :- | :- |
| string_value | str |输入值|


##  put_value(self, date_time) {#DateTime}
将 DateTime 值放入单元格。



```python

def put_value(self, date_time):
    ...
```


|范围|类型|描述|
| :- | :- | :- |
| date_time | DateTime |输入值|
### 注意事项

为单元格设置 DateTime 值并不意味着该单元格将自动格式化为日期时间。
在 ms excel 和 Aspose.Cells 的数据模型中，DateTime 值都以数值形式保存。
数值是否将被视为数值本身或日期时间
取决于此单元格应用的数字格式。如果此单元格尚未格式化为日期时间，
即使您输入的是 DateTime，它也将显示为数值。
### 例子

此示例显示如何将 DateTime 值设置为单元格并使其显示为日期时间。

```python
from aspose.cells import Workbook
from datetime import datetime

excel = Workbook()
cells = excel.worksheets[0].cells
# Put date time into a cell
cell = cells.get(0, 0)
cell.put_value(datetime(2023, 5, 15))
style = cell.get_style(False)
style.number = 14
cell.set_style(style)

```


##  put_value(self, object_value) {#any}
将对象值放入单元格。



```python

def put_value(self, object_value):
    ...
```


|范围|类型|描述|
| :- | :- | :- |
| object_value | any |输入值|


##  put_value(self, string_value, is_converted) {#str-bool}
将字符串值放入单元格，并在适当的情况下将该值转换为其他数据类型。



```python

def put_value(self, string_value, is_converted):
    ...
```


|范围|类型|描述|
| :- | :- | :- |
| string_value | str |输入值|
| is_converted | bool |真：如果合适，则转换为其他数据类型。|


##  put_value(self, string_value, is_converted, set_style) {#str-bool-bool}
将值放入单元格，如果合适，该值将转换为其他数据类型，并且单元格的数字格式将被重置。



```python

def put_value(self, string_value, is_converted, set_style):
    ...
```


|范围|类型|描述|
| :- | :- | :- |
| string_value | str |输入值|
| is_converted | bool |真：如果合适，则转换为其他数据类型。|
| set_style | bool | True：转换为其他数据类型时将数字格式设置为单元格的样式|



### 也可以看看
* 模块[`aspose.cells`](../../)
* 类 [`Cell`](/cells/python-net/zh/aspose.cells/cell)
