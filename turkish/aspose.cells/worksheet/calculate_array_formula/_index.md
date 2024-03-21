---
title: calculate_array_formula yöntemi
second_title: Aspose.Cells for Python via .NET API Referanslar
description:
type: docs
weight: 80
url: /tr/aspose.cells/worksheet/calculate_array_formula/
is_root: false
---
##  calculate_array_formula {#str-aspose.cells.CalculationOptions}
Bir formülü dizi formülü olarak hesaplar.



```python
def calculate_array_formula(self, formula, opts):
    ...
```


| Parametre| Tip| Tanım|
| :- | :- | :- |
| formula | str | Hesaplanacak formül.|
| opts | [`CalculationOptions`](/cells/python-net/tr/aspose.cells/calculationoptions) | Formül hesaplama seçenekleri|


##  calculate_array_formula {#str-aspose.cells.CalculationOptions-int-int}
Bir formülü dizi formülü olarak hesaplar.


###  İadeler

Hesaplanan formül sonucu.


```python
def calculate_array_formula(self, formula, opts, max_row_count, max_column_count):
    ...
```


| Parametre| Tip| Tanım|
| :- | :- | :- |
| formula | str | Hesaplanacak formül.|
| opts | [`CalculationOptions`](/cells/python-net/tr/aspose.cells/calculationoptions) | Formül hesaplama seçenekleri|
| max_row_count | int | elde edilen verilerin maksimum satır sayısı.<br/> Pozitif değilse veya gerçek satır sayısından büyükse gerçek satır sayısı kullanılacaktır.|
| max_column_count | int | elde edilen verilerin maksimum sütun sayısı.<br/> Pozitif değilse veya gerçek satır sayısından büyükse gerçek sütun sayısı kullanılacaktır.|
###  Notlar

Formül, boyutu ve sonucu hesaplamak için dinamik dizi formülü olarak alınacaktır.
Hesaplanan sonucun büyük veri kümesi olduğu durumlarda kullanıcı tarafından belirlenen maksimum boyut kullanılır
(örneğin hesaplanan sonuç bir satır veya sütun verisinin tamamına karşılık gelebilir)
ancak kullanıcının iş gereksinimlerine veya performans değerlendirmesine göre bu kadar büyük bir diziye ihtiyacı yoktur.

##  calculate_array_formula {#str-aspose.cells.FormulaParseOptions-aspose.cells.CalculationOptions-int-int-int-int-aspose.cells.CalculationData}
Bir formülü dizi formülü olarak hesaplar.


###  İadeler

Hesaplanan formül sonucu.


```python
def calculate_array_formula(self, formula, p_opts, c_opts, base_cell_row, base_cell_column, max_row_count, max_column_count, calculation_data):
    ...
```


| Parametre| Tip| Tanım|
| :- | :- | :- |
| formula | str | Hesaplanacak formül.|
| p_opts | [`FormulaParseOptions`](/cells/python-net/tr/aspose.cells/formulaparseoptions) | Formül ayrıştırma seçenekleri|
| c_opts | [`CalculationOptions`](/cells/python-net/tr/aspose.cells/calculationoptions) | Formül hesaplama seçenekleri|
| base_cell_row | int | Temel hücrenin satır dizini.|
| base_cell_column | int | Temel hücrenin sütun dizini.|
| max_row_count | int | Ortaya çıkan verilerin maksimum satır sayısı.<br/> Pozitif değilse veya gerçek satır sayısından büyükse gerçek satır sayısı kullanılacaktır.|
| max_column_count | int | Ortaya çıkan verilerin maksimum sütun sayısı.<br/> Pozitif değilse veya gerçek satır sayısından büyükse gerçek sütun sayısı kullanılacaktır.|
| calculation_data | [`CalculationData`](/cells/python-net/tr/aspose.cells/calculationdata) | Hesaplama verileri. Durum için kullanılır<br/>bu kullanıcının özel hesaplama motorunu uygularken bazı statik formülleri hesaplaması gerekir.<br/>Böyle bir durum için kullanıcının bunu sağlanan hesaplama verileriyle belirtmesi gerekir.<br/> [`AbstractCalculationEngine.calculate`](/cells/python-net/tr/aspose.cells/abstractcalculationengine/calculate) için.|
###  Notlar

Formül, boyutu ve sonucu hesaplamak için dinamik dizi formülü olarak alınacaktır.
Hesaplanan sonucun büyük veri kümesi olduğu durumlarda kullanıcı tarafından belirlenen maksimum boyut kullanılır
(örneğin hesaplanan sonuç bir satır veya sütun verisinin tamamına karşılık gelebilir)
ancak kullanıcının iş gereksinimlerine veya performans değerlendirmesine göre bu kadar büyük bir diziye ihtiyacı yoktur.


###  Ayrıca bakınız
* modül [`aspose.cells`](../../)
* sınıf [`Worksheet`](/cells/python-net/tr/aspose.cells/worksheet)
