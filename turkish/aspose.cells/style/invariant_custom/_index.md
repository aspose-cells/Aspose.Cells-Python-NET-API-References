---
title: invariant_custom mülk
second_title: Aspose.Cells for Python via .NET API Referanslar
description:
type: docs
weight: 260
url: /tr/aspose.cells/style/invariant_custom/
is_root: false
---
##  invariant_custom mülk

Sayı biçimi için kültürden bağımsız desen dizesini alır.
Bu nesne için herhangi bir sayı biçimi ayarlanmamışsa, null döndürülür.
Sayı biçimi yerleşik ise yerleşik sayıya karşılık gelen desen dizesi döndürülecektir.

###  Notlar

Yerleşik sayı biçimleri için, döndürülen desen içeriği hala kültüre bağlıdır.
örneğin, bazı yerel ayarlar için "a/g/y" değerini döndürürken, bazı diğer yerel ayarlar için "g/a/y" değerini döndürür.
[`Style.culture_custom`](/cells/python-net/tr/aspose.cells/style#culture_custom)'den farkı (kültürden bağımsızlığın anlamı da budur):
biçim belirteçleri ve ayırıcılar standart olarak tutulur, örneğin '/' her zaman tarih-saat ayırıcısı olarak kullanılır
ve "y" her zaman belirli bir yerel için hangi özel karakter kullanılırsa kullanılsın "yıl" kısmı olarak kullanılacaktır.
###  Tanım:
```python
@property
def invariant_custom(self):
    ...
```

###  Ayrıca bakınız
* modül [`aspose.cells`](../../)
* sınıf [`Style`](/cells/python-net/tr/aspose.cells/style)
