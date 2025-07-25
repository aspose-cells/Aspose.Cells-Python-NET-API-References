---
title: add_copy方法
second_title: Aspose.Cells for Python via .NET API 参考文献
description:
type: docs
weight: 90
url: /zh/aspose.cells.drawing/shapecollection/add_copy/
is_root: false
---
##  add_copy(self, source_shape, top_row, top, left_column, left) {#aspose.cells.drawing.Shape-int-int-int-int}
添加并复制形状到工作表。


### 返回

新的 [`Shape`](/cells/python-net/zh/aspose.cells.drawing/shape) 对象。


```python

def add_copy(self, source_shape, top_row, top, left_column, left):
    ...
```


|范围|类型|描述|
| :- | :- | :- |
| source_shape | [`Shape`](/cells/python-net/zh/aspose.cells.drawing/shape) |源形状。|
| top_row | int |顶行索引。|
| top | int |表示距其顶行的垂直偏移，以像素为单位。|
| left_column | int |左列索引。|
| left | int |表示相对于其左列的水平偏移量，以像素为单位。|

### 例子

```python

# add a shape
rectangle = shapes.add_rectangle(2, 0, 2, 0, 130, 130)
# Adds and copies a shape.
shapes.add_copy(rectangle, 7, 0, 7, 0)

```



### 也可以看看
* 模块[`aspose.cells.drawing`](../../)
* 类 [`Shape`](/cells/python-net/zh/aspose.cells.drawing/shape)
* 类 [`ShapeCollection`](/cells/python-net/zh/aspose.cells.drawing/shapecollection)
