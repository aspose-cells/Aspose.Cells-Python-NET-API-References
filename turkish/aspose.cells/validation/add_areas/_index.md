---
title: add_areas yöntemi
second_title: Aspose.Cells for Python via .NET API Referanslar
description:
type: docs
weight: 30
url: /tr/aspose.cells/validation/add_areas/
is_root: false
---
##  add_areas(self, areas, check_intersection, check_edge) {#list-bool-bool}
Doğrulamayı verilen alanlara uygular.



```python

def add_areas(self, areas, check_intersection, check_edge):
    ...
```


| Parametre| Tip| Tanım|
| :- | :- | :- |
| areas | list | Alanlar.|
| check_intersection | bool | Verilen alanın mevcut doğrulama alanlarıyla kesişimini kontrol edin.<br/>Belirli bir alanda (veya bir bölümünde) bir doğrulama uygulanmışsa,<br/>daha sonra mevcut doğrulamanın öncelikle verilen alandan kaldırılması gerekir.<br/>Aksi takdirde oluşturulan Doğrulamalarda bozulmalar meydana gelebilir.<br/>Kullanıcı eklenen tüm alanların mevcut herhangi bir alanla kesişmediğinden eminse,<br/> Bu parametre performans değerlendirmesi için false olarak ayarlanabilir.|
| check_edge | bool | Bu doğrulamanın uygulandığı alanların kenarını kontrol edin.<br/>Doğrulamanın dahili ayarları, uygulanan aralıklarından sol üsttekine bağlıdır.<br/>yani verilen alanlardan biri uygulanan aralıkların yeni sol üst alanı haline gelirse,<br/>İç ayarlar değiştirilmeli ve yeniden kurulmalıdır, aksi takdirde beklenmeyen sonuçlar ortaya çıkabilir.<br/>Kullanıcı eklenen alanlardan hiçbirinin sol üstte olmadığından eminse,<br/> Bu parametre performans değerlendirmesi için false olarak ayarlanabilir.|
###  Notlar

Bu yöntemde verilen alandaki tüm eski doğrulamaları kaldıracağız.
Validation'ın uyguladığı aralıklardan en sol üstteki için, öncelikle StartRow'u en küçüktür,
ikinci olarak StartColumn'u aynı en küçük StartRow'a sahip olan alanların en küçüğüdür.


###  Ayrıca bakınız
* modül [`aspose.cells`](../../)
* sınıf [`Validation`](/cells/python-net/tr/aspose.cells/validation)
