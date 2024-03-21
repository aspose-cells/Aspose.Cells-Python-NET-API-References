---
title: set_dynamic_array_formula yöntemi
second_title: Aspose.Cells for Python via .NET API Referanslar
description:
type: docs
weight: 330
url: /tr/aspose.cells/cell/set_dynamic_array_formula/
is_root: false
---
##  set_dynamic_array_formula {#str-aspose.cells.FormulaParseOptions-bool}
Dinamik dizi formülünü ayarlar ve mümkünse formülün komşu hücrelere yayılmasını sağlar.


###  İadeler

formülün içine yayılması gereken aralık.


```python
def set_dynamic_array_formula(self, array_formula, options, calculate_value):
    ...
```


| Parametre| Tip| Tanım|
| :- | :- | :- |
| array_formula | str |formül ifadesi|
| options | [`FormulaParseOptions`](/cells/python-net/tr/aspose.cells/formulaparseoptions) | formülü ayrıştırma seçenekleri.<br/> "Ayrıştır" seçeneği göz ardı edilecek ve formül her zaman hemen ayrıştırılacak|
| calculate_value | bool | Taşınan aralıktaki hücreler için bu dinamik dizi formülünün hesaplanıp hesaplanmayacağı.|


##  set_dynamic_array_formula {#str-aspose.cells.FormulaParseOptions-list-bool-bool}
Dinamik dizi formülünü ayarlar ve mümkünse formülün komşu hücrelere yayılmasını sağlar.


###  İadeler

formülün içine yayılması gereken aralık.


```python
def set_dynamic_array_formula(self, array_formula, options, values, calculate_range, calculate_value):
    ...
```


| Parametre| Tip| Tanım|
| :- | :- | :- |
| array_formula | str |formül ifadesi|
| options | [`FormulaParseOptions`](/cells/python-net/tr/aspose.cells/formulaparseoptions) | formülü ayrıştırma seçenekleri.<br/> "Ayrıştır" seçeneği göz ardı edilecek ve formül her zaman hemen ayrıştırılacak|
| values | list | Verilen dinamik dizi formülüne sahip hücreler için değerler (hesaplanan sonuçlar)|
| calculate_range | bool | Bu dinamik dizi formülü için dağılmış aralığın hesaplanıp hesaplanmayacağı.<br/>"values" parametresi null değilse ve bu bayrak yanlışsa,<br/> o zaman dökülen aralığın yüksekliği değerler olacaktır. Uzunluk ve genişlik, değerler[0].Uzunluk olacaktır.|
| calculate_value | bool | "değerler" boş olduğunda, dağılmış aralıktaki hücreler için bu dinamik dizi formülünün hesaplanıp hesaplanmayacağı<br/> veya bir hücre için "değerler"deki karşılık gelen öğe boştur.|


##  set_dynamic_array_formula {#str-aspose.cells.FormulaParseOptions-list-bool-bool-aspose.cells.CalculationOptions}
Dinamik dizi formülünü ayarlar ve mümkünse formülün komşu hücrelere yayılmasını sağlar.


###  İadeler

formülün içine yayılması gereken aralık.


```python
def set_dynamic_array_formula(self, array_formula, options, values, calculate_range, calculate_value, copts):
    ...
```


| Parametre| Tip| Tanım|
| :- | :- | :- |
| array_formula | str |formül ifadesi|
| options | [`FormulaParseOptions`](/cells/python-net/tr/aspose.cells/formulaparseoptions) | formülü ayrıştırma seçenekleri.<br/> "Ayrıştır" seçeneği göz ardı edilecek ve formül her zaman hemen ayrıştırılacak|
| values | list | Verilen dinamik dizi formülüne sahip hücreler için değerler (hesaplanan sonuçlar)|
| calculate_range | bool | Bu dinamik dizi formülü için dağılmış aralığın hesaplanıp hesaplanmayacağı.<br/>"values" parametresi null değilse ve bu bayrak yanlışsa,<br/> o zaman dökülen aralığın yüksekliği değerler olacaktır. Uzunluk ve genişlik, değerler[0].Uzunluk olacaktır.|
| calculate_value | bool | "değerler" boş olduğunda, dağılmış aralıktaki hücreler için bu dinamik dizi formülünün hesaplanıp hesaplanmayacağı<br/> veya bir hücre için "değerler"deki karşılık gelen öğe boştur.|
| copts | [`CalculationOptions`](/cells/python-net/tr/aspose.cells/calculationoptions) | Formül hesaplama seçenekleri.<br/> Performans değerlendirmesi için genellikle [`CalculationOptions.recursive`](/cells/python-net/tr/aspose.cells/calculationoptions#recursive) özelliğinin false olması gerekir.|



###  Ayrıca bakınız
* modül [`aspose.cells`](../../)
* sınıf [`Cell`](/cells/python-net/tr/aspose.cells/cell)
