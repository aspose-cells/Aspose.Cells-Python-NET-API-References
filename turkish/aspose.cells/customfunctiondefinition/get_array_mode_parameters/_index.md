---
title: get_array_mode_parameters yöntemi
second_title: Aspose.Cells for Python via .NET API Referanslar
description:
type: docs
weight: 20
url: /tr/aspose.cells/customfunctiondefinition/get_array_mode_parameters/
is_root: false
---
##  get_array_mode_parameters {#str}
Verilen özel fonksiyonun dizi modunda hesaplanması gereken parametrelerinin indekslerini alır.


###  İadeler

Belirli bir özel işlev için dizi modunda hesaplanması gereken parametrelerin endeksleri.
Varsayılan değer null'dur, özel işlev için dizi modunda hesaplanması gereken hiçbir parametre yoktur.


```python
def get_array_mode_parameters(self, function_name):
    ...
```


| Parametre| Tip| Tanım|
| :- | :- | :- |
| function_name | str | Özel işlevin adı.|
###  Notlar

Hesaplanması gereken bir ifade için A:A+B:B örnek alınarak:
Genellikle değer modunda mevcut hücre tabanına göre tek bir değere göre hesaplanır.
Ancak dizi modunda A1+B1,A2+B2,A3+B3,...'in tüm değerleri hesaplanacak ve hesaplama için kullanılacaktır.


###  Ayrıca bakınız
* modül [`aspose.cells`](../../)
* sınıf [`CustomFunctionDefinition`](/cells/python-net/tr/aspose.cells/customfunctiondefinition)
