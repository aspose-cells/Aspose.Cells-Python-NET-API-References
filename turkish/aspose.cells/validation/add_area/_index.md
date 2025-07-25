---
title: add_area yöntemi
second_title: Aspose.Cells for Python via .NET API Referanslar
description:
type: docs
weight: 20
url: /tr/aspose.cells/validation/add_area/
is_root: false
---
##  add_area(self, cell_area) {#aspose.cells.CellArea}
Doğrulamayı alana uygular.



```python

def add_area(self, cell_area):
    ...
```


| Parametre| Tip| Tanım|
| :- | :- | :- |
| cell_area | [`CellArea`](/cells/python-net/tr/aspose.cells/cellarea) | Alan.|
###  Notlar

[`Validation.add_area`](/cells/python-net/tr/aspose.cells/validation/add_area) kullanmaya eşdeğerdir
kesişim ve kenar kontrolü ile.

##  add_area(self, cell_area, check_intersection, check_edge) {#aspose.cells.CellArea-bool-bool}
Doğrulamayı alana uygular.



```python

def add_area(self, cell_area, check_intersection, check_edge):
    ...
```


| Parametre| Tip| Tanım|
| :- | :- | :- |
| cell_area | [`CellArea`](/cells/python-net/tr/aspose.cells/cellarea) | Alan.|
| check_intersection | bool | Verilen alanın mevcut doğrulama alanlarıyla kesişimini kontrol edin.<br/>Belirli bir alanda (veya bir bölümünde) bir doğrulama uygulanmışsa,<br/>daha sonra mevcut doğrulamanın öncelikle verilen alandan kaldırılması gerekir.<br/>Aksi takdirde oluşturulan Doğrulamalarda bozulmalar meydana gelebilir.<br/>Kullanıcı eklenen alanın mevcut herhangi bir alanla kesişmediğinden eminse,<br/> Bu parametre performans değerlendirmesi için false olarak ayarlanabilir.|
| check_edge | bool | Bu doğrulamanın uygulandığı alanların kenarını kontrol edin.<br/>Doğrulamanın dahili ayarları, uygulanan aralıklarından sol üsttekine bağlıdır.<br/>yani verilen alan uygulanan aralıkların yeni sol üst alanı haline gelecekse,<br/>İç ayarlar değiştirilmeli ve yeniden kurulmalıdır, aksi takdirde beklenmeyen sonuçlar ortaya çıkabilir.<br/>Kullanıcı eklenen alanın sol üstteki alan olmadığından eminse,<br/> Bu parametre performans değerlendirmesi için false olarak ayarlanabilir.|
###  Notlar

Bu yöntemde verilen alandaki tüm eski doğrulamaları kaldıracağız.
Validation'ın uyguladığı aralıklardan en sol üstteki için, öncelikle StartRow'u en küçüktür,
ikinci olarak StartColumn'u aynı en küçük StartRow'a sahip olan alanların en küçüğüdür.


###  Ayrıca bakınız
* modül [`aspose.cells`](../../)
* sınıf [`Validation`](/cells/python-net/tr/aspose.cells/validation)
