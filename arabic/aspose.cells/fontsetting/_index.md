---
title: FontSetting صف
second_title: Aspose.Cells for Python via .NET API المراجع
description:
type: docs
weight: 700
url: /ar/aspose.cells/fontsetting/
is_root: false
---
##  FontSetting صف
يمثل نطاقًا من الأحرف داخل نص الخلية.



يكشف النوع FontSetting عن الأعضاء التاليين:

###  البنائين
| البناء| وصف|
| :- | :- |
| [__init__](/cells/python-net/ar/aspose.cells/fontsetting/__init__/#int-int-aspose.cells.WorksheetCollection) |  |


###  ملكيات
| ملكية| وصف|
| :- | :- |
| [type](/cells/python-net/ar/aspose.cells/fontsetting/type) | يحصل على نوع عقدة النص.|
| [start_index](/cells/python-net/ar/aspose.cells/fontsetting/start_index) |يحصل على فهرس البداية للأحرف.|
| [length](/cells/python-net/ar/aspose.cells/fontsetting/length) | يحصل على طول الأحرف.|
| [font](/cells/python-net/ar/aspose.cells/fontsetting/font) | إرجاع الخط لهذا الكائن.|
| [text_options](/cells/python-net/ar/aspose.cells/fontsetting/text_options) | إرجاع خيارات النص.|


###  طُرق
| طريقة| وصف|
| :- | :- |
| [set_word_art_style](/cells/python-net/ar/aspose.cells/fontsetting/set_word_art_style/#aspose.cells.drawing.PresetWordArtStyle) | يضبط نمط WordArt المعين مسبقًا.|



###  مثال

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

###  أنظر أيضا
* الوحدة [`aspose.cells`](..)
