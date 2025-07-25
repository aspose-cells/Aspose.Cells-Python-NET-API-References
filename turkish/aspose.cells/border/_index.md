---
title: Border sınıfı
second_title: Aspose.Cells for Python via .NET API Referanslar
description:
type: docs
weight: 60
url: /tr/aspose.cells/border/
is_root: false
---
##  Border sınıfı
Hücre sınırını temsil eden nesneyi kapsüller.



Border türü aşağıdaki üyeleri ortaya çıkarır:

###  Özellikler
| Mülk| Tanım|
| :- | :- |
| [theme_color](/cells/python-net/tr/aspose.cells/border/theme_color) | Sınırın tema rengini alır ve ayarlar.|
| [color](/cells/python-net/tr/aspose.cells/border/color) | Kenarlığın Rengini alır veya ayarlar.|
| [argb_color](/cells/python-net/tr/aspose.cells/border/argb_color) | 32-bit ARGB değerine sahip rengi alır ve ayarlar.|
| [line_style](/cells/python-net/tr/aspose.cells/border/line_style) | Hücre kenarlık türünü alır veya ayarlar.|



###  Örnek

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

###  Ayrıca bakınız
* modül [`aspose.cells`](..)
