---
title: get_picture yöntemi
second_title: Aspose.Cells for Python via .NET API Referanslar
description:
type: docs
weight: 120
url: /tr/aspose.cells/pagesetup/get_picture/
is_root: false
---
##  get_picture(self, is_header, section) {#bool-int}
Başlık / altbilginin [`Picture`](/cells/python-net/tr/aspose.cells.drawing/picture) nesnesini alır.


###  İadeler

[`Picture`](/cells/python-net/tr/aspose.cells.drawing/picture) nesnesini döndürür.
Resim yoksa null döner.


```python

def get_picture(self, is_header, section):
    ...
```


| Parametre| Tip| Tanım|
| :- | :- | :- |
| is_header | bool | Başlıkta mı yoksa alt bilgide mi olduğunu belirtir.|
| section | int |0: Sol Bölüm, 1: Orta Bölüm, 2: Sağ Bölüm.|


##  get_picture(self, is_first, is_even, is_header, section) {#bool-bool-bool-int}
Başlık / altbilginin [`Picture`](/cells/python-net/tr/aspose.cells.drawing/picture) nesnesini alır.


###  İadeler

[`Picture`](/cells/python-net/tr/aspose.cells.drawing/picture) nesnesini döndürür.


```python

def get_picture(self, is_first, is_even, is_header, section):
    ...
```


| Parametre| Tip| Tanım|
| :- | :- | :- |
| is_first | bool | İlk sayfa üstbilgisi/altbilgisinin resminin alınıp alınmadığını belirtir.|
| is_even | bool | Çift sayfa üstbilgisi/altbilgisinin görüntüsünün alınıp alınmadığını belirtir.|
| is_header | bool | Başlık/altbilgi resminin alınıp alınmadığını belirtir.|
| section | int |0: Sol Bölüm, 1: Orta Bölüm, 2: Sağ Bölüm.|



###  Ayrıca bakınız
* modül [`aspose.cells`](../../)
* sınıf [`PageSetup`](/cells/python-net/tr/aspose.cells/pagesetup)
* sınıf [`Picture`](/cells/python-net/tr/aspose.cells.drawing/picture)
