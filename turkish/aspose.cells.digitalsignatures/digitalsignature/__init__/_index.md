---
title: DigitalSignature yapıcı
second_title: Aspose.Cells for Python via .NET API Referanslar
description:
type: docs
weight: 10
url: /tr/aspose.cells.digitalsignatures/digitalsignature/__init__/
is_root: false
---
##  \_\_init\_\_(self, sertifika, yorumlar, imza_zamanı){#System.Security.Cryptography.X509Certificates.X509Certificate2-str-DateTime}
digitalSignature'ın kurucusu. .Net uygulamasını kullanır.



```python

def __init__(self, certificate, comments, sign_time):
    ...
```


| Parametre| Tip| Tanım|
| :- | :- | :- |
| certificate | System.Security.Cryptography.X509Certificates.X509Certificate2 | Belgeyi imzalamak için kullanılan sertifika nesnesi.|
| comments | str | İmzalamanın amacı.|
| sign_time | DateTime | Belgenin imzalandığı UTC saati.|


## \_\_init\_\_(self, ham_veri, parola, yorumlar, imza_süresi){#bytes-str-str-DateTime}
digitalSignature'ın kurucusu. Bouncy Castle uygulamasını kullanır.



```python

def __init__(self, raw_data, password, comments, sign_time):
    ...
```


| Parametre| Tip| Tanım|
| :- | :- | :- |
| raw_data | bytes | X.509 sertifikasından veri içeren bir bayt dizisi.|
| password | str | X.509 sertifika verilerine erişmek için gereken şifre.|
| comments | str | İmzalamanın amacı.|
| sign_time | DateTime | Belgenin imzalandığı UTC saati.|



###  Ayrıca bakınız
* modül [`aspose.cells.digitalsignatures`](../../)
* sınıf [`DigitalSignature`](/cells/python-net/tr/aspose.cells.digitalsignatures/digitalsignature)
