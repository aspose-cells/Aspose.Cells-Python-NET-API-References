---
title: start_access_cache yöntemi
second_title: Aspose.Cells for Python via .NET API Referanslar
description:
type: docs
weight: 380
url: /tr/aspose.cells/workbook/start_access_cache/
is_root: false
---
##  start_access_cache(opts) {#AccessCacheOptions}
Verilere erişmek için önbellekleri kullanan oturumu başlatır.



```python
def start_access_cache(self, opts):
    ...
```


| Parametre| Tip| Tanım|
| :- | :- | :- |
| opts | [AccessCacheOptions](/cells/python-net/tr/aspose.cells/accesscacheoptions) | veri erişim seçenekleri|
###  Notlar

Belirtilen veri erişiminin önbelleği, çalışma sayfasındaki bazı veri modellerinin "salt okunur" olmasını gerektiriyorsa,
daha sonra bu çalışma kitabındaki her çalışma sayfasındaki karşılık gelen veri modelleri "salt okunur" olarak alınacaktır.
ve kullanıcı bunların hiçbirini değiştirmemelidir.


Verilere erişimi bitirdikten sonra [Workbook.close_access_cache(opts)](/cells/python-net/tr/aspose.cells/workbook/close_access_cache)
tüm önbellekleri temizlemek ve normal erişim modunu kurtarmak için aynı seçeneklerle çağrılabilir.


###  Ayrıca bakınız
* modül [aspose.cells](../../)
* sınıf [Workbook](/cells/python-net/tr/aspose.cells/workbook)
