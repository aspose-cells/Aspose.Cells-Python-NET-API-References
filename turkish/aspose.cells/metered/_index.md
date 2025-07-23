---
title: Metered sınıfı
second_title: Aspose.Cells for Python via .NET API Referanslar
description:
type: docs
weight: 980
url: /tr/aspose.cells/metered/
is_root: false
---
##  Metered sınıfı
Ölçülü anahtarı ayarlamak için yöntemler sağlar.



Metered türü aşağıdaki üyeleri ortaya çıkarır:

###  İnşaatçılar
| Oluşturucu| Tanım|
| :- | :- |
| [`__init__(self)`](/cells/python-net/tr/aspose.cells/metered/__init__/#) | Bu sınıfın yeni bir örneğini başlatır.|


###  Yöntemler
| Yöntem| Tanım|
| :- | :- |
| [`set_metered_key(self, public_key, private_key)`](/cells/python-net/tr/aspose.cells/metered/set_metered_key/#str-str) | Ölçülü genel ve özel anahtarları ayarlar.<br/>Eğer tarifeli lisans satın aldıysanız, uygulamayı başlattığınızda API numarasını aramanız gerekiyor, normalde bu yeterlidir.<br/> Ancak, tüketim verilerini yüklemede her zaman başarısız olunursa ve 24 saati aşarsa, lisans değerlendirme durumuna ayarlanacaktır.<br/> Bu gibi durumlarla karşılaşmamak için lisans durumunuzu düzenli olarak kontrol etmeli, değerlendirme durumunda ise API'i tekrar aramalısınız.|
| [`get_consumption_quantity()`](/cells/python-net/tr/aspose.cells/metered/get_consumption_quantity/#) | Tüketim dosyası boyutunu alır|
| [`get_consumption_credit()`](/cells/python-net/tr/aspose.cells/metered/get_consumption_credit/#) | Tüketim kredisi alır|
| [`get_product_name(self)`](/cells/python-net/tr/aspose.cells/metered/get_product_name/#) | Ürün adını alır|
| [`is_metered_licensed()`](/cells/python-net/tr/aspose.cells/metered/is_metered_licensed/#) | Ölçüm cihazının lisanslı olup olmadığını kontrol edin|



###  Örnek

Bu örnekte, ölçülü genel ve özel anahtar ayarlama girişimi yapılacaktır


```python
from aspose.cells import Metered

matered = Metered()
matered.set_metered_key("PublicKey", "PrivateKey")

```

###  Ayrıca bakınız
* modül [`aspose.cells`](..)
