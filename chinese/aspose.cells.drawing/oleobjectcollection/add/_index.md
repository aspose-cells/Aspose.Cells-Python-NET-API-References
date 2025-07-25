---
title: add方法
second_title: Aspose.Cells for Python via .NET API 参考文献
description:
type: docs
weight: 20
url: /zh/aspose.cells.drawing/oleobjectcollection/add/
is_root: false
---
##  add(self, upper_left_row, upper_left_column, height, width, image_data) {#int-int-int-int-bytes}
将 OleObject 添加到集合中。


### 返回

[`OleObject`](/cells/python-net/zh/aspose.cells.drawing/oleobject) 对象索引。


```python

def add(self, upper_left_row, upper_left_column, height, width, image_data):
    ...
```


|范围|类型|描述|
| :- | :- | :- |
| upper_left_row | int |左上行索引。|
| upper_left_column | int |左上角的列索引。|
| height | int | oleObject 的高度，以像素为单位。|
| width | int | oleObject 的宽度，以像素为单位。|
| image_data | bytes |作为字节数组的 OLE 对象图像。|


##  add(self, upper_left_row, upper_left_column, height, width, image_data, linked_file) {#int-int-int-int-bytes-str}
将链接的 OleObject 添加到集合中。


### 返回

[`OleObject`](/cells/python-net/zh/aspose.cells.drawing/oleobject) 对象索引。


```python

def add(self, upper_left_row, upper_left_column, height, width, image_data, linked_file):
    ...
```


|范围|类型|描述|
| :- | :- | :- |
| upper_left_row | int |左上行索引。|
| upper_left_column | int |左上角的列索引。|
| height | int | oleObject 的高度，以像素为单位。|
| width | int | oleObject 的宽度，以像素为单位。|
| image_data | bytes |作为字节数组的 OLE 对象图像。|
| linked_file | str |  |



### 也可以看看
* 模块[`aspose.cells.drawing`](../../)
* 类 [`OleObject`](/cells/python-net/zh/aspose.cells.drawing/oleobject)
* 类 [`OleObjectCollection`](/cells/python-net/zh/aspose.cells.drawing/oleobjectcollection)
