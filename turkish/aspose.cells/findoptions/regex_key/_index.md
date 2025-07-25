---
title: regex_key mülk
second_title: Aspose.Cells for Python via .NET API Referanslar
description:
type: docs
weight: 110
url: /tr/aspose.cells/findoptions/regex_key/
is_root: false
---
##  regex_key mülk

Aranan anahtarın regex olup olmadığını belirtir.
Eğer doğruysa aranan anahtar regex olarak alınacak ve ayrıştırılacaktır.
Aksi takdirde anahtar ms excel'deki kurallara göre ayrıştırılacaktır.

###  Notlar

Arama anahtarı regex olarak belirtilmiş olsa bile,
belirtilen [`FindOptions.look_at_type`](/cells/python-net/tr/aspose.cells/findoptions#look_at_type)'e göre yeniden düzenlenebilir.
Örneğin, tip [`LookAtType.CONTAINS`](/cells/python-net/tr/aspose.cells/lookattype#CONTAINS) olduğunda (bu, bu seçeneğin varsayılan değeridir),
Eşleşmenin sağlanması için arama anahtarının başına ve sonuna otomatik olarak joker karakterler eklenecektir.
"içerir" olarak işaretlendi. Bu durumda, düzenli ifadeler daha karmaşık hale gelecektir.
ve performans da düşecektir.
Bu nedenle, performans değerlendirmesi için, kullanıcı regex için tam kuralı belirtmişse, o zaman buna gerek yoktur.
[`FindOptions.look_at_type`](/cells/python-net/tr/aspose.cells/findoptions#look_at_type)'i ek kısıtlama olarak kullanın ve kullanıcı bunu [`LookAtType.ENTIRE_CONTENT`](/cells/python-net/tr/aspose.cells/lookattype#ENTIRE_CONTENT) olarak ayarlayabilir
daha iyi performans elde etmek için.
###  Tanım:
```python
@property
def regex_key(self):
    ...
@regex_key.setter
def regex_key(self, value):
    ...
```

###  Ayrıca bakınız
* modül [`aspose.cells`](../../)
* sınıf [`FindOptions`](/cells/python-net/tr/aspose.cells/findoptions)
