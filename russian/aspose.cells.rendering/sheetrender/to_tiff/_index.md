---
title: to_tiff метод
second_title: Aspose.Cells for Python via .NET API Ссылки
description:
type: docs
weight: 70
url: /ru/aspose.cells.rendering/sheetrender/to_tiff/
is_root: false
---
##  to_tiff(self, stream) {#io.RawIOBase}
Отобразить весь рабочий лист как изображение Tiff для потоковой передачи.



```python

def to_tiff(self, stream):
    ...
```


| Параметр| Тип| Описание|
| :- | :- | :- |
| stream | io.RawIOBase | поток выходного изображения|


##  to_tiff(self, filename) {#str}
Сохраните весь рабочий лист в виде изображения Tiff в файле.



```python

def to_tiff(self, filename):
    ...
```


| Параметр| Тип| Описание|
| :- | :- | :- |
| filename | str | имя файла выходного изображения|

###  Пример

Следующий код выводит все страницы первого листа в изображение Tiff.

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



###  Смотрите также
* модуль [`aspose.cells.rendering`](../../)
* класс [`SheetRender`](/cells/python-net/ru/aspose.cells.rendering/sheetrender)
