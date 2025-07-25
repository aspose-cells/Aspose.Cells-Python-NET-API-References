---
title: add_scroll_bar方法
second_title: Aspose.Cells for Python via .NET API 参考文献
description:
type: docs
weight: 270
url: /zh/aspose.cells.drawing/shapecollection/add_scroll_bar/
is_root: false
---
##  add_scroll_bar(self, upper_left_row, top, upper_left_column, left, height, width) {#int-int-int-int-int-int}
向工作表添加滚动条。


### 返回

ScrollBar 对象。


```python

def add_scroll_bar(self, upper_left_row, top, upper_left_column, left, height, width):
    ...
```


|范围|类型|描述|
| :- | :- | :- |
| upper_left_row | int |左上行索引。|
| top | int |表示ScrollBar相对于其左行的垂直偏移量，以像素为单位。|
| upper_left_column | int |左上角的列索引。|
| left | int |表示ScrollBar相对于其左列的水平偏移量，以像素为单位。|
| height | int |表示ScrollBar的高度，单位为像素。|
| width | int |表示ScrollBar的宽度，单位为像素。|

### 例子

```python

# add a scroll bar
scrollBar = shapes.add_scroll_bar(1, 0, 1, 0, 100, 20)

```



### 也可以看看
* 模块[`aspose.cells.drawing`](../../)
* 类 [`ShapeCollection`](/cells/python-net/zh/aspose.cells.drawing/shapecollection)
