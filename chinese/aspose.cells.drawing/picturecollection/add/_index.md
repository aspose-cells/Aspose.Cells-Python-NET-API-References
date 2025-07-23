---
title: add方法
second_title: Aspose.Cells for Python via .NET API 参考文献
description:
type: docs
weight: 20
url: /zh/aspose.cells.drawing/picturecollection/add/
is_root: false
---
##  add(self, upper_left_row, upper_left_column, stream) {#int-int-io.RawIOBase}
将图片添加到收藏夹。


### 返回

[`Picture`](/cells/python-net/zh/aspose.cells.drawing/picture) 对象索引。


```python

def add(self, upper_left_row, upper_left_column, stream):
    ...
```


|范围|类型|描述|
| :- | :- | :- |
| upper_left_row | int |左上行索引。|
| upper_left_column | int |左上角的列索引。|
| stream | io.RawIOBase |包含图像数据的流对象。|

### 例子

```python

# add a picture
with open("image.jpg", "rb") as fs:
    pictures.add(1, 1, fs)

```


##  add(self, upper_left_row, upper_left_column, file_name) {#int-int-str}
将图片添加到收藏夹。


### 返回

[`Picture`](/cells/python-net/zh/aspose.cells.drawing/picture) 对象索引。


```python

def add(self, upper_left_row, upper_left_column, file_name):
    ...
```


|范围|类型|描述|
| :- | :- | :- |
| upper_left_row | int |左上行索引。|
| upper_left_column | int |左上角的列索引。|
| file_name | str |图像文件名。|

### 例子

```python

# add a picture
pictures.add(1, 1, "image.jpg")

```


##  add(self, upper_left_row, upper_left_column, lower_right_row, lower_right_column, stream) {#int-int-int-int-io.RawIOBase}
将图片添加到收藏夹。


### 返回

[`Picture`](/cells/python-net/zh/aspose.cells.drawing/picture) 对象索引。


```python

def add(self, upper_left_row, upper_left_column, lower_right_row, lower_right_column, stream):
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
    pictures.add(1, 1, 5, 5, fs)

```


##  add(self, upper_left_row, upper_left_column, lower_right_row, lower_right_column, file_name) {#int-int-int-int-str}
将图片添加到收藏夹。


### 返回

[`Picture`](/cells/python-net/zh/aspose.cells.drawing/picture) 对象索引。


```python

def add(self, upper_left_row, upper_left_column, lower_right_row, lower_right_column, file_name):
    ...
```


|范围|类型|描述|
| :- | :- | :- |
| upper_left_row | int |左上行索引。|
| upper_left_column | int |左上角的列索引。|
| lower_right_row | int |右下行索引|
| lower_right_column | int |右下角列索引|
| file_name | str |图像文件名。|

### 例子

```python

# add a picture
pictures.add(1, 1, 5, 5, "image.jpg")

```


##  add(self, upper_left_row, upper_left_column, stream, width_scale, height_scale) {#int-int-io.RawIOBase-int-int}
将图片添加到收藏夹。


### 返回

[`Picture`](/cells/python-net/zh/aspose.cells.drawing/picture) 对象索引。


```python

def add(self, upper_left_row, upper_left_column, stream, width_scale, height_scale):
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
    pictures.add(1, 1, fs, 50, 50)

```


##  add(self, upper_left_row, upper_left_column, file_name, width_scale, height_scale) {#int-int-str-int-int}
将图片添加到收藏夹。


### 返回

[`Picture`](/cells/python-net/zh/aspose.cells.drawing/picture) 对象索引。


```python

def add(self, upper_left_row, upper_left_column, file_name, width_scale, height_scale):
    ...
```


|范围|类型|描述|
| :- | :- | :- |
| upper_left_row | int |左上行索引。|
| upper_left_column | int |左上角的列索引。|
| file_name | str |图像文件名。|
| width_scale | int |图像宽度的比例，百分比。|
| height_scale | int |图像高度的比例，以百分比表示。|

### 例子

```python

# add a picture
pictures.add(1, 1, "image.jpg", 50, 50)

```



### 也可以看看
* 模块[`aspose.cells.drawing`](../../)
* 类 [`Picture`](/cells/python-net/zh/aspose.cells.drawing/picture)
* 类 [`PictureCollection`](/cells/python-net/zh/aspose.cells.drawing/picturecollection)
