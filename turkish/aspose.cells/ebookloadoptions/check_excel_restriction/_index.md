---
title: check_excel_restriction mülk
second_title: Aspose.Cells for Python via .NET API Referanslar
description:
type: docs
weight: 90
url: /tr/aspose.cells/ebookloadoptions/check_excel_restriction/
is_root: false
---
##  check_excel_restriction mülk

Kullanıcı hücrelerle ilgili nesneleri değiştirdiğinde excel dosyasının kısıtlamasının kontrol edilip edilmeyeceği.
Örneğin Excel, 32K'dan uzun dize değerinin girilmesine izin vermez.
Cell.PutValue(string) gibi 32K'dan daha uzun bir değer girdiğinizde, bu özellik doğruysa bir Exception alırsınız.
Bu özellik false ise, giriş dizesi değerinizi hücrenin değeri olarak kabul edeceğiz, böylece daha sonra
CSV gibi diğer dosya formatları için dize değerinin tamamının çıktısını alabilirsiniz.
Ancak excel dosya formatı için geçersiz olan bir değer belirlediyseniz,
çalışma kitabını daha sonra excel dosya formatında kaydetmemelisiniz. Aksi takdirde oluşturulan excel dosyasında beklenmeyen hatalar oluşabilir.
###  Tanım:
```python
@property
def check_excel_restriction(self):
    ...
@check_excel_restriction.setter
def check_excel_restriction(self, value):
    ...
```

###  Ayrıca bakınız
* modül [`aspose.cells`](../../)
* sınıf [`EbookLoadOptions`](/cells/python-net/tr/aspose.cells/ebookloadoptions)
