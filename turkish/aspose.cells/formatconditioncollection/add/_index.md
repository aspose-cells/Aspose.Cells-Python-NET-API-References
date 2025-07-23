---
title: add yöntemi
second_title: Aspose.Cells for Python via .NET API Referanslar
description:
type: docs
weight: 20
url: /tr/aspose.cells/formatconditioncollection/add/
is_root: false
---
##  add(self, cell_area, type, operator_type, formula1, formula2) {#aspose.cells.CellArea-aspose.cells.FormatConditionType-aspose.cells.OperatorType-str-str}
FormatConditions'a bir biçimlendirme koşulu ve etkilenen hücre aralığı ekler
FormatConditions en fazla üç koşullu biçimlendirme içerebilir.
Koşullu biçimlendirme formüllerinde diğer sayfalara atıf yapılmasına izin verilmez.


###  İadeler

[0]:Biçimlendirme koşulu nesne dizini;[1] Etkilenen hücre aralığı dizini.


```python

def add(self, cell_area, type, operator_type, formula1, formula2):
    ...
```


| Parametre| Tip| Tanım|
| :- | :- | :- |
| cell_area | [`CellArea`](/cells/python-net/tr/aspose.cells/cellarea) |Koşullu biçimlendirilmiş hücre aralığı.|
| type | [`FormatConditionType`](/cells/python-net/tr/aspose.cells/formatconditiontype) | Koşullu biçimlendirme türüdür. FormatConditionType üyelerinden biri olabilir.|
| operator_type | [`OperatorType`](/cells/python-net/tr/aspose.cells/operatortype) | Karşılaştırma operatörü.OperatorType'ın üyelerinden biri olabilir.|
| formula1 | str | Koşullu biçimlendirmeyle ilişkili değer veya ifade.|
| formula2 | str | Koşullu biçimlendirmeyle ilişkili değer veya ifade|



###  Ayrıca bakınız
* modül [`aspose.cells`](../../)
* sınıf [`FormatConditionCollection`](/cells/python-net/tr/aspose.cells/formatconditioncollection)
