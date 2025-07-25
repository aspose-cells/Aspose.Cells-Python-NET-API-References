---
title: BorderCollection sınıfı
second_title: Aspose.Cells for Python via .NET API Referanslar
description:
type: docs
weight: 70
url: /tr/aspose.cells/bordercollection/
is_root: false
---
##  BorderCollection sınıfı
[`Border`](/cells/python-net/tr/aspose.cells/border) nesneden oluşan bir koleksiyonu kapsüller.



BorderCollection türü aşağıdaki üyeleri ortaya çıkarır:

###  Özellikler
| Mülk| Tanım|
| :- | :- |
| [diagonal_color](/cells/python-net/tr/aspose.cells/bordercollection/diagonal_color) | Çapraz çizgilerin Rengini alır veya ayarlar.|
| [diagonal_style](/cells/python-net/tr/aspose.cells/bordercollection/diagonal_style) | Çapraz çizgilerin stilini alır veya ayarlar.|


###  Yöntemler
| Yöntem| Tanım|
| :- | :- |
| [`get(self, border_type)`](/cells/python-net/tr/aspose.cells/bordercollection/get/#aspose.cells.bordertype) | API for Python'i .Net yoluyla ekleyin. Bu [BorderType borderType] desteklenmediğinden|
| [`set_color(self, color)`](/cells/python-net/tr/aspose.cells/bordercollection/set_color/#aspose.pydrawing.color) | Koleksiyondaki tüm kenarlıkların Rengini ayarlar.|
| [`set_style(self, style)`](/cells/python-net/tr/aspose.cells/bordercollection/set_style/#aspose.cells.cellbordertype) | Koleksiyonun tüm kenarlıklarının stilini ayarlar.|



###  Örnek

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

###  Ayrıca bakınız
* modül [`aspose.cells`](..)
* sınıf [`Border`](/cells/python-net/tr/aspose.cells/border)
