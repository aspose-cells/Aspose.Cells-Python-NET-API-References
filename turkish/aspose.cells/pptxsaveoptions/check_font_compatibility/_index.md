---
title: check_font_compatibility mülk
second_title: Aspose.Cells for Python via .NET API Referanslar
description:
type: docs
weight: 60
url: /tr/aspose.cells/pptxsaveoptions/check_font_compatibility/
is_root: false
---
##  check_font_compatibility mülk

Metindeki her karakter için yazı tipi uyumluluğunun kontrol edilip edilmeyeceğini belirtir.

###  Notlar

Varsayılan değer doğrudur.
Bu özelliğin devre dışı bırakılması daha iyi performans sağlayabilir.
Ancak varsayılan veya belirtilen metin/karakter yazı tipi bunu oluşturmak için kullanılamadığında,
Oluşturulan pdf'te okunamayan karakterler (blok gibi) oluşabilir.
Böyle bir durumda kullanıcının bu özelliği true olarak tutması gerekir, böylece
bunun yerine metni oluşturmak için alternatif yazı tipi aranabilir ve kullanılabilir;
###  Tanım:
```python
@property
def check_font_compatibility(self):
    ...
@check_font_compatibility.setter
def check_font_compatibility(self, value):
    ...
```

###  Ayrıca bakınız
* modül [`aspose.cells`](../../)
* sınıf [`PptxSaveOptions`](/cells/python-net/tr/aspose.cells/pptxsaveoptions)
