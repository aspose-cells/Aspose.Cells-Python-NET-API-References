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

获取并设置该注意事项中包含数据和一些格式的html字符串。

### 注意事项

如果这是线程注释，则注释不能被更改，否则 MS Excel 无法将其作为线程注释进行处理。

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
