---
title: set_image_resample метод
second_title: Aspose.Cells for Python via .NET API Ссылки
description:
type: docs
weight: 20
url: /ru/aspose.cells/pdfsaveoptions/set_image_resample/
is_root: false
---
##  set_image_resample(self, desired_ppi, jpeg_quality) {#int-int}
 Устанавливает желаемое количество пикселей на дюйм (PPI) для изображений с измененной выборкой и качество JPEG.
 Все изображения будут преобразованы в JPEG с указанными настройками качества,
и изображения, которые больше указанного PPI (пикселей на дюйм), будут подвергнуты повторной выборке.



```python

def set_image_resample(self, desired_ppi, jpeg_quality):
    ...
```


| Параметр| Тип| Описание|
| :- | :- | :- |
| desired_ppi | int | Желаемое количество пикселей на дюйм. 220 — высокое качество. 150 — качество экрана. 96 — качество электронной почты.|
| jpeg_quality | int | 0 - 100% JPEG качество.|

###  Пример

Следующий код устанавливает желаемое значение PPI 96 и качество JPEG 80 для изображений в выходном PDF-файле.

```python
from aspose.cells import PdfSaveOptions, Workbook

# load the source file with images.
wb = Workbook("Book1.xlsx")
pdfSaveOptions = PdfSaveOptions()
# set desired PPI as 96 and jpeg quality as 80.
pdfSaveOptions.set_image_resample(96, 80)
wb.save("output.pdf", pdfSaveOptions)

```



###  Смотрите также
* модуль [`aspose.cells`](../../)
* класс [`PdfSaveOptions`](/cells/python-net/ru/aspose.cells/pdfsaveoptions)
