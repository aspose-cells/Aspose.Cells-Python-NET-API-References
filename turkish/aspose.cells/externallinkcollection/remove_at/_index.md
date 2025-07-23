---
title: remove_at yöntemi
second_title: Aspose.Cells for Python via .NET API Referanslar
description:
type: docs
weight: 40
url: /tr/aspose.cells/externallinkcollection/remove_at/
is_root: false
---
##  remove_at(self, index) {#int}
Belirtilen dış bağlantıyı çalışma kitabından kaldırır.



```python

def remove_at(self, index):
    ...
```


| Parametre| Tip| Tanım|
| :- | :- | :- |
| index | int | Kaldırılacak dış bağlantının dizini.|
###  Notlar

Dış bağlantıyı kaldırdığınızda, ona başvuran tüm formüller de kaldırılacaktır çünkü
referanslar geçersiz hale gelir.

##  remove_at(self, index, update_references_as_local) {#int-bool}
Belirtilen dış bağlantıyı çalışma kitabından kaldırır.



```python

def remove_at(self, index, update_references_as_local):
    ...
```


| Parametre| Tip| Tanım|
| :- | :- | :- |
| index | int | Kaldırılacak dış bağlantının dizini.|
| update_references_as_local | bool | Verilen dış bağlantının tüm referanslarını güncel çalışma kitabının referansına güncelleyin.<br/> Bu parametre hakkında daha fazla bilgi edinmek için [`ExternalLinkCollection.clear`](/cells/python-net/tr/aspose.cells/externallinkcollection/clear)'i kontrol edin.|



###  Ayrıca bakınız
* modül [`aspose.cells`](../../)
* sınıf [`ExternalLinkCollection`](/cells/python-net/tr/aspose.cells/externallinkcollection)
