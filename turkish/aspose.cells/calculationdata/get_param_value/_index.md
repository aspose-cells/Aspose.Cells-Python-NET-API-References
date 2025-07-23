---
title: get_param_value yöntemi
second_title: Aspose.Cells for Python via .NET API Referanslar
description:
type: docs
weight: 30
url: /tr/aspose.cells/calculationdata/get_param_value/
is_root: false
---
##  get_param_value(self, index) {#int}
Verilen dizindeki parametrenin temsil edilen değer nesnesini alır.


###  İadeler

Parametrenin hesaplanan değeri.


```python

def get_param_value(self, index):
    ...
```


| Parametre| Tip| Tanım|
| :- | :- | :- |
| index | int | Parametrenin indeksi (0 tabanlı)|
###  Notlar

Bir parametre için:

Eğer düz değer ise, düz değerin kendisini döndürür;


Eğer referans ise, o zaman ReferredArea nesnesini döndürür;


Eğer birden fazla değere sahip veri kümesine başvuruyorsa, nesne dizisini döndürür;



Hesaplanması gereken bir tür ifade varsa, o zaman değer modunda hesaplanacaktır.
ve genellikle geçerli hücre tabanına göre tek bir değer döndürülür. Örneğin,
D2 formülünün bir parametresi A:A+B:B ise A2+B2 hesaplanacak ve döndürülecektir.
Ancak bu parametre dizi modu olarak belirtilmişse
([`Workbook.update_custom_function_definition`](/cells/python-net/tr/aspose.cells/workbook/update_custom_function_definition) tarafından)
veya [`FormulaParseOptions.custom_function_definition`](/cells/python-net/tr/aspose.cells/formulaparseoptions#custom_function_definition)),
daha sonra öğeleri A1+B1,A2+B2,.... olan bir dizi(nesne[][]) döndürülecektir.


###  Ayrıca bakınız
* modül [`aspose.cells`](../../)
* sınıf [`CalculationData`](/cells/python-net/tr/aspose.cells/calculationdata)
