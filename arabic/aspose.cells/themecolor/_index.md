---
title: ThemeColor صف
second_title: Aspose.Cells for Python via .NET API المراجع
description:
type: docs
weight: 1500
url: /ar/aspose.cells/themecolor/
is_root: false
---
##  ThemeColor صف
يمثل لون الموضوع.



يكشف النوع ThemeColor عن الأعضاء التاليين:

###  البنائين
| البناء| وصف|
| :- | :- |
| [__init__](/cells/python-net/ar/aspose.cells/themecolor/__init__/#aspose.cells.ThemeColorType-float) |  |


###  ملكيات
| ملكية| وصف|
| :- | :- |
| [color_type](/cells/python-net/ar/aspose.cells/themecolor/color_type) | الحصول على نوع السمة وتعيينها.|
| [tint](/cells/python-net/ar/aspose.cells/themecolor/tint) | الحصول على قيمة الصبغة وتعيينها.|



###  مثال

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

###  أنظر أيضا
* الوحدة [`aspose.cells`](..)
