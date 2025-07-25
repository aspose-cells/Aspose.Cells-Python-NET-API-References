---
title: to_tiff方法
second_title: Aspose.Cells for Python via .NET API 参考文献
description:
type: docs
weight: 70
url: /zh/aspose.cells.rendering/sheetrender/to_tiff/
is_root: false
---
##  to_tiff(self, stream) {#io.RawIOBase}
将整个工作表作为 Tiff 图像渲染到流中。



```python

def to_tiff(self, stream):
    ...
```


|范围|类型|描述|
| :- | :- | :- |
| stream | io.RawIOBase |输出图像的流|


##  to_tiff(self, filename) {#str}
将整个工作表作为 Tiff 图像呈现到文件中。



```python

def to_tiff(self, filename):
    ...
```


|范围|类型|描述|
| :- | :- | :- |
| filename | str |输出图像的文件名|

### 例子

以下代码将第一张表的所有页面输出为 Tiff 图像。

```python
from aspose.cells import SaveFormat, Workbook
from aspose.cells.rendering import ImageOrPrintOptions, SheetRender

# load the source file with images.
wb = Workbook("Book1.xlsx")
imgOpt = ImageOrPrintOptions()
# set output image type.
imgOpt.save_format = SaveFormat.TIFF
# render the first sheet.
sr = SheetRender(wb.worksheets[0], imgOpt)
# output all the pages of the sheet to Tiff image.
sr.to_tiff("output.tiff")

```



### 也可以看看
* 模块[`aspose.cells.rendering`](../../)
* 类 [`SheetRender`](/cells/python-net/zh/aspose.cells.rendering/sheetrender)
