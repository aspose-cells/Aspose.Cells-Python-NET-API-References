---
title: ShapeTextAlignment sınıfı
second_title: Aspose.Cells for Python via .NET API Referanslar
description:
type: docs
weight: 70
url: /tr/aspose.cells.drawing.texts/shapetextalignment/
is_root: false
---
##  ShapeTextAlignment sınıfı
Şeklin metin hizalamasının ayarını temsil eder;



ShapeTextAlignment türü aşağıdaki üyeleri ortaya çıkarır:

###  Özellikler
| Mülk| Tanım|
| :- | :- |
| [is_text_wrapped](/cells/python-net/tr/aspose.cells.drawing.texts/shapetextalignment/is_text_wrapped) | Metni içeren şeklin metin sarma türünü alır veya ayarlar.|
| [rotate_text_with_shape](/cells/python-net/tr/aspose.cells.drawing.texts/shapetextalignment/rotate_text_with_shape) | Metnin şekille birlikte döndürülüp döndürülmeyeceğini belirtir.|
| [text_vertical_overflow](/cells/python-net/tr/aspose.cells.drawing.texts/shapetextalignment/text_vertical_overflow) | Metin kutusunun metin dikey taşma türünü alır ve ayarlar.|
| [text_horizontal_overflow](/cells/python-net/tr/aspose.cells.drawing.texts/shapetextalignment/text_horizontal_overflow) | Metin kutusunun metin yatay taşma türünü alır ve ayarlar.|
| [rotation_angle](/cells/python-net/tr/aspose.cells.drawing.texts/shapetextalignment/rotation_angle) | Şeklin dönüşünü alır ve ayarlar.|
| [text_vertical_type](/cells/python-net/tr/aspose.cells.drawing.texts/shapetextalignment/text_vertical_type) | Metin yönünü alır ve ayarlar.|
| [is_locked_text](/cells/python-net/tr/aspose.cells.drawing.texts/shapetextalignment/is_locked_text) | Çalışma sayfası korunduğunda şeklin kilitli olup olmadığını gösterir.|
| [auto_size](/cells/python-net/tr/aspose.cells.drawing.texts/shapetextalignment/auto_size) | Şeklin boyutunun içeriğine göre otomatik olarak ayarlanıp ayarlanmadığını belirtir.|
| [text_shape_type](/cells/python-net/tr/aspose.cells.drawing.texts/shapetextalignment/text_shape_type) | Metnin dönüşüm türünü alır ve ayarlar.|
| [top_margin_pt](/cells/python-net/tr/aspose.cells.drawing.texts/shapetextalignment/top_margin_pt) | Üst kenar boşluğunu Puan biriminde döndürür|
| [bottom_margin_pt](/cells/python-net/tr/aspose.cells.drawing.texts/shapetextalignment/bottom_margin_pt) | Alt kenar boşluğunu Puan biriminde döndürür|
| [left_margin_pt](/cells/python-net/tr/aspose.cells.drawing.texts/shapetextalignment/left_margin_pt) | Sol kenar boşluğunu Nokta biriminde döndürür|
| [right_margin_pt](/cells/python-net/tr/aspose.cells.drawing.texts/shapetextalignment/right_margin_pt) | Sağ kenar boşluğunu Puan biriminde döndürür|
| [is_auto_margin](/cells/python-net/tr/aspose.cells.drawing.texts/shapetextalignment/is_auto_margin) |Metin çerçevesinin kenar boşluğunun otomatik olup olmadığını belirtir.|
| [number_of_columns](/cells/python-net/tr/aspose.cells.drawing.texts/shapetextalignment/number_of_columns) | Sınırlayıcı dikdörtgendeki metin sütunlarının sayısını alır ve ayarlar.|



###  Örnek

```python
from aspose.cells import Workbook

# Instantiating a Workbook object
workbook = Workbook()
shape = workbook.worksheets[0].shapes.add_rectangle(1, 0, 1, 0, 50, 100)
shapeTextAlignment = shape.text_body.text_alignment

```

###  Ayrıca bakınız
* modül [`aspose.cells.drawing.texts`](..)
