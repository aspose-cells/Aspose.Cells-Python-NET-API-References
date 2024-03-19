---
title: multi_thread_reading mülk
second_title: Aspose.Cells for Python via .NET API Referanslar
description:
type: docs
weight: 1190
url: /tr/aspose.cells/cells/multi_thread_reading/
is_root: false
---
##  multi_thread_reading mülk

Hücre veri modelinin Multi-Thread okumayı desteklemesi gerekip gerekmediğini alır veya ayarlar.
Bu özelliğin varsayılan değeri false'tur.

###  Notlar

Bu koleksiyondaki Row/Cell nesnelerini aynı anda okumak için birden fazla iş parçacığı varsa,
bu özellik true olarak ayarlanmalıdır, aksi takdirde beklenmeyen sonuçlar üretilebilir.
Çoklu İş Parçacığı okumayı desteklemek, bu koleksiyondaki Row/Cell nesnelerine erişim performansını düşürebilir.
Bazı özelliklerin Çoklu İş Parçacığı okumayı destekleyemeyeceğini lütfen unutmayın.
biçimlendirme değerleri gibi ([`Cell.string_value`](/cells/python-net/tr/aspose.cells/cell#string_value), [`Cell.display_string_value`](/cells/python-net/tr/aspose.cells/cell#display_string_value), .vb.'ye göre).
Dolayısıyla, bu özellik true olarak ayarlanmış olsa bile bu API'ler, Çoklu İş Parçacığı okuması için yine de beklenmeyen sonuçlar verebilir.
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
