---
title: TextBoxOptions sınıfı
second_title: Aspose.Cells for Python via .NET API Referanslar
description:
type: docs
weight: 80
url: /tr/aspose.cells.drawing.texts/textboxoptions/
is_root: false
---
##  TextBoxOptions sınıfı
Şeklin metin seçeneklerini temsil eder



TextBoxOptions türü aşağıdaki üyeleri ortaya çıkarır:

###  Özellikler
| Mülk| Tanım|
| :- | :- |
| [shape_text_vertical_alignment](/cells/python-net/tr/aspose.cells.drawing.texts/textboxoptions/shape_text_vertical_alignment) | Excel'de "Şekil Biçimi - Metin Seçenekleri - Metin Kutusu - Dikey Hizalama"ya karşılık gelir.|
| [resize_to_fit_text](/cells/python-net/tr/aspose.cells.drawing.texts/textboxoptions/resize_to_fit_text) | Şeklin metne uyacak şekilde yeniden boyutlandırılıp boyutlandırılmayacağını belirtir|
| [shape_text_direction](/cells/python-net/tr/aspose.cells.drawing.texts/textboxoptions/shape_text_direction) | Belirli bir metin gövdesi içindeki metin görüntüleme yönünü alır veya ayarlar.<br/> Excel'de "Şekil Biçimi - Metin Seçenekleri - Metin Kutusu - Metin yönü"ne karşılık gelir|
| [left_margin_pt](/cells/python-net/tr/aspose.cells.drawing.texts/textboxoptions/left_margin_pt) | Sol kenar boşluğunu Puan biriminde alır ve ayarlar.|
| [right_margin_pt](/cells/python-net/tr/aspose.cells.drawing.texts/textboxoptions/right_margin_pt) | Sağ kenar boşluğunu Puan biriminde alır ve ayarlar.|
| [top_margin_pt](/cells/python-net/tr/aspose.cells.drawing.texts/textboxoptions/top_margin_pt) | Üst kenar boşluğunu Puan biriminde alır ve ayarlar.|
| [bottom_margin_pt](/cells/python-net/tr/aspose.cells.drawing.texts/textboxoptions/bottom_margin_pt) | Alt kenar boşluğunu Puan biriminde döndürür|
| [allow_text_to_overflow](/cells/python-net/tr/aspose.cells.drawing.texts/textboxoptions/allow_text_to_overflow) | Metnin şeklin dışına taşmasına izin verilsin mi?|
| [wrap_text_in_shape](/cells/python-net/tr/aspose.cells.drawing.texts/textboxoptions/wrap_text_in_shape) | Bir şeklin içindeki metin sarmayı belirtir.<br/> Yanlış - Metin gövdesinde herhangi bir sarma işlemi gerçekleşmeyecektir.<br/>Doğru - Metin gövdesinde sarma işlemi gerçekleşecektir.|



###  Örnek

```python
from aspose.cells import Workbook

# Instantiating a Workbook object
workbook = Workbook()
index = workbook.worksheets[0].text_boxes.add(0, 0, 350, 350)
shape = workbook.worksheets[0].text_boxes[index]
shape.text = "This is test."
# do your business
# Save the excel file.
workbook.save("exmaple.xlsx")

```

###  Ayrıca bakınız
* modül [`aspose.cells.drawing.texts`](..)
