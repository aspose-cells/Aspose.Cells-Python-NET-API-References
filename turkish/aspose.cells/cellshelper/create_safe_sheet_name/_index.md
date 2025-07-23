---
title: create_safe_sheet_name yöntemi
second_title: Aspose.Cells for Python via .NET API Referanslar
description:
type: docs
weight: 90
url: /tr/aspose.cells/cellshelper/create_safe_sheet_name/
is_root: false
---
##  create_safe_sheet_name(, ad_teklifi){#str}
Verilen sayfa adını kontrol eder ve gerektiğinde geçerli bir sayfa oluşturur.
Eğer verilen sayfa adı excel sayfa adı kurallarına uyuyorsa geri döndür.
Aksi takdirde uzunluk sınırı aşarsa dize kesilecektir
ve geçersiz karakterler ' ' ile değiştirilecek, ardından yeniden oluşturulan dize değeri döndürülecektir.


###  İadeler




```python

@staticmethod
def create_safe_sheet_name(name_proposal):
    ...
```


| Parametre| Tip| Tanım|
| :- | :- | :- |
| name_proposal | str | kullanılacak sayfa adı|


##  create_safe_sheet_name(, ad_teklifi, değiştir_karakteri){#str-char}
Verilen sayfa adını kontrol eder ve gerektiğinde geçerli bir sayfa oluşturur.
Eğer verilen sayfa adı excel sayfa adı kurallarına uyuyorsa geri döndür.
Aksi takdirde uzunluk sınırı aşarsa dize kesilecektir
ve geçersiz karakterler verilen karakterle değiştirilecek, ardından yeniden oluşturulan dize değeri döndürülecektir.


###  İadeler




```python

@staticmethod
def create_safe_sheet_name(name_proposal, replace_char):
    ...
```


| Parametre| Tip| Tanım|
| :- | :- | :- |
| name_proposal | str | kullanılacak sayfa adı|
| replace_char | char | verilen sayfa adında geçersiz karakterlerin yerine kullanılacak karakter|



###  Ayrıca bakınız
* modül [`aspose.cells`](../../)
* sınıf [`CellsHelper`](/cells/python-net/tr/aspose.cells/cellshelper)
