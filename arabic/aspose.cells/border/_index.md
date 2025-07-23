---
title: Border صف
second_title: Aspose.Cells for Python via .NET API المراجع
description:
type: docs
weight: 60
url: /ar/aspose.cells/border/
is_root: false
---
##  Border صف
يقوم بتغليف الكائن الذي يمثل حدود الخلية.



يكشف النوع Border عن الأعضاء التاليين:

###  ملكيات
| ملكية| وصف|
| :- | :- |
| [theme_color](/cells/python-net/ar/aspose.cells/border/theme_color) | يحصل على لون موضوع الحدود ويحدده.|
| [color](/cells/python-net/ar/aspose.cells/border/color) | يحصل على لون الحدود أو يعينه.|
| [argb_color](/cells/python-net/ar/aspose.cells/border/argb_color) | يحصل على اللون ويضبطه بقيمة ARGB 32 بت.|
| [line_style](/cells/python-net/ar/aspose.cells/border/line_style) | يحصل على نوع حدود الخلية أو يعينه.|



###  مثال

```python
from aspose.cells import BorderType, CellBorderType, Workbook
from aspose.pydrawing import Color

workbook = Workbook()
sheets = workbook.worksheets
cell = sheets[0].cells.get("A1")
style = cell.get_style()
# Set top border style and color
border = style.borders.get(BorderType.TOP_BORDER)
border.line_style = CellBorderType.MEDIUM
border.color = Color.red
cell.set_style(style)

```

###  أنظر أيضا
* الوحدة [`aspose.cells`](..)
