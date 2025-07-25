---
title: add_rectangle方法
second_title: Aspose.Cells for Python via .NET API 参考文献
description:
type: docs
weight: 260
url: /zh/aspose.cells.drawing/shapecollection/add_rectangle/
is_root: false
---
##  add_rectangle(self, upper_left_row, top, upper_left_column, left, height, width) {#int-int-int-int-int-int}
向工作表添加一个 RectangleShape。


### 返回

RectangleShape 对象。


```python

def add_rectangle(self, upper_left_row, top, upper_left_column, left, height, width):
    ...
```


|范围|类型|描述|
| :- | :- | :- |
| upper_left_row | int |左上行索引。|
| top | int |表示 RectangleShape 相对于其左行的垂直偏移量，以像素为单位。|
| upper_left_column | int |左上角的列索引。|
| left | int |表示 RectangleShape 相对于其左列的水平偏移量，以像素为单位。|
| height | int |表示矩形的高度，以像素为单位。|
| width | int |表示 RectangleShape 的宽度，以像素为单位。|

### 例子

```python

#  add a rectangle
rectangleShape = shapes.add_rectangle(2, 0, 2, 0, 130, 130)

```



### 也可以看看
* 模块[`aspose.cells.drawing`](../../)
* 类 [`ShapeCollection`](/cells/python-net/zh/aspose.cells.drawing/shapecollection)
