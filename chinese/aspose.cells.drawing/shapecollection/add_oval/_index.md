---
title: add_oval方法
second_title: Aspose.Cells for Python via .NET API 参考文献
description:
type: docs
weight: 220
url: /zh/aspose.cells.drawing/shapecollection/add_oval/
is_root: false
---
##  add_oval(self, upper_left_row, top, upper_left_column, left, height, width) {#int-int-int-int-int-int}
在工作表中添加一个椭圆。


### 返回

椭圆形物体。


```python

def add_oval(self, upper_left_row, top, upper_left_column, left, height, width):
    ...
```


|范围|类型|描述|
| :- | :- | :- |
| upper_left_row | int |左上行索引。|
| top | int |表示椭圆距其左行的垂直偏移量，以像素为单位。|
| upper_left_column | int |左上角的列索引。|
| left | int |表示椭圆距其左列的水平偏移量，以像素为单位。|
| height | int |表示椭圆的高度，以像素为单位。|
| width | int |表示椭圆的宽度，以像素为单位。|

### 例子

```python

# add a oval
oval = shapes.add_oval(1, 0, 1, 0, 50, 50)

```



### 也可以看看
* 模块[`aspose.cells.drawing`](../../)
* 类 [`ShapeCollection`](/cells/python-net/zh/aspose.cells.drawing/shapecollection)
