---
title: html_note属性
second_title: Aspose.Cells for Python via .NET API 参考文献
description:
type: docs
weight: 150
url: /zh/aspose.cells/comment/html_note/
is_root: false
---
## html_note属性

获取和设置包含该注释中的数据和某些格式的html字符串。

### 评论

如果这是线程注释，则无法更改注释，否则 MS Excel 无法将其作为线程注释处理。

### 例子

```python

comment1.html_note = "<Font Style='FONT-FAMILY: Calibri;FONT-SIZE: 11pt;COLOR: #0000ff;TEXT-ALIGN: left;'>This is a <b>test</b>.</Font>"

```
### 定义：
```python
@property
def html_note(self):
    ...
@html_note.setter
def html_note(self, value):
    ...
```

### 也可以看看
* 模块[`aspose.cells`](../../)
* 类 [`Comment`](/cells/python-net/zh/aspose.cells/comment)
