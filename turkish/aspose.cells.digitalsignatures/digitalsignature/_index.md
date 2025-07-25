---
title: DigitalSignature sınıfı
second_title: Aspose.Cells for Python via .NET API Referanslar
description:
type: docs
weight: 10
url: /tr/aspose.cells.digitalsignatures/digitalsignature/
is_root: false
---
##  DigitalSignature sınıfı
İmza dosyada.



DigitalSignature türü aşağıdaki üyeleri ortaya çıkarır:

###  İnşaatçılar
| Oluşturucu| Tanım|
| :- | :- |
| [`__init__(self, certificate, comments, sign_time)`](/cells/python-net/tr/aspose.cells.digitalsignatures/digitalsignature/__init__/#system.security.cryptography.x509certificates.x509certificate2-str-datetime) | digitalSignature'ın kurucusu. .Net uygulamasını kullanır.|
| [`__init__(self, raw_data, password, comments, sign_time)`](/cells/python-net/tr/aspose.cells.digitalsignatures/digitalsignature/__init__/#bytes-str-str-datetime) |digitalSignature'ın kurucusu. Bouncy Castle uygulamasını kullanır.|


###  Özellikler
| Mülk| Tanım|
| :- | :- |
| [certificate](/cells/python-net/tr/aspose.cells.digitalsignatures/digitalsignature/certificate) | Belgeyi imzalamak için kullanılan sertifika nesnesi.|
| [comments](/cells/python-net/tr/aspose.cells.digitalsignatures/digitalsignature/comments) | İmzalamanın amacı.|
| [sign_time](/cells/python-net/tr/aspose.cells.digitalsignatures/digitalsignature/sign_time) | Belgenin imzalandığı zaman.|
| [id](/cells/python-net/tr/aspose.cells.digitalsignatures/digitalsignature/id) | Belge içeriğinde saklanan imza satırının GUID'si ile çapraz referanslanabilen bir GUID belirtir.<br/> Varsayılan değer Boş (tamamı sıfır) Guid'dir.|
| [text](/cells/python-net/tr/aspose.cells.digitalsignatures/digitalsignature/text) | Dijital imzadaki gerçek imzanın metnini belirtir.<br/> Varsayılan değer Boş'tur.|
| [image](/cells/python-net/tr/aspose.cells.digitalsignatures/digitalsignature/image) | Dijital imza için bir resim belirtir.<br/> Varsayılan değer null'dır.|
| [provider_id](/cells/python-net/tr/aspose.cells.digitalsignatures/digitalsignature/provider_id) | İmza sağlayıcısının sınıf kimliğini belirtir.<br/> Varsayılan değer Boş (tamamı sıfır) Guid'dir.|
| [is_valid](/cells/python-net/tr/aspose.cells.digitalsignatures/digitalsignature/is_valid) | Bu dijital imza geçerliyse ve belgede herhangi bir değişiklik yapılmamışsa,<br/> bu değer doğru olacaktır.|
| [x_ad_es_type](/cells/python-net/tr/aspose.cells.digitalsignatures/digitalsignature/x_ad_es_type) | XAdES türü.<br/> Varsayılan değer None'dur (XAdES kapalıdır).|



###  Ayrıca bakınız
* modül [`aspose.cells.digitalsignatures`](..)
