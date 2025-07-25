---
title: empty_formula_value_as_blank mülk
second_title: Aspose.Cells for Python via .NET API Referanslar
description:
type: docs
weight: 40
url: /tr/aspose.cells/deleteblankoptions/empty_formula_value_as_blank/
is_root: false
---
##  empty_formula_value_as_blank mülk

Formül olduğunda ve hesaplanan sonuç null veya boş dize olduğunda bir hücrenin boş olarak alınıp alınmayacağı.
Varsayılan değer false'tur.

###  Notlar

Genellikle kullanıcı, bu özelliği true olarak kullanarak silme işlemi yapmadan önce formüllerin hesaplandığından emin olmalıdır.
Aksi takdirde, [`Cell.formula`](/cells/python-net/tr/aspose.cells/cell#formula) gibi normal API'ler tarafından yeni oluşturulan tüm formüller boş olarak alınacak ve silinebilir.
çünkü hesaplamadan önce hesaplanan sonuçların hepsi boştur.
###  Tanım:
```python
@property
def empty_formula_value_as_blank(self):
    ...
@empty_formula_value_as_blank.setter
def empty_formula_value_as_blank(self, value):
    ...
```

###  Ayrıca bakınız
* modül [`aspose.cells`](../../)
* sınıf [`DeleteBlankOptions`](/cells/python-net/tr/aspose.cells/deleteblankoptions)
