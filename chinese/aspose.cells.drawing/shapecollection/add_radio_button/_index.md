---
title: add_radio_button方法
second_title: Aspose.Cells for Python via .NET API 参考文献
description:
type: docs
weight: 250
url: /zh/aspose.cells.drawing/shapecollection/add_radio_button/
is_root: false
---
##  add_radio_button(self, upper_left_row, top, upper_left_column, left, height, width) {#int-int-int-int-int-int}
向工作表添加一个 RadioButton。


### 返回

RadioButton 对象。


```python

def add_radio_button(self, upper_left_row, top, upper_left_column, left, height, width):
    ...
```


|范围|类型|描述|
| :- | :- | :- |
| upper_left_row | int |左上行索引。|
| top | int |表示RadioButton相对于其左行的垂直偏移量，以像素为单位。|
| upper_left_column | int |左上角的列索引。|
| left | int |表示RadioButton相对于其左列的水平偏移量，以像素为单位。|
| height | int |表示RadioButton的高度，单位为像素。|
| width | int |表示RadioButton的宽度，单位为像素。|

### 例子

```python

# add a radio button
radioButton = shapes.add_radio_button(1, 0, 1, 0, 100, 50)

```



### 也可以看看
* 模块[`aspose.cells.drawing`](../../)
* 类 [`ShapeCollection`](/cells/python-net/zh/aspose.cells.drawing/shapecollection)
