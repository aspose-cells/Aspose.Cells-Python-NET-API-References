---
title: set_license yöntemi
second_title: Aspose.Cells for Python via .NET API Referanslar
description:
type: docs
weight: 20
url: /tr/aspose.cells/license/set_license/
is_root: false
---
##  set_license(license_name) {#str}
Bileşeni lisanslar.



```python
def set_license(self, license_name):
    ...
```


| Parametre| Tip| Tanım|
| :- | :- | :- |
| license_name | str |  |
###  Notlar

Lisansı aşağıdaki konumlarda bulmaya çalışır:


1. Açık yol.


2. Aspose bileşen tertibatını içeren klasör.


3. İstemcinin çağrı derlemesini içeren klasör.


4. Giriş (başlangıç) derlemesini içeren klasör.


5. İstemcinin çağrı derlemesinde katıştırılmış bir kaynak.


**Not:** .NET Kompakt Çerçeve üzerinde, lisansı yalnızca şu konumlarda bulmaya çalışır:


1. Açık yol.


2. İstemcinin çağrı derlemesinde katıştırılmış bir kaynak.
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
Tam veya kısa dosya adı veya katıştırılmış bir kaynağın adı olabilir.
Değerlendirme moduna geçmek için boş bir dize kullanın.


##  set_license(stream) {#io.RawIOBase}
Bileşeni lisanslar.



```python
def set_license(self, stream):
    ...
```


| Parametre| Tip| Tanım|
| :- | :- | :- |
| stream | io.RawIOBase | Lisansı içeren bir akış.|
###  Notlar

Akıştan lisans yüklemek için bu yöntemi kullanın.
###  Örnek


```python
from aspose.cells import License

license = License()
license.set_license(myStream)

```



###  Ayrıca bakınız
* modül [aspose.cells](../../)
* sınıf [License](/cells/python-net/tr/aspose.cells/license)
