---
title: Column sınıfı
second_title: Aspose.Cells for Python via .NET API Referanslar
description:
type: docs
weight: 240
url: /tr/aspose.cells/column/
is_root: false
---
##  Column sınıfı
Çalışma sayfasındaki tek bir sütunu temsil eder.



Column türü aşağıdaki üyeleri ortaya çıkarır:

###  Özellikler
| Mülk| Tanım|
| :- | :- |
| [index](/cells/python-net/tr/aspose.cells/column/index) | Bu sütunun indeksini alır.|
| [width](/cells/python-net/tr/aspose.cells/column/width) | Sütun genişliğini karakter biriminde alır ve ayarlar.|
| [group_level](/cells/python-net/tr/aspose.cells/column/group_level) | Sütunun grup düzeyini alır.|
| [is_hidden](/cells/python-net/tr/aspose.cells/column/is_hidden) | Sütunun gizli olup olmadığını belirtir.|
| [has_custom_style](/cells/python-net/tr/aspose.cells/column/has_custom_style) | Bu sütunun özel stil ayarlarına (çalışma kitabından devralınan varsayılan ayarlardan farklı) sahip olup olmadığını gösterir.|
| [style](/cells/python-net/tr/aspose.cells/column/style) | Bu sütunun stilini alır.|
| [is_collapsed](/cells/python-net/tr/aspose.cells/column/is_collapsed) | sütunun çöküp çökmediği|


###  Yöntemler
| Yöntem| Tanım|
| :- | :- |
| [`apply_style(self, style, flag)`](/cells/python-net/tr/aspose.cells/column/apply_style/#aspose.cells.style-aspose.cells.styleflag) | Tüm sütun için biçimleri uygular.|
| [`get_style(self)`](/cells/python-net/tr/aspose.cells/column/get_style/#) | Bu sütunun stilini alır.|
| [`set_style(self, style)`](/cells/python-net/tr/aspose.cells/column/set_style/#aspose.cells.style) | Bu sütunun stilini ayarlar.|



###  Örnek

```python
from aspose.cells import BackgroundType, StyleFlag, Workbook
from aspose.pydrawing import Color

# Instantiating a Workbook object
workbook = Workbook()
# Obtaining the reference of the first worksheet
worksheet = workbook.worksheets[0]
style = workbook.create_style()
# Setting the background color to Blue
style.background_color = Color.blue
# Setting the foreground color to Red
style.foreground_color = Color.red
# setting Background Pattern
style.pattern = BackgroundType.DIAGONAL_STRIPE
# New Style Flag
styleFlag = StyleFlag()
# Set All Styles
styleFlag.all = True
# Get first Column
column = worksheet.cells.columns[0]
# Apply Style to first Column
column.apply_style(style, styleFlag)
# Saving the Excel file
workbook.save("book1.xls")

```

###  Ayrıca bakınız
* modül [`aspose.cells`](..)
