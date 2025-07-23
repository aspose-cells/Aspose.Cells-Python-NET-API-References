---
title: set_image_resample方法
second_title: Aspose.Cells for Python via .NET API 参考文献
description:
type: docs
weight: 20
url: /zh/aspose.cells/pdfsaveoptions/set_image_resample/
is_root: false
---
##  set_image_resample(self, desired_ppi, jpeg_quality) {#int-int}
设置重采样图像所需的 PPI（每英寸像素数）和 jpeg 质量。
所有图像将转换为具有指定质量设置的 JPEG，
大于指定 PPI（每英寸像素数）的图像将被重新采样。



```python

def set_image_resample(self, desired_ppi, jpeg_quality):
    ...
```


|范围|类型|描述|
| :- | :- | :- |
| desired_ppi | int |每英寸所需像素数。220 高质量。150 屏幕质量。96 电子邮件质量。|
| jpeg_quality | int | 0 - 100% JPEG 质量。|

### 例子

以下代码将输出 pdf 中的图像所需 PPI 设置为 96，jpeg 质量设置为 80。

```python
from aspose.cells import PdfSaveOptions, Workbook

# load the source file with images.
wb = Workbook("Book1.xlsx")
pdfSaveOptions = PdfSaveOptions()
# set desired PPI as 96 and jpeg quality as 80.
pdfSaveOptions.set_image_resample(96, 80)
wb.save("output.pdf", pdfSaveOptions)

```



### 也可以看看
* 模块[`aspose.cells`](../../)
* 类 [`PdfSaveOptions`](/cells/python-net/zh/aspose.cells/pdfsaveoptions)
