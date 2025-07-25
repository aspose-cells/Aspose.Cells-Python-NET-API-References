---
title: calculated_value mülk
second_title: Aspose.Cells for Python via .NET API Referanslar
description:
type: docs
weight: 60
url: /tr/aspose.cells/calculationdata/calculated_value/
is_root: false
---
##  calculated_value mülk

Bu fonksiyon için hesaplanan değeri alır veya ayarlar.

###  Notlar

Kullanıcı, motorun desteklediği işlevler için bu özelliği kendi özel hesaplama motorunda ayarlamalıdır.
ve bu özellik daha sonra alındığında ayarlanan değer döndürülecektir.
Ayarlanan değer [`Cell.value`](/cells/python-net/tr/aspose.cells/cell#value)'in olası tiplerinden olabilir,
veya bu tür değerlerin dizisi, ya da bir Aralık, Ad, Referans Alanı.
Bu özelliğin değerini ayarlamadan önce alınması, fonksiyonun hesaplanmasına neden olur
Aspose.Cells varsayılan hesaplama motoru ile ve ardından hesaplanan değer
döndürülür (genellikle kullanıcı tanımlı fonksiyonlar için #NAME? olmalıdır).
###  Tanım:
```python
@property
def calculated_value(self):
    ...
@calculated_value.setter
def calculated_value(self, value):
    ...
```

###  Ayrıca bakınız
* modül [`aspose.cells`](../../)
* sınıf [`CalculationData`](/cells/python-net/tr/aspose.cells/calculationdata)
