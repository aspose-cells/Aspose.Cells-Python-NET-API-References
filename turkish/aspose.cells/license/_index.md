---
title: License sınıfı
second_title: Aspose.Cells for Python via .NET API Referanslar
description:
type: docs
weight: 980
url: /tr/aspose.cells/license/
is_root: false
---
##  License sınıfı
Bileşeni lisanslamak için yöntemler sağlar.



License türü aşağıdaki üyeleri gösterir:

###  İnşaatçılar
| Yapıcı| Tanım|
| :- | :- |
| [License()](/cells/python-net/tr/aspose.cells/license/__init__/#) | Bu sınıfın yeni bir örneğini başlatır.|


###  Yöntemler
| Yöntem| Tanım|
| :- | :- |
| [set_license(license_name)](/cells/python-net/tr/aspose.cells/license/set_license/#str) | Bileşeni lisanslar.|
| [set_license(stream)](/cells/python-net/tr/aspose.cells/license/set_license/#io.RawIOBase) | Bileşeni lisanslar.|



###  Örnek

Bu örnekte, MyLicense.lic adlı bir lisans dosyası bulunmaya çalışılacaktır.
 içeren klasörde


çağıran derlemeyi içeren klasördeki bileşen,
giriş derlemesinin klasöründe ve ardından çağıran derlemenin katıştırılmış kaynaklarında.

```python
from aspose.cells import License

license = License()
license.set_license("MyLicense.lic")

```

###  Ayrıca bakınız
* modül [aspose.cells](..)
