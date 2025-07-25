---
title: to_pdf方法
second_title: Aspose.Cells for Python via .NET API 参考文献
description:
type: docs
weight: 150
url: /zh/aspose.cells.charts/chart/to_pdf/
is_root: false
---
##  to_pdf(self, file_name) {#str}
将图表保存为 pdf 文件。



```python

def to_pdf(self, file_name):
    ...
```


|范围|类型|描述|
| :- | :- | :- |
| file_name | str |带完整路径的 PDF 文件名|


##  to_pdf(self, stream) {#io.RawIOBase}
创建图表 pdf 并将其保存到流中。



```python

def to_pdf(self, stream):
    ...
```


|范围|类型|描述|
| :- | :- | :- |
| stream | io.RawIOBase |输出流。|


##  to_pdf(self, file_name, desired_page_width, desired_page_height, h_alignment_type, v_alignment_type) {#str-float-float-aspose.cells.PageLayoutAlignmentType-aspose.cells.PageLayoutAlignmentType}
将图表保存为 pdf 文件。



```python

def to_pdf(self, file_name, desired_page_width, desired_page_height, h_alignment_type, v_alignment_type):
    ...
```


|范围|类型|描述|
| :- | :- | :- |
| file_name | str |带完整路径的 PDF 文件名|
| desired_page_width | float |所需的页面宽度（以英寸为单位）。|
| desired_page_height | float |所需的页面高度（以英寸为单位）。|
| h_alignment_type | [`PageLayoutAlignmentType`](/cells/python-net/zh/aspose.cells/pagelayoutalignmenttype) |输出页面中的图表水平对齐类型。|
| v_alignment_type | [`PageLayoutAlignmentType`](/cells/python-net/zh/aspose.cells/pagelayoutalignmenttype) |输出页面中的图表垂直对齐类型。|


##  to_pdf(self, stream, desired_page_width, desired_page_height, h_alignment_type, v_alignment_type) {#io.RawIOBase-float-float-aspose.cells.PageLayoutAlignmentType-aspose.cells.PageLayoutAlignmentType}
创建图表 pdf 并将其保存到流中。



```python

def to_pdf(self, stream, desired_page_width, desired_page_height, h_alignment_type, v_alignment_type):
    ...
```


|范围|类型|描述|
| :- | :- | :- |
| stream | io.RawIOBase |输出流。|
| desired_page_width | float |所需的页面宽度（以英寸为单位）。|
| desired_page_height | float |所需的页面高度（以英寸为单位）。|
| h_alignment_type | [`PageLayoutAlignmentType`](/cells/python-net/zh/aspose.cells/pagelayoutalignmenttype) |输出页面中的图表水平对齐类型。|
| v_alignment_type | [`PageLayoutAlignmentType`](/cells/python-net/zh/aspose.cells/pagelayoutalignmenttype) |输出页面中的图表垂直对齐类型。|



### 也可以看看
* 模块[`aspose.cells.charts`](../../)
* 类 [`Chart`](/cells/python-net/zh/aspose.cells.charts/chart)
