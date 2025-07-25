---
title: add方法
second_title: Aspose.Cells for Python via .NET API 参考文献
description:
type: docs
weight: 20
url: /zh/aspose.cells.drawing/textboxcollection/add/
is_root: false
---
##  add(self, upper_left_row, upper_left_column, height, width) {#int-int-int-int}
将文本框添加到集合中。


### 返回

[`TextBox`](/cells/python-net/zh/aspose.cells.drawing/textbox) 对象索引。


```python

def add(self, upper_left_row, upper_left_column, height, width):
    ...
```


|范围|类型|描述|
| :- | :- | :- |
| upper_left_row | int |左上行索引。|
| upper_left_column | int |左上角的列索引。|
| height | int |文本框的高度，以像素为单位。|
| width | int |文本框的宽度，以像素为单位。|

### 例子

```python

# add a TextBox
index2 = textBoxCollection.add(1, 1, 50, 100)

```



### 也可以看看
* 模块[`aspose.cells.drawing`](../../)
* 类 [`TextBox`](/cells/python-net/zh/aspose.cells.drawing/textbox)
* 类 [`TextBoxCollection`](/cells/python-net/zh/aspose.cells.drawing/textboxcollection)
