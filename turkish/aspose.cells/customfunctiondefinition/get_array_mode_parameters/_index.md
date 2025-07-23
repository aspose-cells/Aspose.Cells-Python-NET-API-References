---
title: get_array_mode_parameters yöntemi
second_title: Aspose.Cells for Python via .NET API Referanslar
description:
type: docs
weight: 20
url: /tr/aspose.cells/customfunctiondefinition/get_array_mode_parameters/
is_root: false
---
##  get_array_mode_parameters(self, function_name) {#str}
Dizi modunda hesaplanması gereken verilen özel fonksiyon parametrelerinin indekslerini alır.


###  İadeler

Verilen özel fonksiyon için dizi modunda hesaplanması gereken parametrelerin indeksleri.
Varsayılan değer null'dır, özel fonksiyon için dizi modunda hesaplanması gereken bir parametre yoktur.


```python

def get_array_mode_parameters(self, function_name):
    ...
```


| Parametre| Tip| Tanım|
| :- | :- | :- |
| function_name | str | Özel fonksiyonun adı.|
###  Notlar

Hesaplanması gereken bir ifade için, A:A+B:B örneğini ele alalım:
Genellikle değer modunda, geçerli hücre tabanına göre tek bir değer hesaplanacaktır.
Ancak dizi modunda A1+B1,A2+B2,A3+B3,... değerlerinin tamamı hesaplanacak ve hesaplamada kullanılacaktır.


###  Ayrıca bakınız
* modül [`aspose.cells`](../../)
* sınıf [`CustomFunctionDefinition`](/cells/python-net/tr/aspose.cells/customfunctiondefinition)
