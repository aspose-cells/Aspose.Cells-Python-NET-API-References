---
title: License sınıfı
second_title: Aspose.Cells for Python via .NET API Referanslar
description:
type: docs
weight: 930
url: /tr/aspose.cells/license/
is_root: false
---
##  License sınıfı
Bileşeni lisanslamak için yöntemler sağlar.



License türü aşağıdaki üyeleri ortaya çıkarır:

###  İnşaatçılar
| Oluşturucu| Tanım|
| :- | :- |
| [`__init__(self)`](/cells/python-net/tr/aspose.cells/license/__init__/#) | Bu sınıfın yeni bir örneğini başlatır.|


###  Yöntemler
| Yöntem| Tanım|
| :- | :- |
| [`set_license(self, license_name)`](/cells/python-net/tr/aspose.cells/license/set_license/#str) | Bileşeni lisanslar.|
| [`set_license(self, stream)`](/cells/python-net/tr/aspose.cells/license/set_license/#io.rawiobase) | Bileşeni lisanslar.|



###  Örnek

Bu örnekte, MyLicense.lic adlı bir lisans dosyası bulunmaya çalışılacaktır.
 içeren klasörde


çağrıyı yapan derlemeyi içeren klasördeki bileşen,
giriş derlemesinin klasöründe ve ardından çağıran derlemenin gömülü kaynaklarında.

```python
from aspose.cells import License

license = License()
license.set_license("MyLicense.lic")

```

###  Ayrıca bakınız
* modül [`aspose.cells`](..)
