---
title: group_by yöntemi
second_title: Aspose.Cells for Python via .NET API Referanslar
description:
type: docs
weight: 140
url: /tr/aspose.cells.pivot/pivotfield/group_by/
is_root: false
---
##  group_by(self, interval, new_field) {#float-bool}
Alanı dahili olarak otomatik olarak gruplandır



```python

def group_by(self, interval, new_field):
    ...
```


| Parametre| Tip| Tanım|
| :- | :- | :- |
| interval | float | Grubun iç yapısı.<br/> Sıfır ise otomatik değer atanacaktır,|
| new_field | bool | Pivot tabloya yeni bir alan eklenip eklenmeyeceğini belirtir.|


##  group_by(self, custom_group_items, new_field) {#list-bool}
Alanı özel grupla.


###  İadeler

Yanlış, bu alanın tarih saatine göre gruplandırılamayacağı anlamına gelir.


```python

def group_by(self, custom_group_items, new_field):
    ...
```


| Parametre| Tip| Tanım|
| :- | :- | :- |
| custom_group_items | list | Özel grup öğeleri.|
| new_field | bool | Pivot tabloya yeni bir alan eklenip eklenmeyeceğini belirtir|


##  group_by(self, start, end, interval, new_field) {#float-float-float-bool}
Dosyayı numaraya göre gruplandırın.


###  İadeler

Yanlış, bu alanın tarih saatine göre gruplandırılamayacağı anlamına gelir.


```python

def group_by(self, start, end, interval, new_field):
    ...
```


| Parametre| Tip| Tanım|
| :- | :- | :- |
| start | float | Başlangıç değeri|
| end | float | Değerin sonu|
| interval | float | Aralık|
| new_field | bool | Pivot tabloya yeni bir alan eklenip eklenmeyeceğini belirtir|


##  group_by(self, start, end, groups, interval, first_as_new_field) {#DateTime-DateTime-list-float-bool}
Dosyayı tarih grubu türlerine göre gruplandırın.


###  İadeler

Yanlış, bu alanın tarih saatine göre gruplandırılamayacağı anlamına gelir.


```python

def group_by(self, start, end, groups, interval, first_as_new_field):
    ...
```


| Parametre| Tip| Tanım|
| :- | :- | :- |
| start | DateTime | Başlangıç tarihi ve saati|
| end | DateTime | Tarih/saat sonu|
| groups | list | Grup türleri|
| interval | float | Aralık|
| first_as_new_field | bool | Pivot tabloya yeni bir alan eklenip eklenmeyeceğini belirtir.<br/> Sadece ilk grup maddesi için.|



###  Ayrıca bakınız
* modül [`aspose.cells.pivot`](../../)
* sınıf [`PivotField`](/cells/python-net/tr/aspose.cells.pivot/pivotfield)
