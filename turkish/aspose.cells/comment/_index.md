---
title: Comment sınıfı
second_title: Aspose.Cells for Python via .NET API Referanslar
description:
type: docs
weight: 260
url: /tr/aspose.cells/comment/
is_root: false
---
##  Comment sınıfı
Bir hücre yorumunu temsil eden nesneyi kapsüller.



Comment türü aşağıdaki üyeleri ortaya çıkarır:

###  Özellikler
| Mülk| Tanım|
| :- | :- |
| [author](/cells/python-net/tr/aspose.cells/comment/author) | Orijinal yorum yazarının adını alır ve ayarlar|
| [comment_shape](/cells/python-net/tr/aspose.cells/comment/comment_shape) | Belirtilen yoruma eklenen şekli temsil eden bir Şekil nesnesi alın.|
| [row](/cells/python-net/tr/aspose.cells/comment/row) | Yorumun satır indeksini alır.|
| [column](/cells/python-net/tr/aspose.cells/comment/column) | Yorumun sütun indeksini alır.|
| [is_threaded_comment](/cells/python-net/tr/aspose.cells/comment/is_threaded_comment) | Bu yorumun bir konu başlığı altında yorumlanıp yorumlanmadığını belirtir.|
| [threaded_comments](/cells/python-net/tr/aspose.cells/comment/threaded_comments) | Konulu yorumların listesini alır;|
| [note](/cells/python-net/tr/aspose.cells/comment/note) | Yorumun içeriğini temsil eder.|
| [html_note](/cells/python-net/tr/aspose.cells/comment/html_note) | Bu yorumda veri ve bazı formatları içeren html dizesini alır ve ayarlar.|
| [font](/cells/python-net/tr/aspose.cells/comment/font) | Yorumun yazı tipini alır.|
| [is_visible](/cells/python-net/tr/aspose.cells/comment/is_visible) | Yorumun görünür olup olmadığını gösterir.|
| [text_orientation_type](/cells/python-net/tr/aspose.cells/comment/text_orientation_type) | Yorumun metin yönlendirme türünü alır ve ayarlar.|
| [text_horizontal_alignment](/cells/python-net/tr/aspose.cells/comment/text_horizontal_alignment) | Yorumun metin yatay hizalama türünü alır ve ayarlar.|
| [text_vertical_alignment](/cells/python-net/tr/aspose.cells/comment/text_vertical_alignment) | Yorumun metin dikey hizalama türünü alır ve ayarlar.|
| [auto_size](/cells/python-net/tr/aspose.cells/comment/auto_size) | Yorumun boyutunun içeriğine göre otomatik olarak ayarlanıp ayarlanmadığını belirtir.<br/>Not: Bazı özel durumlarda (Mac ortamı gibi) bu ayar etkili olmayabilir. Bu ayar etkili olmazsa, lütfen FitToTextSize() ile değiştirin.|
| [height_cm](/cells/python-net/tr/aspose.cells/comment/height_cm) | Yorumun yüksekliğini santimetre cinsinden gösterir.|
| [width_cm](/cells/python-net/tr/aspose.cells/comment/width_cm) | Yorumun genişliğini santimetre cinsinden gösterir.|
| [width](/cells/python-net/tr/aspose.cells/comment/width) | Yorumun genişliğini piksel cinsinden temsil eder.|
| [height](/cells/python-net/tr/aspose.cells/comment/height) | Yorumun yüksekliğini piksel cinsinden temsil eder.|
| [width_inch](/cells/python-net/tr/aspose.cells/comment/width_inch) | Yorumun genişliğini inç cinsinden gösterir.|
| [height_inch](/cells/python-net/tr/aspose.cells/comment/height_inch) | Yorumun yüksekliğini inç cinsinden gösterir.|


###  Yöntemler
| Yöntem| Tanım|
| :- | :- |
| [`format_characters(self, start_index, length, font, flag)`](/cells/python-net/tr/aspose.cells/comment/format_characters/#int-int-aspose.cells.font-aspose.cells.styleflag) | Bazı karakterleri font ayarıyla biçimlendirin.|
| [`characters(self, start_index, length)`](/cells/python-net/tr/aspose.cells/comment/characters/#int-int) | Yorum metnindeki karakter aralığını temsil eden bir Characters nesnesi döndürür.|
| [`get_characters(self)`](/cells/python-net/tr/aspose.cells/comment/get_characters/#) | Tüm Karakter nesnelerini döndürür<br/> yorum metnindeki karakter aralığını temsil eder.|
| [`get_rich_formattings(self)`](/cells/python-net/tr/aspose.cells/comment/get_rich_formattings/#) | Tüm Karakter nesnelerini döndürür<br/> yorum metnindeki karakter aralığını temsil eder.|



###  Örnek

```python
from aspose.cells import Workbook

workbook = Workbook()
comments = workbook.worksheets[0].comments
# Add comment to cell A1
commentIndex1 = comments.add(0, 0)
comment1 = comments[commentIndex1]
comment1.note = "First note."
comment1.font.name = "Times New Roman"
# Add comment to cell B2
comments.add("B2")
comment2 = comments.get("B2")
comment2.note = "Second note."
# do your business
# Save the excel file.
workbook.save("exmaple.xlsx")

```

###  Ayrıca bakınız
* modül [`aspose.cells`](..)
