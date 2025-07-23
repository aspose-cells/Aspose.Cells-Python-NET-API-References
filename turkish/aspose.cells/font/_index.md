---
title: Font sınıfı
second_title: Aspose.Cells for Python via .NET API Referanslar
description:
type: docs
weight: 660
url: /tr/aspose.cells/font/
is_root: false
---
##  Font sınıfı
Bir elektronik tabloda kullanılan yazı tipi nesnesini kapsüller.



Font türü aşağıdaki üyeleri ortaya çıkarır:

###  Özellikler
| Mülk| Tanım|
| :- | :- |
| [charset](/cells/python-net/tr/aspose.cells/font/charset) | Karakter setini temsil eder.|
| [is_italic](/cells/python-net/tr/aspose.cells/font/is_italic) | Yazı tipinin italik olup olmadığını belirten bir değer alır veya ayarlar.|
| [is_bold](/cells/python-net/tr/aspose.cells/font/is_bold) | Yazı tipinin kalın olup olmadığını gösteren bir değer alır veya ayarlar.|
| [caps_type](/cells/python-net/tr/aspose.cells/font/caps_type) | Metin büyük harf türünü alır ve ayarlar.|
| [strike_type](/cells/python-net/tr/aspose.cells/font/strike_type) | Metnin vuruş türünü alır.|
| [is_strikeout](/cells/python-net/tr/aspose.cells/font/is_strikeout) | Yazı tipinin tek çizgili olup olmadığını belirten bir değer alır veya ayarlar.|
| [script_offset](/cells/python-net/tr/aspose.cells/font/script_offset) | Komut dosyası ofsetini yüzde biriminde alır ve ayarlar|
| [is_superscript](/cells/python-net/tr/aspose.cells/font/is_superscript) | Yazı tipinin üst simge olup olmadığını belirten bir değer alır veya ayarlar.|
| [is_subscript](/cells/python-net/tr/aspose.cells/font/is_subscript) | Yazı tipinin alt simge olup olmadığını belirten bir değer alır veya ayarlar.|
| [underline](/cells/python-net/tr/aspose.cells/font/underline) | Alt çizgi yazı tipini alır veya ayarlar.|
| [name](/cells/python-net/tr/aspose.cells/font/name) | [`Font`](/cells/python-net/tr/aspose.cells/font)'in adını alır veya ayarlar.|
| [double_size](/cells/python-net/tr/aspose.cells/font/double_size) | Yazı tipinin boyutunu iki katına çıkarır ve ayarlar.|
| [size](/cells/python-net/tr/aspose.cells/font/size) | Yazı tipinin boyutunu alır veya ayarlar.|
| [theme_color](/cells/python-net/tr/aspose.cells/font/theme_color) | Tema rengini alır ve ayarlar.|
| [color](/cells/python-net/tr/aspose.cells/font/color) | Yazı tipinin rengini alır veya ayarlar.|
| [argb_color](/cells/python-net/tr/aspose.cells/font/argb_color) | 32-bit ARGB değerine sahip rengi alır ve ayarlar.|
| [is_normalize_heights](/cells/python-net/tr/aspose.cells/font/is_normalize_heights) | Metne uygulanacak yükseklik normalizasyonunun çalışıp çalışmayacağını belirtir.|
| [scheme_type](/cells/python-net/tr/aspose.cells/font/scheme_type) |Yazı tipinin şema türünü alır ve ayarlar.|


###  Yöntemler
| Yöntem| Tanım|
| :- | :- |
| [`equals(self, font)`](/cells/python-net/tr/aspose.cells/font/equals/#aspose.cells.font) | İki yazı tipinin eşit olup olmadığını kontrol eder.|



###  Örnek

```python
from aspose.cells import Workbook
from aspose.pydrawing import Color

# Instantiating a Workbook object
workbook = Workbook()
# Obtaining the reference of the newly added worksheet by passing its sheet index
worksheet = workbook.worksheets[0]
# Accessing the "A1" cell from the worksheet
cell = worksheet.cells.get("A1")
# Adding some value to the "A1" cell
cell.put_value("Hello Aspose!")
font = cell.get_style().font
# Setting the font name to "Times New Roman"
font.name = "Times New Roman"
# Setting font size to 14
font.size = 14
# setting font color as Red
font.color = Color.red
# Saving the Excel file
workbook.save(r"dest.xls")

```

###  Ayrıca bakınız
* modül [`aspose.cells`](..)
* sınıf [`Font`](/cells/python-net/tr/aspose.cells/font)
