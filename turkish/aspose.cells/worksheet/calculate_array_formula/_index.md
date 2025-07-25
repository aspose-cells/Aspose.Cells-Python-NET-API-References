---
title: calculate_array_formula yöntemi
second_title: Aspose.Cells for Python via .NET API Referanslar
description:
type: docs
weight: 80
url: /tr/aspose.cells/worksheet/calculate_array_formula/
is_root: false
---
##  calculate_array_formula(self, formula, opts) {#str-aspose.cells.CalculationOptions}
Bir formülü dizi formülü olarak hesaplar.



```python

def calculate_array_formula(self, formula, opts):
    ...
```


| Parametre| Tip| Tanım|
| :- | :- | :- |
| formula | str | Hesaplanması gereken formül.|
| opts | [`CalculationOptions`](/cells/python-net/tr/aspose.cells/calculationoptions) | Formül hesaplama seçenekleri|


##  calculate_array_formula(self, formula, opts, max_row_count, max_column_count) {#str-aspose.cells.CalculationOptions-int-int}
Bir formülü dizi formülü olarak hesaplar.


###  İadeler

Hesaplanan formül sonucu.


```python

def calculate_array_formula(self, formula, opts, max_row_count, max_column_count):
    ...
```


| Parametre| Tip| Tanım|
| :- | :- | :- |
| formula | str | Hesaplanması gereken formül.|
| opts | [`CalculationOptions`](/cells/python-net/tr/aspose.cells/calculationoptions) | Formül hesaplama seçenekleri|
| max_row_count | int | sonuçta elde edilen verilerin maksimum satır sayısı.<br/> Eğer pozitif değilse veya gerçek satır sayısından büyükse, gerçek satır sayısı kullanılacaktır.|
| max_column_count | int | sonuçta elde edilen verilerin maksimum sütun sayısı.<br/> Eğer pozitif değilse veya gerçek satır sayısından büyükse, gerçek sütun sayısı kullanılacaktır.|
###  Notlar

Formül, boyut ve sonucu hesaplamak için dinamik dizi formülü olarak alınacaktır.
Hesaplanan sonucun büyük veri kümesi olduğu durumlarda kullanıcı tarafından belirlenen maksimum boyut kullanılır
(örneğin, hesaplanan sonuç bir satır veya sütun verisinin tamamına karşılık gelebilir)
Ancak kullanıcının iş gereksinimi veya performans değerlendirmesi açısından bu kadar büyük bir diziye ihtiyacı yoktur.

##  calculate_array_formula(self, formula, p_opts, c_opts, base_cell_row, base_cell_column, max_row_count, max_column_count, calculation_data) {#str-aspose.cells.FormulaParseOptions-aspose.cells.CalculationOptions-int-int-int-int-aspose.cells.CalculationData}
Bir formülü dizi formülü olarak hesaplar.


###  İadeler

Hesaplanan formül sonucu.


```python

def calculate_array_formula(self, formula, p_opts, c_opts, base_cell_row, base_cell_column, max_row_count, max_column_count, calculation_data):
    ...
```


| Parametre| Tip| Tanım|
| :- | :- | :- |
| formula | str | Hesaplanması gereken formül.|
| p_opts | [`FormulaParseOptions`](/cells/python-net/tr/aspose.cells/formulaparseoptions) |Formülü ayrıştırma seçenekleri|
| c_opts | [`CalculationOptions`](/cells/python-net/tr/aspose.cells/calculationoptions) | Formül hesaplama seçenekleri|
| base_cell_row | int | Temel hücrenin satır indeksi.|
| base_cell_column | int | Temel hücrenin sütun indeksi.|
| max_row_count | int | Elde edilen verilerin maksimum satır sayısı.<br/> Eğer pozitif değilse veya gerçek satır sayısından büyükse, gerçek satır sayısı kullanılacaktır.|
| max_column_count | int | Elde edilen verilerin maksimum sütun sayısı.<br/> Eğer pozitif değilse veya gerçek satır sayısından büyükse, gerçek sütun sayısı kullanılacaktır.|
| calculation_data | [`CalculationData`](/cells/python-net/tr/aspose.cells/calculationdata) | Hesaplama verileri. Aşağıdaki durumlar için kullanılır:<br/>Kullanıcının özel hesaplama motorunu uygularken bazı statik formülleri hesaplaması gerekir.<br/>Bu tür bir durum için kullanıcının bunu sağlanan hesaplama verileriyle belirtmesi gerekir<br/> Aspose.Cells.AbstractCalculationEngine.Calculate için.|
###  Notlar

Formül, boyut ve sonucu hesaplamak için dinamik dizi formülü olarak alınacaktır.
Hesaplanan sonucun büyük veri kümesi olduğu durumlarda kullanıcı tarafından belirlenen maksimum boyut kullanılır
(örneğin, hesaplanan sonuç bir satır veya sütun verisinin tamamına karşılık gelebilir)
Ancak kullanıcının iş gereksinimi veya performans değerlendirmesi açısından bu kadar büyük bir diziye ihtiyacı yoktur.


###  Ayrıca bakınız
* modül [`aspose.cells`](../../)
* sınıf [`Worksheet`](/cells/python-net/tr/aspose.cells/worksheet)
