---
title: check_excel_restriction mülk
second_title: Aspose.Cells for Python via .NET API Referanslar
description:
type: docs
weight: 70
url: /tr/aspose.cells/xmlloadoptions/check_excel_restriction/
is_root: false
---
##  check_excel_restriction mülk

Kullanıcı hücrelerle ilgili nesneleri değiştirdiğinde Excel dosyasının kısıtlamasını kontrol edin.
Örneğin, Excel 32K'dan uzun dize değerlerinin girilmesine izin vermez.
Cell.PutValue(string) gibi 32K'dan uzun bir değer girdiğinizde, bu özellik true ise bir Exception alırsınız.
Bu özellik yanlışsa, giriş dizesi değerinizi hücrenin değeri olarak kabul edeceğiz, böylece daha sonra
CSV gibi diğer dosya biçimleri için tam dize değerini çıktı olarak alabilirsiniz.
Ancak, Excel dosya biçimi için geçersiz olan bu tür bir değer ayarladıysanız,
Çalışma kitabını daha sonra Excel dosya formatında kaydetmemelisiniz. Aksi takdirde, oluşturulan Excel dosyasında beklenmedik hatalar oluşabilir.
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
* sınıf [`XmlLoadOptions`](/cells/python-net/tr/aspose.cells/xmlloadoptions)
