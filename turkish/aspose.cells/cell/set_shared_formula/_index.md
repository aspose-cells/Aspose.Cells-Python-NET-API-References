---
title: set_shared_formula yöntemi
second_title: Aspose.Cells for Python via .NET API Referanslar
description:
type: docs
weight: 350
url: /tr/aspose.cells/cell/set_shared_formula/
is_root: false
---
##  set_shared_formula {#str-int-int}
Paylaşılan formülleri bir hücre aralığına ayarlar.



```python
def set_shared_formula(self, shared_formula, row_number, column_number):
    ...
```


| Parametre| Tip| Tanım|
| :- | :- | :- |
| shared_formula | str | Paylaşılan formül|
| row_number | int | Formülün doldurulacağı satır sayısı.|
| column_number | int | Formülün doldurulacağı sütun sayısı.|
###  Notlar



##  set_shared_formula {#str-int-int-aspose.cells.FormulaParseOptions}

Paylaşılan formülleri bir hücre aralığına ayarlar.



```python
def set_shared_formula(self, shared_formula, row_number, column_number, options):
    ...
```


| Parametre| Tip| Tanım|
| :- | :- | :- |
| shared_formula | str | Paylaşılan formül|
| row_number | int | Formülün doldurulacağı satır sayısı.|
| column_number | int | Formülün doldurulacağı sütun sayısı.|
| options | [`FormulaParseOptions`](/cells/python-net/tr/aspose.cells/formulaparseoptions) | Formülü ayrıştırmaya yönelik seçenekler.|


##  set_shared_formula {#str-int-int-bool-bool}
Bir formül hücre aralığına ayarlar.



```python
def set_shared_formula(self, shared_formula, row_number, column_number, is_r1c1, is_local):
    ...
```


| Parametre| Tip| Tanım|
| :- | :- | :- |
| shared_formula | str | Paylaşılan formül|
| row_number | int | Formülün doldurulacağı satır sayısı.|
| column_number | int | Formülün doldurulacağı sütun sayısı.|
| is_r1c1 | bool | formülün R1C1 formülü olup olmadığı|
| is_local | bool | formülün yerel ayarda biçimlendirilip biçimlendirilmediği|
###  Notlar

NOT: Bu sınıf artık kullanılmıyor. Yerine,
lütfen Cell.SetSharedFormula(string,int,int,FormulaParseOptions) komutunu kullanın.
Bu mülk Aralık 2019'dan 12 ay sonra kaldırılacaktır.
Aspose, yaşamış olabileceğiniz rahatsızlıklardan dolayı özür diler.

##  set_shared_formula {#str-int-int-aspose.cells.FormulaParseOptions-list}
Paylaşılan formülleri bir hücre aralığına ayarlar.



```python
def set_shared_formula(self, shared_formula, row_number, column_number, options, values):
    ...
```


| Parametre| Tip| Tanım|
| :- | :- | :- |
| shared_formula | str | Paylaşılan formül|
| row_number | int | Formülün doldurulacağı satır sayısı.|
| column_number | int | Formülün doldurulacağı sütun sayısı.|
| options | [`FormulaParseOptions`](/cells/python-net/tr/aspose.cells/formulaparseoptions) | Formülü ayrıştırmaya yönelik seçenekler.|
| values | list | verilen paylaşılan formüle sahip hücreler için değerler|



###  Ayrıca bakınız
* modül [`aspose.cells`](../../)
* sınıf [`Cell`](/cells/python-net/tr/aspose.cells/cell)
