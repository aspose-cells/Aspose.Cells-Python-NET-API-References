---
title: printing_page_type недвижимость
second_title: Aspose.Cells for Python via .NET API Рекомендации
description:
type: docs
weight: 220
url: /ru/aspose.cells/xpssaveoptions/printing_page_type/
is_root: false
---
##  printing_page_type недвижимость

Указывает, какие страницы не будут распечатаны.

###  Примечания

Если содержимое листа скудное, некоторые страницы в выходном PDF-файле будут совершенно пустыми.
Если вам не нужны эти пустые страницы, вы можете использовать эту опцию, чтобы пропустить их.

###  Пример

В следующем коде отсутствуют пустые страницы или страницы, которые содержат только некоторое содержимое стиля, например фон ячейки и границы.

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
###  Определение:
```python
@property
def printing_page_type(self):
    ...
@printing_page_type.setter
def printing_page_type(self, value):
    ...
```

###  Смотрите также
* модуль [`aspose.cells`](../../)
* класс [`PrintingPageType`](/cells/python-net/ru/aspose.cells/printingpagetype)
* класс [`XpsSaveOptions`](/cells/python-net/ru/aspose.cells/xpssaveoptions)
