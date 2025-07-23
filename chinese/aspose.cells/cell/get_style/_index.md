---
title: get_style方法
second_title: Aspose.Cells for Python via .NET API 参考文献
description:
type: docs
weight: 220
url: /zh/aspose.cells/cell/get_style/
is_root: false
---
##  get_style(self) {#}
获取单元格样式。


### 返回

样式对象。


```python

def get_style(self):
    ...
```


### 注意事项

要改变单元格的样式，请在修改返回的样式对象后调用Cell.SetStyle()方法。
此方法与 [`Cell.get_style`](/cells/python-net/zh/aspose.cells/cell/get_style) 相同，参数为真值。

##  get_style(self, check_borders) {#bool}
如果 checkBorders 为真，则检查其他单元格的边框是否会影响此单元格的样式。


### 返回

样式对象。


```python

def get_style(self, check_borders):
    ...
```


|范围|类型|描述|
| :- | :- | :- |
| check_borders | bool |检查其他单元格的边界|
### 注意事项




### 也可以看看

* 模块[`aspose.cells`](../../)
* 类 [`Cell`](/cells/python-net/zh/aspose.cells/cell)
