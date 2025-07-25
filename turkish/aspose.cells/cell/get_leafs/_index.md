---
title: get_leafs yöntemi
second_title: Aspose.Cells for Python via .NET API Referanslar
description:
type: docs
weight: 160
url: /tr/aspose.cells/cell/get_leafs/
is_root: false
---
##  get_leafs(self) {#}
Bu hücreye doğrudan referans veren ve bu hücre değiştirildiğinde güncellenmesi gereken tüm hücreleri al.


###  İadeler

Tüm bakmakla yükümlü olunan kişileri sayacak Sayım Görevlisi (Cell)


```python

def get_leafs(self):
    ...
```


###  Notlar

NOT: Bu sınıf artık kullanımdan kaldırıldı. Bunun yerine,
Hesaplama zincirindeki tüm bağımlıları almak için lütfen Cell.GetDependentsInCalculation(bool) kullanın.
Bu özellik Mayıs 2022'den itibaren 12 ay sonra kaldırılacaktır.
Aspose yaşadığınız olumsuzluktan dolayı özür diler.

##  get_leafs(self, recursive) {#bool}
Bu hücre değiştirildiğinde güncellenecek tüm hücreleri al.


###  İadeler

Tüm bakmakla yükümlü olunan kişileri sayacak Sayım Görevlisi (Cell)


```python

def get_leafs(self, recursive):
    ...
```


| Parametre| Tip| Tanım|
| :- | :- | :- |
| recursive | bool | Bu hücreye doğrudan başvurmayan yaprakları döndürür mü?<br/> ancak bu hücrenin diğer yapraklarına referans|
###  Notlar

NOT: Bu sınıf artık kullanımdan kaldırıldı. Bunun yerine,
Hesaplama zincirindeki tüm bağımlıları almak için lütfen Cell.GetDependentsInCalculation(bool) kullanın.
Bu özellik Mayıs 2022'den itibaren 12 ay sonra kaldırılacaktır.
Aspose yaşadığınız olumsuzluktan dolayı özür diler.


###  Ayrıca bakınız
* modül [`aspose.cells`](../../)
* sınıf [`Cell`](/cells/python-net/tr/aspose.cells/cell)
