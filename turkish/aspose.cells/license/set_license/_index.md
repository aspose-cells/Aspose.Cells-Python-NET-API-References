---
title: set_license yöntemi
second_title: Aspose.Cells for Python via .NET API Referanslar
description:
type: docs
weight: 20
url: /tr/aspose.cells/license/set_license/
is_root: false
---
##  set_license(self, license_name) {#str}
Bileşeni lisanslar.



```python

def set_license(self, license_name):
    ...
```


| Parametre| Tip| Tanım|
| :- | :- | :- |
| license_name | str |  |
###  Notlar

Aşağıdaki konumlarda lisansı bulmaya çalışır:


1. Açık yol.


2. Aspose bileşen montajını içeren klasör.


3. İstemcinin çağırdığı derlemeyi içeren klasör.


4. Giriş (başlangıç) derlemesini içeren klasör.


5. İstemcinin çağıran derlemesinde gömülü bir kaynak.


**Not:**.NET Compact Framework'te, yalnızca şu konumlarda lisansı bulmaya çalışır:


1. Açık yol.


2. İstemcinin çağıran derlemesinde gömülü bir kaynak.
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
Tam veya kısa dosya adı veya gömülü bir kaynağın adı olabilir.
Değerlendirme moduna geçmek için boş bir dize kullanın.


##  set_license(self, stream) {#io.RawIOBase}
Bileşeni lisanslar.



```python

def set_license(self, stream):
    ...
```


| Parametre| Tip| Tanım|
| :- | :- | :- |
| stream | io.RawIOBase |Lisansı içeren bir akış.|
###  Notlar

Bir akıştan lisans yüklemek için bu yöntemi kullanın.
###  Örnek


```python
from aspose.cells import License

license = License()
license.set_license(myStream)

```



###  Ayrıca bakınız
* modül [`aspose.cells`](../../)
* sınıf [`License`](/cells/python-net/tr/aspose.cells/license)
