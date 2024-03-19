---
title: sheet_set недвижимость
second_title: Aspose.Cells for Python via .NET API Рекомендации
description:
type: docs
weight: 250
url: /ru/aspose.cells/docxsaveoptions/sheet_set/
is_root: false
---
##  sheet_set недвижимость

Получает или задает листы для визуализации. По умолчанию — все видимые листы в книге: [`SheetSet.visible`](/cells/python-net/ru/aspose.cells.rendering/sheetset#visible).

###  Пример

Следующий код отображает только активный лист в формате PDF.

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
* модуль [`aspose.cells`](../../)
* класс [`DocxSaveOptions`](/cells/python-net/ru/aspose.cells/docxsaveoptions)
* класс [`SheetSet`](/cells/python-net/ru/aspose.cells.rendering/sheetset)
