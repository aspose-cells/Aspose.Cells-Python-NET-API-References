---
title: set_formula yöntemi
second_title: Aspose.Cells for Python via .NET API Referanslar
description:
type: docs
weight: 340
url: /tr/aspose.cells/cell/set_formula/
is_root: false
---
##  set_formula {#str-any}
Formülü ve formülün değerini (hesaplanan sonuç) ayarlayın.



```python
def set_formula(self, formula, value):
    ...
```


| Parametre| Tip| Tanım|
| :- | :- | :- |
| formula | str | Formül.|
| value | any |Formülün değeri (hesaplanan sonuç).|


##  set_formula {#str-aspose.cells.FormulaParseOptions-any}
Formülü ve formülün değerini (hesaplanan sonuç) ayarlayın.



```python
def set_formula(self, formula, options, value):
    ...
```


| Parametre| Tip| Tanım|
| :- | :- | :- |
| formula | str | Formül.|
| options | [`FormulaParseOptions`](/cells/python-net/tr/aspose.cells/formulaparseoptions) | Formülü ayrıştırmaya yönelik seçenekler.|
| value | any |Formülün değeri (hesaplanan sonuç).|


##  set_formula {#str-bool-bool-any}
Formülü ve formülün değerini ayarlayın.



```python
def set_formula(self, formula, is_r1c1, is_local, value):
    ...
```


| Parametre| Tip| Tanım|
| :- | :- | :- |
| formula | str | Formül.|
| is_r1c1 | bool | Formülün R1C1 formülü olup olmadığı.|
| is_local | bool | Formülün yerel ayarlı olup olmadığı.|
| value | any | Formülün değeri.|
###  Notlar

NOT: Bu sınıf artık kullanılmıyor. Yerine,
lütfen Cell.SetFormula(string,FormulaParseOptions,object) komutunu kullanın.
Bu mülk Aralık 2019'dan 12 ay sonra kaldırılacaktır.
Aspose, yaşamış olabileceğiniz rahatsızlıklardan dolayı özür diler.


###  Ayrıca bakınız
* modül [`aspose.cells`](../../)
* sınıf [`Cell`](/cells/python-net/tr/aspose.cells/cell)
