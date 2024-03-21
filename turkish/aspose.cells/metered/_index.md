---
title: Metered sınıfı
second_title: Aspose.Cells for Python via .NET API Referanslar
description:
type: docs
weight: 1090
url: /tr/aspose.cells/metered/
is_root: false
---
##  Metered sınıfı
Ölçülü anahtarı ayarlamak için yöntemler sağlar.



Metered türü aşağıdaki üyeleri ortaya çıkarır:

###  İnşaatçılar
| Oluşturucu| Tanım|
| :- | :- |
| [__init__](/cells/python-net/tr/aspose.cells/metered/__init__/#) | Bu sınıfın yeni bir örneğini başlatır.|


###  Yöntemler
| Yöntem| Tanım|
| :- | :- |
| [set_metered_key](/cells/python-net/tr/aspose.cells/metered/set_metered_key/#str-str) | Ölçülen genel ve özel anahtarı ayarlar.<br/> Tarifeli lisans satın alırsanız başvuruya başladığınızda bu API'i aramanız gerekiyor, normalde bu yeterli.<br/> Ancak tüketim verilerinin yüklenememesi ve 24 saati aşması halinde lisans değerlendirme durumuna geçecektir.<br/> böyle bir durumla karşılaşmamak için lisans durumunu düzenli olarak kontrol etmelisiniz, değerlendirme durumu ise API'i tekrar arayın.|
| [get_consumption_quantity](/cells/python-net/tr/aspose.cells/metered/get_consumption_quantity/#) | Tüketim dosyası boyutunu alır|
| [get_consumption_credit](/cells/python-net/tr/aspose.cells/metered/get_consumption_credit/#) | Tüketim kredisi alıyor|
| [get_product_name](/cells/python-net/tr/aspose.cells/metered/get_product_name/#) | Ürün adını alır|
| [is_metered_licensed](/cells/python-net/tr/aspose.cells/metered/is_metered_licensed/#) | Ölçüm cihazının lisanslı olup olmadığını kontrol edin|



###  Örnek

Bu örnekte, ölçülü genel ve özel anahtar ayarlanmaya çalışılacaktır.


```python
from aspose.cells import Metered

matered = Metered()
matered.set_metered_key("PublicKey", "PrivateKey")

```

###  Ayrıca bakınız
* modül [`aspose.cells`](..)
