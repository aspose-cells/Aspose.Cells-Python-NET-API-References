---
title: look_at_type mülk
second_title: Aspose.Cells for Python via .NET API Referanslar
description:
type: docs
weight: 90
url: /tr/aspose.cells/findoptions/look_at_type/
is_root: false
---
##  look_at_type mülk

Tipine bak.

###  Notlar

[`FindOptions.regex_key`](/cells/python-net/tr/aspose.cells/findoptions#regex_key) doğru olduğunda ve kullanıcı regex için tam kuralı belirttiğinde,
Performans değerlendirmesi için bu özellik [`LookAtType.ENTIRE_CONTENT`](/cells/python-net/tr/aspose.cells/lookattype#ENTIRE_CONTENT) olarak ayarlanmalıdır.
Aksi takdirde arama anahtarını, belirli türe göre eşleştirilebilmesini sağlamak için yeniden düzenleyeceğiz.
Örneğin, tip [`LookAtType.CONTAINS`](/cells/python-net/tr/aspose.cells/lookattype#CONTAINS) olduğunda (bu, bu özelliğin varsayılan değeridir),
Arama anahtarının başına ve sonuna otomatik olarak joker karakterler ekleyeceğiz.
Bu durumda düzenli ifadeler daha karmaşık hale gelecek ve performans da düşecektir.
###  Tanım:
```python
@property
def look_at_type(self):
    ...
@look_at_type.setter
def look_at_type(self, value):
    ...
```

###  Ayrıca bakınız
* modül [`aspose.cells`](../../)
* sınıf [`FindOptions`](/cells/python-net/tr/aspose.cells/findoptions)
* sınıf [`LookAtType`](/cells/python-net/tr/aspose.cells/lookattype)
