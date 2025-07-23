---
title: add_condition yöntemi
second_title: Aspose.Cells for Python via .NET API Referanslar
description:
type: docs
weight: 40
url: /tr/aspose.cells/formatconditioncollection/add_condition/
is_root: false
---
##  add_condition(self, type) {#aspose.cells.FormatConditionType}
Biçimlendirme koşulu ekleyin.


###  İadeler

Biçimlendirme koşulu nesne dizini;


```python

def add_condition(self, type):
    ...
```


| Parametre| Tip| Tanım|
| :- | :- | :- |
| type | [`FormatConditionType`](/cells/python-net/tr/aspose.cells/formatconditiontype) | Biçimlendirme koşulu türü.|


##  add_condition(self, type, operator_type, formula1, formula2) {#aspose.cells.FormatConditionType-aspose.cells.OperatorType-str-str}
Biçimlendirme koşulu ekler.


###  İadeler

Biçimlendirme koşulu nesne dizini;


```python

def add_condition(self, type, operator_type, formula1, formula2):
    ...
```


| Parametre| Tip| Tanım|
| :- | :- | :- |
| type | [`FormatConditionType`](/cells/python-net/tr/aspose.cells/formatconditiontype) | Biçimlendirme koşulunun türü.|
| operator_type | [`OperatorType`](/cells/python-net/tr/aspose.cells/operatortype) | Operatör türü|
| formula1 | str | Koşullu biçimlendirmeyle ilişkili değer veya ifade.<br/>Eğer girilen değer '=' ile başlıyorsa formül olarak alınacaktır.<br/>Aksi takdirde düz değer(metin, sayı, bool) olarak alınacaktır.<br/> '=' ile başlayan metin değerleri için kullanıcı bunu formül olarak "=\"=...\"" formatında girebilir.|
| formula2 | str | Koşullu biçimlendirmeyle ilişkili değer veya ifade.<br/> Giriş formatı formül1 ile aynıdır|



###  Ayrıca bakınız
* modül [`aspose.cells`](../../)
* sınıf [`FormatConditionCollection`](/cells/python-net/tr/aspose.cells/formatconditioncollection)
