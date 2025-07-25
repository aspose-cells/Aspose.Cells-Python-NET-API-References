---
title: calculate_formula yöntemi
second_title: Aspose.Cells for Python via .NET API Referanslar
description:
type: docs
weight: 90
url: /tr/aspose.cells/worksheet/calculate_formula/
is_root: false
---
##  calculate_formula(self, formula) {#str}
Bir formülü hesaplar.


###  İadeler

Hesaplanan formül sonucu.


```python

def calculate_formula(self, formula):
    ...
```


| Parametre| Tip| Tanım|
| :- | :- | :- |
| formula | str | Hesaplanması gereken formül.|


##  calculate_formula(self, formula, opts) {#str-aspose.cells.CalculationOptions}
Bir formül ifadesini doğrudan hesaplar.


###  İadeler

Verilen formülün hesaplanan sonucu.
Dönen nesne [`Cell.value`](/cells/python-net/tr/aspose.cells/cell#value) veya ReferredArea türlerinden biri olabilir.


```python

def calculate_formula(self, formula, opts):
    ...
```


| Parametre| Tip| Tanım|
| :- | :- | :- |
| formula | str | Hesaplanması gereken formül.|
| opts | [`CalculationOptions`](/cells/python-net/tr/aspose.cells/calculationoptions) | Formül hesaplama seçenekleri|
###  Notlar

Formül A1 hücresine ayarlandığı gibi hesaplanacaktır.
Ve formül normal formül olarak alınacaktır.
Formülün bir dizi formülü olarak hesaplanması ve hesaplanan sonuç için bir dizi elde edilmesi gerekiyorsa,
Lütfen bunun yerine [`Worksheet.calculate_array_formula`](/cells/python-net/tr/aspose.cells/worksheet/calculate_array_formula)'i kullanın.

##  calculate_formula(self, options, recursive) {#aspose.cells.CalculationOptions-bool}
Bu çalışma sayfasındaki tüm formülleri hesaplar.



```python

def calculate_formula(self, options, recursive):
    ...
```


| Parametre| Tip| Tanım|
| :- | :- | :- |
| options | [`CalculationOptions`](/cells/python-net/tr/aspose.cells/calculationoptions) | Hesaplama seçenekleri|
| recursive | bool | Doğrusu, çalışma sayfasının hücrelerinin diğer çalışma sayfalarının hücrelerine bağlı olması demektir.<br/>Diğer çalışma sayfalarındaki bağımlı hücreler de hesaplanacaktır.<br/> Yanlış, çalışma sayfasındaki tüm formüllerin hesaplandığı ve değerlerin doğru olduğu anlamına gelir.|


##  calculate_formula(self, formula, p_opts, c_opts, base_cell_row, base_cell_column, calculation_data) {#str-aspose.cells.FormulaParseOptions-aspose.cells.CalculationOptions-int-int-aspose.cells.CalculationData}
Bir formül ifadesini doğrudan hesaplar.


###  İadeler

Verilen formülün hesaplanan sonucu.
Dönen nesne [`Cell.value`](/cells/python-net/tr/aspose.cells/cell#value) veya ReferredArea türlerinden biri olabilir.


```python

def calculate_formula(self, formula, p_opts, c_opts, base_cell_row, base_cell_column, calculation_data):
    ...
```


| Parametre| Tip| Tanım|
| :- | :- | :- |
| formula | str | Hesaplanması gereken formül.|
| p_opts | [`FormulaParseOptions`](/cells/python-net/tr/aspose.cells/formulaparseoptions) | Formül ayrıştırma seçenekleri.|
| c_opts | [`CalculationOptions`](/cells/python-net/tr/aspose.cells/calculationoptions) | Formül hesaplama seçenekleri.|
| base_cell_row | int | Temel hücrenin satır indeksi.|
| base_cell_column | int | Temel hücrenin sütun indeksi.|
| calculation_data | [`CalculationData`](/cells/python-net/tr/aspose.cells/calculationdata) | Hesaplama verileri. Aşağıdaki durumlar için kullanılır:<br/>Kullanıcının özel hesaplama motorunu uygularken bazı statik formülleri hesaplaması gerekir.<br/>Bu tür bir durum için kullanıcının bunu sağlanan hesaplama verileriyle belirtmesi gerekir<br/> Aspose.Cells.AbstractCalculationEngine.Calculate için.|
###  Notlar

Formül, belirtilen taban hücresine ayarlandığı gibi hesaplanacaktır.
Formül normal formül olarak alınacaktır. Formülün dizi formülü olarak hesaplanmasını istiyorsanız
ve hesaplanan sonuç için bir dizi elde etmek için lütfen şunu kullanın:
[`Worksheet.calculate_array_formula`](/cells/python-net/tr/aspose.cells/worksheet/calculate_array_formula) yerine.


###  Ayrıca bakınız
* modül [`aspose.cells`](../../)
* sınıf [`Worksheet`](/cells/python-net/tr/aspose.cells/worksheet)
