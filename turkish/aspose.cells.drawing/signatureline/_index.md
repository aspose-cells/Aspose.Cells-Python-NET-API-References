---
title: SignatureLine sınıfı
second_title: Aspose.Cells for Python via .NET API Referanslar
description:
type: docs
weight: 610
url: /tr/aspose.cells.drawing/signatureline/
is_root: false
---
##  SignatureLine sınıfı
İmza satırını temsil eder.



SignatureLine türü aşağıdaki üyeleri ortaya çıkarır:

###  İnşaatçılar
| Oluşturucu| Tanım|
| :- | :- |
| [`__init__(self)`](/cells/python-net/tr/aspose.cells.drawing/signatureline/__init__/#) | SignatureLine'ın yeni bir örneğini oluşturur|


###  Özellikler
| Mülk| Tanım|
| :- | :- |
| [id](/cells/python-net/tr/aspose.cells.drawing/signatureline/id) | Bu imza satırı için tanımlayıcıyı alır veya ayarlar.|
| [provider_id](/cells/python-net/tr/aspose.cells.drawing/signatureline/provider_id) | İmza sağlayıcısının kimliğini alır veya ayarlar.|
| [signer](/cells/python-net/tr/aspose.cells.drawing/signatureline/signer) | İmzalayanı alır veya ayarlar.|
| [title](/cells/python-net/tr/aspose.cells.drawing/signatureline/title) | Şarkıcının unvanını alır veya ayarlar.|
| [email](/cells/python-net/tr/aspose.cells.drawing/signatureline/email) | Şarkıcının e-postasını alır veya ayarlar.|
| [is_line](/cells/python-net/tr/aspose.cells.drawing/signatureline/is_line) | İmza satırı olup olmadığını belirtir.|
| [allow_comments](/cells/python-net/tr/aspose.cells.drawing/signatureline/allow_comments) | Yorumların eklenip eklenemeyeceğini belirtir.|
| [show_signed_date](/cells/python-net/tr/aspose.cells.drawing/signatureline/show_signed_date) | İmzalanma tarihinin gösterilip gösterilmediğini belirtir.|
| [instructions](/cells/python-net/tr/aspose.cells.drawing/signatureline/instructions) | İmzalama sırasında kullanıcıya gösterilen metni alır veya ayarlar.|
| [signature_line_type](/cells/python-net/tr/aspose.cells.drawing/signatureline/signature_line_type) | İmza türünü alır veya ayarlar.<br/>Varsayılan - Varsayılan değer ayarlandığında, karşılık gelen ProviderId değeri {0000000000-0000-0000-0000-000000000} olarak sabitlenir.<br/>Damga - Değer Damga olduğunda, karşılık gelen ProviderId değeri genellikle {000CD6A4-0000-0000-C000-000000000046} olur.<br/> Özel - Değer Özel olduğunda, genellikle ilgili ProviderId değerinin kullanıcı tarafından ayarlanması gerekir. Bu değer, sağlayıcıyla birlikte gönderilen belgelerden elde edilmelidir.|



###  Örnek

```python
from aspose.cells import Workbook
from aspose.cells.drawing import SignatureLine

# Instantiating a Workbook object
workbook = Workbook()
worksheet = workbook.worksheets[0]
#  Create signature line object
s = SignatureLine()
s.signer = "Simon"
s.title = "Development"
s.email = "simon@aspose.com"
s.instructions = "Sign to confirm the excel content."
#  Adds a Signature Line to the worksheet.
signatureLine = worksheet.shapes.add_signature_line(0, 0, s)
# do your business
# Save the excel file.
workbook.save("result.xlsx")

```

###  Ayrıca bakınız
* modül [`aspose.cells.drawing`](..)
