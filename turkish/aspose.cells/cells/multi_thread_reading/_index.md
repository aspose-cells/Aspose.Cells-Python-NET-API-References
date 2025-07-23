---
title: multi_thread_reading mülk
second_title: Aspose.Cells for Python via .NET API Referanslar
description:
type: docs
weight: 1220
url: /tr/aspose.cells/cells/multi_thread_reading/
is_root: false
---
##  multi_thread_reading mülk

Hücre veri modelinin Çoklu İş Parçacığı okumayı destekleyip desteklemeyeceğini alır veya ayarlar.
Bu özelliğin varsayılan değeri false'tur.

###  Notlar

Bu koleksiyondaki Row/Cell nesnelerini aynı anda okumak için birden fazla iş parçacığı varsa,
Bu özellik true olarak ayarlanmalıdır, aksi takdirde beklenmeyen sonuçlar ortaya çıkabilir.
Çoklu İş Parçacığı okumayı desteklemek, bu koleksiyondan Row/Cell nesnelerine erişim performansını düşürebilir.
Lütfen dikkat edin, bazı özellikler Çoklu İş Parçacığı okumayı destekleyemeyebilir.
örneğin değerleri biçimlendirme ([`Cell.string_value`](/cells/python-net/tr/aspose.cells/cell#string_value), [`Cell.display_string_value`](/cells/python-net/tr/aspose.cells/cell#display_string_value), .vb.).
Yani bu özellik true olarak ayarlanmış olsa bile, bu API'ler Multi-Thread okuma için beklenmeyen sonuçlar verebilir.
###  Tanım:
```python
@property
def multi_thread_reading(self):
    ...
@multi_thread_reading.setter
def multi_thread_reading(self, value):
    ...
```

###  Ayrıca bakınız
* modül [`aspose.cells`](../../)
* sınıf [`Cells`](/cells/python-net/tr/aspose.cells/cells)
