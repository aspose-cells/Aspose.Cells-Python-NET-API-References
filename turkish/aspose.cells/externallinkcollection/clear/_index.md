---
title: clear yöntemi
second_title: Aspose.Cells for Python via .NET API Referanslar
description:
type: docs
weight: 30
url: /tr/aspose.cells/externallinkcollection/clear/
is_root: false
---
##  clear(self) {#}
Tüm harici bağlantıları kaldırır.



```python

def clear(self):
    ...
```


###  Notlar

Dış bağlantıları kaldırdığınızda, bunlara başvuran tüm formüller de kaldırılacaktır çünkü
referanslar geçersiz hale gelir.

##  clear(self, update_references_as_local) {#bool}
Tüm harici bağlantıları kaldırır.



```python

def clear(self, update_references_as_local):
    ...
```


| Parametre| Tip| Tanım|
| :- | :- | :- |
| update_references_as_local | bool |Formüllerdeki tüm dış bağlantı referanslarını geçerli çalışma kitabının kendi referanslarına güncelleyin.|
###  Notlar

Referansların güncellenmesi gerekiyorsa, formüllerdeki harici bağlantıların referansları
Mümkün olduğunda güncel çalışma kitabına geçilecektir.
Örneğin, bir hücrenin orijinal formülü "='externalsource.xlam'!customfunction()" şeklindedir,
dış bağlantıları kaldırdıktan sonra formül "=customfunction()" haline gelecektir;
Orijinal formül "='[externalsource.xlam]Sheet1'!$A$1" olduğunda,
Mevcut çalışma kitabında "Sheet1" adında bir sayfa olup olmadığına göre:
eğer doğruysa, formül "=Sheet1!$A$1" haline gelecektir;
Eğer yanlışsa formül "=#REF!$A$1" haline gelecektir.

Referansların güncellenmesi gerekmiyorsa, harici bağlantılara referans veren tüm formüller
o referanslar geçersiz hale geldiğinden kaldırılacaktır.


###  Ayrıca bakınız
* modül [`aspose.cells`](../../)
* sınıf [`ExternalLinkCollection`](/cells/python-net/tr/aspose.cells/externallinkcollection)
