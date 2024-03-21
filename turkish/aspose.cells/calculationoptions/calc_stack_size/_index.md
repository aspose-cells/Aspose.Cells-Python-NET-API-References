---
title: calc_stack_size mülk
second_title: Aspose.Cells for Python via .NET API Referanslar
description:
type: docs
weight: 30
url: /tr/aspose.cells/calculationoptions/calc_stack_size/
is_root: false
---
##  calc_stack_size mülk

Hücreleri yinelemeli olarak hesaplamak için yığın boyutu. Varsayılan değer 200'dür.

###  Notlar

Bağımlılık ağacında çok sayıda hücrenin yinelemeli olarak hesaplanması gerektiğinde,
Hesaplama sürecinde StackOverflowException meydana gelebilir.
Eğer öyleyse, kullanıcı bu özellik için daha küçük bir değer belirtmelidir.
Böyle bir durumda kullanıcının bu özelliğe uygun değeri gerçek formüllere ve verilere göre belirlemesi gerekir.
Ancak çok küçük bir değer, formül hesaplamasında performansın düşmesine ve 2'den küçük bir değere neden olabilir.
başka bir formüle bağlı formülün hesaplanmasını imkansız hale getirecektir. Yani belirtilen değer 2'den küçükse,
2'ye sıfırlanacaktır.
###  Tanım:
```python
@property
def calc_stack_size(self):
    ...
@calc_stack_size.setter
def calc_stack_size(self, value):
    ...
```

###  Ayrıca bakınız
* modül [`aspose.cells`](../../)
* sınıf [`CalculationOptions`](/cells/python-net/tr/aspose.cells/calculationoptions)
