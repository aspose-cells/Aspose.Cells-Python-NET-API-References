---
title: html_cross_string_type属性
second_title: Aspose.Cells for Python via .NET API 参考文献
description:
type: docs
weight: 440
url: /zh/aspose.cells/htmlsaveoptions/html_cross_string_type/
is_root: false
---
## html_cross_string_type属性

指示以 html 格式保存 Excel 文件时是否以与 MS Excel 相同的方式显示跨单元格字符串。
默认情况下，该值为“Default”，因此，对于跨单元格字符串，Aspose.Cells 创建的 html 文件与 MS Excel 创建的 html 文件几乎没有区别。
但对于创建大型 html 文件的性能，将该值设置为 Cross 会比设置为 Default 或 Fit2Cell 快数倍。
### 定义：
```python
@property
def html_cross_string_type(self):
    ...
@html_cross_string_type.setter
def html_cross_string_type(self, value):
    ...
```

### 也可以看看
* 模块[`aspose.cells`](../../)
* 类 [`HtmlCrossType`](/cells/python-net/zh/aspose.cells/htmlcrosstype)
* 类 [`HtmlSaveOptions`](/cells/python-net/zh/aspose.cells/htmlsaveoptions)
