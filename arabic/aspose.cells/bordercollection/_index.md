---
title: BorderCollection صف
second_title: Aspose.Cells for Python via .NET API المراجع
description:
type: docs
weight: 70
url: /ar/aspose.cells/bordercollection/
is_root: false
---
##  BorderCollection صف
يقوم بتغليف مجموعة من الكائنات [`Border`](/cells/python-net/ar/aspose.cells/border).



يكشف النوع BorderCollection عن الأعضاء التاليين:

###  ملكيات
| ملكية| وصف|
| :- | :- |
| [diagonal_color](/cells/python-net/ar/aspose.cells/bordercollection/diagonal_color) | يحصل على لون الخطوط القطرية أو يعينه.|
| [diagonal_style](/cells/python-net/ar/aspose.cells/bordercollection/diagonal_style) | يحصل على نمط الخطوط القطرية أو يعينه.|


###  طُرق
| طريقة| وصف|
| :- | :- |
| [`get(self, border_type)`](/cells/python-net/ar/aspose.cells/bordercollection/get/#aspose.cells.bordertype) | أضف API for Python عبر .Net. نظرًا لأن هذا [BorderType borderType] غير مدعوم|
| [`set_color(self, color)`](/cells/python-net/ar/aspose.cells/bordercollection/set_color/#aspose.pydrawing.color) | تعيين لون جميع الحدود في المجموعة.|
| [`set_style(self, style)`](/cells/python-net/ar/aspose.cells/bordercollection/set_style/#aspose.cells.cellbordertype) | تعيين نمط كافة حدود المجموعة.|



###  مثال

```python
from aspose.cells import BorderType, CellBorderType, Workbook
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
style = cell.get_style()
# Setting the line style of the top border
style.borders.get(BorderType.TOP_BORDER).line_style = CellBorderType.THICK
# Setting the color of the top border
style.borders.get(BorderType.TOP_BORDER).color = Color.black
# Setting the line style of the bottom border
style.borders.get(BorderType.BOTTOM_BORDER).line_style = CellBorderType.THICK
# Setting the color of the bottom border
style.borders.get(BorderType.BOTTOM_BORDER).color = Color.black
# Setting the line style of the left border
style.borders.get(BorderType.LEFT_BORDER).line_style = CellBorderType.THICK
# Setting the color of the left border
style.borders.get(BorderType.LEFT_BORDER).color = Color.black
# Setting the line style of the right border
style.borders.get(BorderType.RIGHT_BORDER).line_style = CellBorderType.THICK
# Setting the color of the right border
style.borders.get(BorderType.RIGHT_BORDER).color = Color.black
cell.set_style(style)
# Saving the Excel file
workbook.save("book1.xls")

```

###  أنظر أيضا
* الوحدة [`aspose.cells`](..)
* فئة [`Border`](/cells/python-net/ar/aspose.cells/border)
