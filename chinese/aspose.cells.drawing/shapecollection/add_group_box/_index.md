---
title: add_group_box方法
second_title: Aspose.Cells for Python via .NET API 参考文献
description:
type: docs
weight: 130
url: /zh/aspose.cells.drawing/shapecollection/add_group_box/
is_root: false
---
##  add_group_box(self, upper_left_row, top, upper_left_column, left, height, width) {#int-int-int-int-int-int}
将 GroupBox 添加到工作表。


### 返回

GroupBox 对象。


```python

def add_group_box(self, upper_left_row, top, upper_left_column, left, height, width):
    ...
```


|范围|类型|描述|
| :- | :- | :- |
| upper_left_row | int |左上行索引。|
| top | int |表示GroupBox相对于其左行的垂直偏移量，以像素为单位。|
| upper_left_column | int |左上角的列索引。|
| left | int |表示GroupBox相对于其左列的水平偏移量，以像素为单位。|
| height | int |表示GroupBox的高度，单位为像素。|
| width | int |表示GroupBox的宽度，单位为像素。|

### 例子

```python

# add a group box
groupBox = shapes.add_group_box(1, 0, 1, 0, 100, 50)

```



### 也可以看看
* 模块[`aspose.cells.drawing`](../../)
* 类 [`ShapeCollection`](/cells/python-net/zh/aspose.cells.drawing/shapecollection)
