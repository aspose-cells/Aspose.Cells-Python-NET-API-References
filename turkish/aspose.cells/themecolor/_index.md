---
title: ThemeColor sınıfı
second_title: Aspose.Cells for Python via .NET API Referanslar
description:
type: docs
weight: 1400
url: /tr/aspose.cells/themecolor/
is_root: false
---
##  ThemeColor sınıfı
Bir tema rengini temsil eder.



ThemeColor türü aşağıdaki üyeleri ortaya çıkarır:

###  İnşaatçılar
| Oluşturucu| Tanım|
| :- | :- |
| [`__init__(self, type, tint)`](/cells/python-net/tr/aspose.cells/themecolor/__init__/#aspose.cells.themecolortype-float) |  |


###  Özellikler
| Mülk| Tanım|
| :- | :- |
| [color_type](/cells/python-net/tr/aspose.cells/themecolor/color_type) | Tema türünü alır ve ayarlar.|
| [tint](/cells/python-net/tr/aspose.cells/themecolor/tint) | Renk tonu değerini alır ve ayarlar.|



###  Örnek

```python
from aspose.cells import BackgroundType, ThemeColor, ThemeColorType, Workbook

# Instantiating a Workbook object
workbook = Workbook()
cells = workbook.worksheets[0].cells
cells.get("A1").put_value("Hello World")
style = cells.get("A1").get_style()
# Set ThemeColorType.Text2 color type with 40% lighten as the font color.
style.font.theme_color = ThemeColor(ThemeColorType.TEXT2, 0.4)
style.pattern = BackgroundType.SOLID
# Set ThemeColorType.Background2 color type with 75% darken as the foreground color
style.foreground_theme_color = ThemeColor(ThemeColorType.BACKGROUND2, -0.75)
cells.get("A1").set_style(style)
# Saving the Excel file
workbook.save("book1.xlsx")

```

###  Ayrıca bakınız
* modül [`aspose.cells`](..)
