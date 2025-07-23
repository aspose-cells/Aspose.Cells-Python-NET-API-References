---
title: start_access_cache yöntemi
second_title: Aspose.Cells for Python via .NET API Referanslar
description:
type: docs
weight: 400
url: /tr/aspose.cells/workbook/start_access_cache/
is_root: false
---
##  start_access_cache(self, opts) {#aspose.cells.AccessCacheOptions}
Verilere erişmek için önbellekleri kullanan oturumu başlatır.



```python

def start_access_cache(self, opts):
    ...
```


| Parametre| Tip| Tanım|
| :- | :- | :- |
| opts | [`AccessCacheOptions`](/cells/python-net/tr/aspose.cells/accesscacheoptions) | veri erişim seçenekleri|
###  Notlar

Belirtilen veri erişiminin önbelleği, çalışma sayfasındaki bazı veri modellerinin "salt okunur" olmasını gerektiriyorsa,
daha sonra bu çalışma kitabındaki her çalışma sayfasındaki ilgili veri modelleri "salt okunur" olarak alınacaktır
ve kullanıcı bunların hiçbirini değiştirmemelidir.


Verilere erişim tamamlandıktan sonra [`Workbook.close_access_cache`](/cells/python-net/tr/aspose.cells/workbook/close_access_cache)
Tüm önbellekleri temizlemek ve normal erişim modunu kurtarmak için aynı seçeneklerle çağrılabilir.


###  Ayrıca bakınız
* modül [`aspose.cells`](../../)
* sınıf [`Workbook`](/cells/python-net/tr/aspose.cells/workbook)
