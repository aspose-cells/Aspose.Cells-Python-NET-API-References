---
title: html_text属性
second_title: Aspose.Cells for Python via .NET API 参考文献
description:
type: docs
weight: 550
url: /zh/aspose.cells.drawing/lineshape/html_text/
is_root: false
---
## html_text属性

获取和设置包含此文本框中的数据和某些格式的 html 字符串。

### 例子

```python

html = shape.html_text
if html == null  or html == "":
    shape.html_text = "<Font Style='FONT-FAMILY: Calibri;FONT-SIZE: 11pt;COLOR: #0000ff;TEXT-ALIGN: left;'>This is a <b>test</b>.</Font>"

```
### 定义：
```python
@property
def html_text(self):
    ...
@html_text.setter
def html_text(self, value):
    ...
```

### 也可以看看
* 模块[`aspose.cells.drawing`](../../)
* 类 [`LineShape`](/cells/python-net/zh/aspose.cells.drawing/lineshape)
