---
title: add_spinner方法
second_title: Aspose.Cells for Python via .NET API 参考资料
description:
type: docs
weight: 290
url: /zh/aspose.cells.drawing/shapecollection/add_spinner/
is_root: false
---
##  add_spinner(upper_left_row, top, upper_left_column, left, height, width) {#int-int-int-int-int-int}
将微调器添加到工作表。


### 返回

微调器对象。


```python
def add_spinner(self, upper_left_row, top, upper_left_column, left, height, width):
    ...
```


|范围|类型|描述|
| :- | :- | :- |
| upper_left_row | int |左上行索引。|
| top | int |表示 Spinner 相对于其左行的垂直偏移量，以像素为单位。|
| upper_left_column | int |左上列索引。|
| left | int |表示 Spinner 相对于其左列的水平偏移量，以像素为单位。|
| height | int |表示 Spinner 的高度，以像素为单位。|
| width | int |表示 Spinner 的宽度，以像素为单位。|

### 例子

```python

# add a spinner
spinner = shapes.add_spinner(1, 0, 1, 0, 100, 50)

```



### 也可以看看
* 模块 [aspose.cells.drawing](../../)
* 类 [ShapeCollection](/cells/python-net/zh/aspose.cells.drawing/shapecollection)
