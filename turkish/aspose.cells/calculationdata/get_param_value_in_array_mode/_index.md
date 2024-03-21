---
title: get_param_value_in_array_mode yöntemi
second_title: Aspose.Cells for Python via .NET API Referanslar
description:
type: docs
weight: 40
url: /tr/aspose.cells/calculationdata/get_param_value_in_array_mode/
is_root: false
---
##  get_param_value_in_array_mode {#int-int-int}
Verilen dizindeki parametrenin değerini/değerlerini alır.
Parametre hesaplanması gereken bir tür ifade ise,
daha sonra dizi modunda hesaplanacaktır.


###  İadeler

Belirtilen parametre tarafından temsil edilen tüm öğeleri içeren bir dizi.


```python
def get_param_value_in_array_mode(self, index, max_row_count, max_column_count):
    ...
```


| Parametre| Tip| Tanım|
| :- | :- | :- |
| index | int | Parametrenin dizini (0 tabanlı)|
| max_row_count | int | Döndürülen dizi için satır sayısı sınırı.<br/> Pozitif değilse veya gerçek satır sayısından büyükse gerçek satır sayısı kullanılacaktır.|
| max_column_count | int | Döndürülen dizi için sütun sayısı sınırı.<br/> Pozitif değilse veya gerçek satır sayısından büyükse gerçek sütun sayısı kullanılacaktır.|
###  Notlar

Hesaplanması gereken bir ifade için A:A+B:B örnek alınarak:
Değer modunda mevcut hücre tabanına göre tek bir değere göre hesaplanacaktır.
Ancak dizi modunda, A1+B1,A2+B2,A3+B3,...'in tüm değerleri hesaplanacak ve döndürülen diziyi oluşturmak için kullanılacaktır.
Ve bu tür bir durum için satır/sütun sayısı için sınır belirlemek daha iyidir
([`Cells.max_data_row`](/cells/python-net/tr/aspose.cells/cells#max_data_row) ve [`Cells.max_data_column`](/cells/python-net/tr/aspose.cells/cells#max_data_column)’e göre olduğu gibi),
aksi takdirde döndürülen büyük dizi, büyük miktarda gereksiz veriyle birlikte bellek maliyetini artırabilir.


###  Ayrıca bakınız
* modül [`aspose.cells`](../../)
* sınıf [`CalculationData`](/cells/python-net/tr/aspose.cells/calculationdata)
