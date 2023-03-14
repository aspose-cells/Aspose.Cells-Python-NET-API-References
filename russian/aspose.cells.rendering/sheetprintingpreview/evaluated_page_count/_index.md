---
title: evaluated_page_count недвижимость
second_title: Aspose.Cells for Python via .NET API
description:
type: docs
weight: 30
url: /ru/aspose.cells.rendering/sheetprintingpreview/evaluated_page_count/
is_root: false
---
##  evaluated_page_count недвижимость

Оцените общее количество страниц этого рабочего листа

###  Пример

В следующем коде показан самый быстрый способ получить количество страниц листа.

```python
from aspose.cells import Workbook
from aspose.cells.rendering import ImageOrPrintOptions, SheetPrintingPreview

workbook = Workbook("Book1.xlsx")
sheetPrintingPreview = SheetPrintingPreview(workbook.worksheets[0], ImageOrPrintOptions())
# fastest way to get page count especailly when there are massive data in worksheet.
print(sheetPrintingPreview.evaluated_page_count)

```
###  Определение:
```python
@property
def evaluated_page_count(self):
    ...
```

###  Смотрите также
* модуль [aspose.cells.rendering](../../)
* класс [SheetPrintingPreview](/cells/python-net/ru/aspose.cells.rendering/sheetprintingpreview)
