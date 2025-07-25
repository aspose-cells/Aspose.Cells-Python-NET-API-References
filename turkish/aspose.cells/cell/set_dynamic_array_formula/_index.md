---
title: set_dynamic_array_formula yöntemi
second_title: Aspose.Cells for Python via .NET API Referanslar
description:
type: docs
weight: 340
url: /tr/aspose.cells/cell/set_dynamic_array_formula/
is_root: false
---
##  set_dynamic_array_formula(self, array_formula, options, calculate_value) {#str-aspose.cells.FormulaParseOptions-bool}
Dinamik dizi formülü ayarlar ve mümkünse formülün komşu hücrelere yayılmasını sağlar.


###  İadeler

formülün yayılması gereken aralık.


```python

def set_dynamic_array_formula(self, array_formula, options, calculate_value):
    ...
```


| Parametre| Tip| Tanım|
| :- | :- | :- |
| array_formula | str | formül ifadesi|
| options | [`FormulaParseOptions`](/cells/python-net/tr/aspose.cells/formulaparseoptions) | Formülü ayrıştırma seçenekleri.<br/> "Ayrıştır" seçeneği göz ardı edilecek ve formül her zaman hemen ayrıştırılacaktır|
| calculate_value | bool | Bu dinamik dizi formülünü dökülmüş aralıktaki hücreler için hesaplayın.|
###  Notlar

döndürülen aralık, bu dinamik dizi formülünün içine döküldüğü gerçek aralıkla aynı olmayabilir.
Aralıkta boş olmayan hücreler varsa, formül yalnızca geçerli hücre için ayarlanacak ve "#SPILL!" olarak işaretlenecektir.
Ama bu tür durumlar için yine de formülün yayılacağı tüm aralığı geri döndürüyoruz.

##  set_dynamic_array_formula(self, array_formula, options, values, calculate_range, calculate_value) {#str-aspose.cells.FormulaParseOptions-list-bool-bool}
Dinamik dizi formülü ayarlar ve mümkünse formülün komşu hücrelere yayılmasını sağlar.


###  İadeler

formülün yayılması gereken aralık.


```python

def set_dynamic_array_formula(self, array_formula, options, values, calculate_range, calculate_value):
    ...
```


| Parametre| Tip| Tanım|
| :- | :- | :- |
| array_formula | str | formül ifadesi|
| options | [`FormulaParseOptions`](/cells/python-net/tr/aspose.cells/formulaparseoptions) | Formülü ayrıştırma seçenekleri.<br/> "Ayrıştır" seçeneği göz ardı edilecek ve formül her zaman hemen ayrıştırılacaktır|
| values | list |Verilen dinamik dizi formülüne sahip hücreler için değerler (hesaplanan sonuçlar)|
| calculate_range | bool | Bu dinamik dizi formülü için dökülen aralığı hesaplayın.<br/>"Values" parametresi boş değilse ve bu bayrak yanlışsa,<br/> Daha sonra dökülen aralığın yüksekliği values.Length ve width values[0].Length olacaktır.|
| calculate_value | bool | "değerler" boş olduğunda, dökülen aralıktaki hücreler için bu dinamik dizi formülünün hesaplanması<br/> veya bir hücrenin "değerler"indeki karşılık gelen öğe boştur.|
###  Notlar

döndürülen aralık, bu dinamik dizi formülünün içine döküldüğü gerçek aralıkla aynı olmayabilir.
Aralıkta boş olmayan hücreler varsa, formül yalnızca geçerli hücre için ayarlanacak ve "#SPILL!" olarak işaretlenecektir.
Ama bu tür durumlar için yine de formülün yayılacağı tüm aralığı geri döndürüyoruz.

##  set_dynamic_array_formula(self, array_formula, options, values, calculate_range, calculate_value, copts) {#str-aspose.cells.FormulaParseOptions-list-bool-bool-aspose.cells.CalculationOptions}
Dinamik dizi formülü ayarlar ve mümkünse formülün komşu hücrelere yayılmasını sağlar.


###  İadeler

formülün yayılması gereken aralık.


```python

def set_dynamic_array_formula(self, array_formula, options, values, calculate_range, calculate_value, copts):
    ...
```


| Parametre| Tip| Tanım|
| :- | :- | :- |
| array_formula | str | formül ifadesi|
| options | [`FormulaParseOptions`](/cells/python-net/tr/aspose.cells/formulaparseoptions) | Formülü ayrıştırma seçenekleri.<br/> "Ayrıştır" seçeneği göz ardı edilecek ve formül her zaman hemen ayrıştırılacaktır|
| values | list |Verilen dinamik dizi formülüne sahip hücreler için değerler (hesaplanan sonuçlar)|
| calculate_range | bool | Bu dinamik dizi formülü için dökülen aralığı hesaplayın.<br/>"Values" parametresi boş değilse ve bu bayrak yanlışsa,<br/> Daha sonra dökülen aralığın yüksekliği values.Length ve width values[0].Length olacaktır.|
| calculate_value | bool | "değerler" boş olduğunda, dökülen aralıktaki hücreler için bu dinamik dizi formülünün hesaplanması<br/> veya bir hücrenin "değerler"indeki karşılık gelen öğe boştur.|
| copts | [`CalculationOptions`](/cells/python-net/tr/aspose.cells/calculationoptions) | Formül hesaplama seçenekleri.<br/> Genellikle performans değerlendirmesi için [`CalculationOptions.recursive`](/cells/python-net/tr/aspose.cells/calculationoptions#recursive) özelliğinin false olması gerekir.|
###  Notlar

döndürülen aralık, bu dinamik dizi formülünün içine döküldüğü gerçek aralıkla aynı olmayabilir.
Aralıkta boş olmayan hücreler varsa, formül yalnızca geçerli hücre için ayarlanacak ve "#SPILL!" olarak işaretlenecektir.
Ama bu tür durumlar için yine de formülün yayılacağı tüm aralığı geri döndürüyoruz.


###  Ayrıca bakınız
* modül [`aspose.cells`](../../)
* sınıf [`Cell`](/cells/python-net/tr/aspose.cells/cell)
