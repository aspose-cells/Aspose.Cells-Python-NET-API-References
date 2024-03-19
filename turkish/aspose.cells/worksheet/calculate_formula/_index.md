---
title: calculate_formula yöntemi
second_title: Aspose.Cells for Python via .NET API Referanslar
description:
type: docs
weight: 90
url: /tr/aspose.cells/worksheet/calculate_formula/
is_root: false
---
##  calculate_formula {#str}
Bir formül hesaplar.


###  İadeler

Hesaplanan formül sonucu.


```python
def calculate_formula(self, formula):
    ...
```


| Parametre| Tip| Tanım|
| :- | :- | :- |
| formula | str | Hesaplanacak formül.|


##  calculate_formula {#str-aspose.cells.CalculationOptions}
Bir formül ifadesini doğrudan hesaplar.


###  İadeler

Verilen formülün hesaplanan sonucu.
Döndürülen nesne olası [`Cell.value`](/cells/python-net/tr/aspose.cells/cell#value) veya ReferredArea türlerinde olabilir.


```python
def calculate_formula(self, formula, opts):
    ...
```


| Parametre| Tip| Tanım|
| :- | :- | :- |
| formula | str | Hesaplanacak formül.|
| opts | [`CalculationOptions`](/cells/python-net/tr/aspose.cells/calculationoptions) | Formül hesaplama seçenekleri|
###  Notlar

Formül tıpkı A1 hücresine ayarlandığı gibi hesaplanacaktır.
Ve formül normal formül olarak alınacaktır.
Formülün dizi formülü olarak hesaplanmasına ve hesaplanan sonuç için bir dizi elde edilmesine ihtiyacınız varsa,
lütfen bunun yerine [`Worksheet.calculate_array_formula`](/cells/python-net/tr/aspose.cells/worksheet/calculate_array_formula)'i kullanın.

##  calculate_formula {#aspose.cells.CalculationOptions-bool}
Bu çalışma sayfasındaki tüm formülleri hesaplar.



```python
def calculate_formula(self, options, recursive):
    ...
```


| Parametre| Tip| Tanım|
| :- | :- | :- |
| options | [`CalculationOptions`](/cells/python-net/tr/aspose.cells/calculationoptions) | Hesaplama seçenekleri|
| recursive | bool | Doğru, çalışma sayfasının hücrelerinin diğer çalışma sayfalarının hücrelerine bağlı olup olmadığı anlamına gelir;<br/>diğer çalışma sayfalarındaki bağımlı hücreler de hesaplanacaktır.<br/> Yanlış, çalışma sayfasındaki tüm formüllerin hesaplandığı ve değerlerin doğru olduğu anlamına gelir.|


##  calculate_formula {#str-aspose.cells.FormulaParseOptions-aspose.cells.CalculationOptions-int-int-aspose.cells.CalculationData}
Bir formül ifadesini doğrudan hesaplar.


###  İadeler

Verilen formülün hesaplanan sonucu.
Döndürülen nesne olası [`Cell.value`](/cells/python-net/tr/aspose.cells/cell#value) veya ReferredArea türlerinde olabilir.


```python
def calculate_formula(self, formula, p_opts, c_opts, base_cell_row, base_cell_column, calculation_data):
    ...
```


| Parametre| Tip| Tanım|
| :- | :- | :- |
| formula | str | Hesaplanacak formül.|
| p_opts | [`FormulaParseOptions`](/cells/python-net/tr/aspose.cells/formulaparseoptions) | Formül ayrıştırma seçenekleri.|
| c_opts | [`CalculationOptions`](/cells/python-net/tr/aspose.cells/calculationoptions) | Formül hesaplama seçenekleri.|
| base_cell_row | int | Temel hücrenin satır dizini.|
| base_cell_column | int | Temel hücrenin sütun dizini.|
| calculation_data | [`CalculationData`](/cells/python-net/tr/aspose.cells/calculationdata) | Hesaplama verileri. Durum için kullanılır<br/>bu kullanıcının özel hesaplama motorunu uygularken bazı statik formülleri hesaplaması gerekir.<br/>Böyle bir durum için kullanıcının bunu sağlanan hesaplama verileriyle belirtmesi gerekir.<br/> [`AbstractCalculationEngine.calculate`](/cells/python-net/tr/aspose.cells/abstractcalculationengine/calculate) için.|
###  Notlar

Formül, belirtilen temel hücreye ayarlandığı gibi hesaplanacaktır.
Ve formül normal formül olarak alınacaktır. Formülün dizi formülü olarak hesaplanmasına ihtiyacınız varsa
ve hesaplanan sonuca yönelik bir dizi almak için lütfen şunu kullanın:
Bunun yerine [`Worksheet.calculate_array_formula`](/cells/python-net/tr/aspose.cells/worksheet/calculate_array_formula)'i arayın.


###  Ayrıca bakınız
* modül [`aspose.cells`](../../)
* sınıf [`Worksheet`](/cells/python-net/tr/aspose.cells/worksheet)
