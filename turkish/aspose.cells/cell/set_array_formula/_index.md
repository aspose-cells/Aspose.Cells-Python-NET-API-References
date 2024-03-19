---
title: set_array_formula yöntemi
second_title: Aspose.Cells for Python via .NET API Referanslar
description:
type: docs
weight: 310
url: /tr/aspose.cells/cell/set_array_formula/
is_root: false
---
##  set_array_formula {#str-int-int}
Bir dizi formülünü (ms excel'de CTRL+SHIFT+ENTER yoluyla girilen eski dizi formülü) bir hücre aralığına ayarlar.



```python
def set_array_formula(self, array_formula, row_number, column_number):
    ...
```


| Parametre| Tip| Tanım|
| :- | :- | :- |
| array_formula | str | Dizi formülü.|
| row_number | int | Dizi formülünün sonucunun doldurulacağı satır sayısı.|
| column_number | int | Dizi formülünün sonucunun doldurulacağı sütun sayısı.|


##  set_array_formula {#str-int-int-aspose.cells.FormulaParseOptions}
Bir dizi formülünü bir hücre aralığına ayarlar.



```python
def set_array_formula(self, array_formula, row_number, column_number, options):
    ...
```


| Parametre| Tip| Tanım|
| :- | :- | :- |
| array_formula | str | Dizi formülü.|
| row_number | int | Dizi formülünün sonucunun doldurulacağı satır sayısı.|
| column_number | int | Dizi formülünün sonucunun doldurulacağı sütun sayısı.|
| options | [`FormulaParseOptions`](/cells/python-net/tr/aspose.cells/formulaparseoptions) | Formülü ayrıştırmaya yönelik seçenekler.|


##  set_array_formula {#str-int-int-bool-bool}
Bir dizi formülünü bir hücre aralığına ayarlar.



```python
def set_array_formula(self, array_formula, row_number, column_number, is_r1c1, is_local):
    ...
```


| Parametre| Tip| Tanım|
| :- | :- | :- |
| array_formula | str | Dizi formülü.|
| row_number | int | Dizi formülünün sonucunun doldurulacağı satır sayısı.|
| column_number | int | Dizi formülünün sonucunun doldurulacağı sütun sayısı.|
| is_r1c1 | bool | formülün R1C1 formülü olup olmadığı|
| is_local | bool | formülün yerel ayarda biçimlendirilip biçimlendirilmediği|
###  Notlar

NOT: Bu sınıf artık kullanılmıyor. Yerine,
lütfen Cell.SetArrayFormula(string,int,int,FormulaParseOptions) komutunu kullanın.
Bu mülk Aralık 2019'dan 12 ay sonra kaldırılacaktır.
Aspose, yaşamış olabileceğiniz rahatsızlıklardan dolayı özür diler.

##  set_array_formula {#str-int-int-aspose.cells.FormulaParseOptions-list}
Bir dizi formülünü bir hücre aralığına ayarlar.



```python
def set_array_formula(self, array_formula, row_number, column_number, options, values):
    ...
```


| Parametre| Tip| Tanım|
| :- | :- | :- |
| array_formula | str | Dizi formülü.|
| row_number | int | Dizi formülünün sonucunun doldurulacağı satır sayısı.|
| column_number | int | Dizi formülünün sonucunun doldurulacağı sütun sayısı.|
| options | [`FormulaParseOptions`](/cells/python-net/tr/aspose.cells/formulaparseoptions) | Formülü ayrıştırmaya yönelik seçenekler.|
| values | list | verilen dizi formülüne sahip hücreler için değerler|



###  Ayrıca bakınız
* modül [`aspose.cells`](../../)
* sınıf [`Cell`](/cells/python-net/tr/aspose.cells/cell)
