---
title: set_array_formula yöntemi
second_title: Aspose.Cells for Python via .NET API Referanslar
description:
type: docs
weight: 320
url: /tr/aspose.cells/cell/set_array_formula/
is_root: false
---
##  set_array_formula(self, array_formula, row_number, column_number) {#str-int-int}
Bir dizi formülünü (MS Excel'de CTRL+SHIFT+ENTER ile girilen eski dizi formülü) bir hücre aralığına ayarlar.



```python

def set_array_formula(self, array_formula, row_number, column_number):
    ...
```


| Parametre| Tip| Tanım|
| :- | :- | :- |
| array_formula | str | Dizi formülü.|
| row_number | int | Dizi formülünün sonucunu dolduracak satır sayısı.|
| column_number | int | Dizi formülünün sonucunu dolduracak sütun sayısı.|


##  set_array_formula(self, array_formula, row_number, column_number, options) {#str-int-int-aspose.cells.FormulaParseOptions}
Bir dizi formülünü bir hücre aralığına ayarlar.



```python

def set_array_formula(self, array_formula, row_number, column_number, options):
    ...
```


| Parametre| Tip| Tanım|
| :- | :- | :- |
| array_formula | str | Dizi formülü.|
| row_number | int | Dizi formülünün sonucunu dolduracak satır sayısı.|
| column_number | int | Dizi formülünün sonucunu dolduracak sütun sayısı.|
| options | [`FormulaParseOptions`](/cells/python-net/tr/aspose.cells/formulaparseoptions) | Formülü ayrıştırma seçenekleri.|


##  set_array_formula(self, array_formula, row_number, column_number, is_r1c1, is_local) {#str-int-int-bool-bool}
Bir dizi formülünü bir hücre aralığına ayarlar.



```python

def set_array_formula(self, array_formula, row_number, column_number, is_r1c1, is_local):
    ...
```


| Parametre| Tip| Tanım|
| :- | :- | :- |
| array_formula | str | Dizi formülü.|
| row_number | int | Dizi formülünün sonucunu dolduracak satır sayısı.|
| column_number | int | Dizi formülünün sonucunu dolduracak sütun sayısı.|
| is_r1c1 | bool | formülün R1C1 formülü olup olmadığı|
| is_local | bool | formülün yerel olarak biçimlendirilmiş olup olmadığı|
###  Notlar

NOT: Bu sınıf artık kullanımdan kaldırıldı. Bunun yerine,
Lütfen Cell.SetArrayFormula(string,int,int,FormulaParseOptions) kullanın.
Bu özellik Aralık 2019'dan itibaren 12 ay sonra kaldırılacaktır.
Aspose yaşadığınız olumsuzluktan dolayı özür diler.

##  set_array_formula(self, array_formula, row_number, column_number, options, values) {#str-int-int-aspose.cells.FormulaParseOptions-list}
Bir dizi formülünü bir hücre aralığına ayarlar.



```python

def set_array_formula(self, array_formula, row_number, column_number, options, values):
    ...
```


| Parametre| Tip| Tanım|
| :- | :- | :- |
| array_formula | str | Dizi formülü.|
| row_number | int | Dizi formülünün sonucunu dolduracak satır sayısı.|
| column_number | int | Dizi formülünün sonucunu dolduracak sütun sayısı.|
| options | [`FormulaParseOptions`](/cells/python-net/tr/aspose.cells/formulaparseoptions) | Formülü ayrıştırma seçenekleri.|
| values | list | verilen dizi formülüne sahip hücrelerin değerleri|



###  Ayrıca bakınız
* modül [`aspose.cells`](../../)
* sınıf [`Cell`](/cells/python-net/tr/aspose.cells/cell)
