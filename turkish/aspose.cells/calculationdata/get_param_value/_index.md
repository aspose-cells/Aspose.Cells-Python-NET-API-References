---
title: get_param_value yöntemi
second_title: Aspose.Cells for Python via .NET API Referanslar
description:
type: docs
weight: 30
url: /tr/aspose.cells/calculationdata/get_param_value/
is_root: false
---
##  get_param_value {#int}
Verilen dizindeki parametrenin temsil edilen değer nesnesini alır.


###  İadeler

Parametrenin hesaplanan değeri.


```python
def get_param_value(self, index):
    ...
```


| Parametre| Tip| Tanım|
| :- | :- | :- |
| index | int | Parametrenin dizini (0 tabanlı)|
###  Notlar

Bir parametre için:

Düz değer ise düz değerin kendisini döndürür;


Referans ise, ReferredArea nesnesini döndürür;


Birden çok değere sahip veri kümesine/kümelerine başvuruyorsa, nesnelerin dizisini döndürür;



Hesaplanması gereken bir tür ifade ise değer modunda hesaplanacaktır.
ve genellikle geçerli hücre tabanına göre tek bir değer döndürülür. Örneğin,
D2 formülünün bir parametresi A:A+B:B ise A2+B2 hesaplanacak ve döndürülecektir.
Ancak bu parametre dizi modu olarak belirtilmişse
([`Workbook.update_custom_function_definition`](/cells/python-net/tr/aspose.cells/workbook/update_custom_function_definition) tarafından
veya [`FormulaParseOptions.custom_function_definition`](/cells/python-net/tr/aspose.cells/formulaparseoptions#custom_function_definition)),
daha sonra öğeleri A1+B1,A2+B2,... olan bir dizi(nesne[][]) döndürülecektir.


###  Ayrıca bakınız
* modül [`aspose.cells`](../../)
* sınıf [`CalculationData`](/cells/python-net/tr/aspose.cells/calculationdata)
