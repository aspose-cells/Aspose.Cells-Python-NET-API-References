---
title: printing_page_type属性
second_title: Aspose.Cells for Python via .NET API 参考文献
description:
type: docs
weight: 220
url: /zh/aspose.cells/docxsaveoptions/printing_page_type/
is_root: false
---
## printing_page_type属性

指示将不打印哪些页面。

### 评论

如果工作表中的内容稀疏，则输出的 pdf 文件中会有一些页面完全空白。
如果您不需要这些空白页，可以使用此选项忽略它们。

### 例子

以下代码省略了空白页面或仅包含单元格背景、边框等样式内容的页面。

```python
from aspose.cells import PdfSaveOptions, PrintingPageType, Workbook

wb = Workbook("Book1.xlsx")
pdfSaveOptions = PdfSaveOptions()
# ignore blank pages
pdfSaveOptions.printing_page_type = PrintingPageType.IGNORE_BLANK
wb.save("output_ignore_blank_page.pdf", pdfSaveOptions)
# ignore blank pages and pages which only contains some style content like cell background
pdfSaveOptions.printing_page_type = PrintingPageType.IGNORE_STYLE
wb.save("output_ignore_blank_and_style_page.pdf", pdfSaveOptions)

```
### 定义：
```python
@property
def printing_page_type(self):
    ...
@printing_page_type.setter
def printing_page_type(self, value):
    ...
```

### 也可以看看
* 模块[`aspose.cells`](../../)
* 类 [`DocxSaveOptions`](/cells/python-net/zh/aspose.cells/docxsaveoptions)
* 类 [`PrintingPageType`](/cells/python-net/zh/aspose.cells/printingpagetype)
