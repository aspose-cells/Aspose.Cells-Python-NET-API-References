---
title: add_picture方法
second_title: Aspose.Cells for Python via .NET API 参考文献
description:
type: docs
weight: 230
url: /zh/aspose.cells.drawing/shapecollection/add_picture/
is_root: false
---
##  add_picture(self, upper_left_row, upper_left_column, lower_right_row, lower_right_column, stream) {#int-int-int-int-io.RawIOBase}
将图片添加到收藏夹。


### 返回

[`Picture`](/cells/python-net/zh/aspose.cells.drawing/picture) 图片对象。


```python

def add_picture(self, upper_left_row, upper_left_column, lower_right_row, lower_right_column, stream):
    ...
```


|范围|类型|描述|
| :- | :- | :- |
| upper_left_row | int |左上行索引。|
| upper_left_column | int |左上角的列索引。|
| lower_right_row | int |右下行索引|
| lower_right_column | int |右下角列索引|
| stream | io.RawIOBase |包含图像数据的流对象。|

### 例子

```python

# add a picture
with open("image.jpg", "rb") as fs:
    picture = shapes.add_picture(1, 0, 1, 0, fs)

```


##  add_picture(self, upper_left_row, upper_left_column, stream, width_scale, height_scale) {#int-int-io.RawIOBase-int-int}
将图片添加到收藏夹。


### 返回

[`Picture`](/cells/python-net/zh/aspose.cells.drawing/picture) 图片对象。


```python

def add_picture(self, upper_left_row, upper_left_column, stream, width_scale, height_scale):
    ...
```


|范围|类型|描述|
| :- | :- | :- |
| upper_left_row | int |左上行索引。|
| upper_left_column | int |左上角的列索引。|
| stream | io.RawIOBase |包含图像数据的流对象。|
| width_scale | int |图像宽度的比例，百分比。|
| height_scale | int |图像高度的比例，以百分比表示。|

### 例子

```python

# add a picture
with open("image.jpg", "rb") as fs:
    picture = shapes.add_picture(1, 1, fs, 50, 60)

```



### 也可以看看
* 模块[`aspose.cells.drawing`](../../)
* 类 [`Picture`](/cells/python-net/zh/aspose.cells.drawing/picture)
* 类 [`ShapeCollection`](/cells/python-net/zh/aspose.cells.drawing/shapecollection)
