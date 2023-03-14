---
title: sheet_set недвижимость
second_title: Aspose.Cells for Python via .NET API
description:
type: docs
weight: 240
url: /ru/aspose.cells/pptxsaveoptions/sheet_set/
is_root: false
---
##  sheet_set недвижимость

Получает или задает листы для отображения. По умолчанию все видимые листы в книге: [SheetSet.visible](/cells/python-net/ru/aspose.cells.rendering/sheetset#visible).

###  Пример

Следующий код отображает только активный лист в pdf.

```python
from aspose.cells import PdfSaveOptions, Workbook
from aspose.cells.rendering import SheetSet

workbook = Workbook("Book1.xlsx")
activeSheetIndex = workbook.worksheets.active_sheet_index
pdfSaveOptions = PdfSaveOptions()
# set active sheet index to sheet set.
pdfSaveOptions.sheet_set = SheetSet([activeSheetIndex])
workbook.save("output.pdf", pdfSaveOptions)

```
###  Определение:
```python
@property
def sheet_set(self):
    ...
@sheet_set.setter
def sheet_set(self, value):
    ...
```

###  Смотрите также
* модуль [aspose.cells](../../)
* класс [PptxSaveOptions](/cells/python-net/ru/aspose.cells/pptxsaveoptions)
* класс [SheetSet](/cells/python-net/ru/aspose.cells.rendering/sheetset)
