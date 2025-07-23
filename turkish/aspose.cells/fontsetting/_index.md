---
title: FontSetting sınıfı
second_title: Aspose.Cells for Python via .NET API Referanslar
description:
type: docs
weight: 690
url: /tr/aspose.cells/fontsetting/
is_root: false
---
##  FontSetting sınıfı
Hücre metnindeki karakter aralığını temsil eder.



FontSetting türü aşağıdaki üyeleri ortaya çıkarır:

###  İnşaatçılar
| Oluşturucu| Tanım|
| :- | :- |
| [`__init__(self, start_index, length, sheets)`](/cells/python-net/tr/aspose.cells/fontsetting/__init__/#int-int-aspose.cells.worksheetcollection) |  |


###  Özellikler
| Mülk| Tanım|
| :- | :- |
| [type](/cells/python-net/tr/aspose.cells/fontsetting/type) |Metin düğümünün türünü alır.|
| [start_index](/cells/python-net/tr/aspose.cells/fontsetting/start_index) | Karakterlerin başlangıç indeksini alır.|
| [length](/cells/python-net/tr/aspose.cells/fontsetting/length) | Karakterlerin uzunluğunu alır.|
| [font](/cells/python-net/tr/aspose.cells/fontsetting/font) | Bu nesnenin yazı tipini döndürür.|
| [text_options](/cells/python-net/tr/aspose.cells/fontsetting/text_options) | Metin seçeneklerini döndürür.|


###  Yöntemler
| Yöntem| Tanım|
| :- | :- |
| [`set_word_art_style(self, style)`](/cells/python-net/tr/aspose.cells/fontsetting/set_word_art_style/#aspose.cells.drawing.presetwordartstyle) | Önceden ayarlanmış WordArt stilini ayarlar.|



###  Örnek

```python
from aspose.cells import Workbook
from aspose.pydrawing import Color

# Instantiating a Workbook object
workbook = Workbook()
# Adding a new worksheet to the Excel object
workbook.worksheets.add()
# Obtaining the reference of the newly added worksheet by passing its sheet index
worksheet = workbook.worksheets[0]
# Accessing the "A1" cell from the worksheet
cell = worksheet.cells.get("A1")
# Adding some value to the "A1" cell
cell.put_value("Visit Aspose!")
# getting charactor
charactor = cell.characters(6, 7)
# Setting the font of selected characters to bold
charactor.font.is_bold = True
# Setting the font color of selected characters to blue
charactor.font.color = Color.blue
# Saving the Excel file
workbook.save("book1.xls")

```

###  Ayrıca bakınız
* modül [`aspose.cells`](..)
