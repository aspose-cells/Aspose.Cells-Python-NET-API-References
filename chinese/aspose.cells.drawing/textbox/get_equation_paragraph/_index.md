---
title: get_equation_paragraph方法
second_title: Aspose.Cells for Python via .NET API 参考文献
description:
type: docs
weight: 110
url: /zh/aspose.cells.drawing/textbox/get_equation_paragraph/
is_root: false
---
##  get_equation_paragraph(self) {#}
从 TextBox 对象的 TextBody 属性获取第一个数学段落。


### 返回

如果有数学段落，则返回第一个，否则返回 null。


```python

def get_equation_paragraph(self):
    ...
```




##  get_equation_paragraph(self, index) {#int}
从 TextBox 对象的 TextBody 属性获取指定的数学段落。
注意：
（1）当索引超出范围或未找到时返回 NULL。
（2）如果指定的索引位置不是数学段落，也返回 NULL。


### 返回

返回索引指定的数学段落。


```python

def get_equation_paragraph(self, index):
    ...
```


|范围|类型|描述|
| :- | :- | :- |
| index | int |数学段落的位置索引，从0开始。|



### 也可以看看
* 模块[`aspose.cells.drawing`](../../)
* 类 [`TextBox`](/cells/python-net/zh/aspose.cells.drawing/textbox)
