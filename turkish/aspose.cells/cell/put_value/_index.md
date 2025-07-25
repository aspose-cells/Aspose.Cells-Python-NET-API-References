---
title: put_value yöntemi
second_title: Aspose.Cells for Python via .NET API Referanslar
description:
type: docs
weight: 290
url: /tr/aspose.cells/cell/put_value/
is_root: false
---
##  put_value(self, bool_value) {#bool}
Hücreye bir Boole değeri koyar.



```python

def put_value(self, bool_value):
    ...
```


| Parametre| Tip| Tanım|
| :- | :- | :- |
| bool_value | bool |  |


##  put_value(self, int_value) {#int}
Hücreye tam sayı değeri koyar.



```python

def put_value(self, int_value):
    ...
```


| Parametre| Tip| Tanım|
| :- | :- | :- |
| int_value | int | Giriş değeri|


##  put_value(self, double_value) {#float}
Hücreye çift değer koyar.



```python

def put_value(self, double_value):
    ...
```


| Parametre| Tip| Tanım|
| :- | :- | :- |
| double_value | float | Giriş değeri|


##  put_value(self, string_value) {#str}
Hücreye bir dize değeri koyar.



```python

def put_value(self, string_value):
    ...
```


| Parametre| Tip| Tanım|
| :- | :- | :- |
| string_value | str | Giriş değeri|


##  put_value(self, date_time) {#DateTime}
Hücreye bir DateTime değeri koyar.



```python

def put_value(self, date_time):
    ...
```


| Parametre| Tip| Tanım|
| :- | :- | :- |
| date_time | DateTime | Giriş değeri|
###  Notlar

Bir hücreye DateTime değeri ayarlamak, hücrenin otomatik olarak tarih saat olarak biçimlendirileceği anlamına gelmez.
DateTime değeri hem ms excel hem de Aspose.Cells veri modelinde sayısal değer olarak korundu.
Sayısal değerin sayısal değerin kendisi mi yoksa tarih saat olarak mı alınacağı
Bu hücreye uygulanan sayı biçimine bağlıdır. Bu hücre tarih saat olarak biçimlendirilmemişse,
Girdiğiniz değer DateTime olsa bile sayısal bir değer olarak gösterilecektir.
###  Örnek

Bu örnekte bir hücreye DateTime değerinin nasıl ayarlanacağı ve tarih saat olarak nasıl gösterileceği gösterilmektedir.

```python
from aspose.cells import Workbook
from datetime import datetime

excel = Workbook()
cells = excel.worksheets[0].cells
# Put date time into a cell
cell = cells.get(0, 0)
cell.put_value(datetime(2023, 5, 15))
style = cell.get_style(False)
style.number = 14
cell.set_style(style)

```


##  put_value(self, object_value) {#any}
Hücreye bir nesne değeri koyar.



```python

def put_value(self, object_value):
    ...
```


| Parametre| Tip| Tanım|
| :- | :- | :- |
| object_value | any | giriş değeri|


##  put_value(self, string_value, is_converted) {#str-bool}
Hücreye bir dize değeri koyar ve uygunsa değeri başka bir veri türüne dönüştürür.



```python

def put_value(self, string_value, is_converted):
    ...
```


| Parametre| Tip| Tanım|
| :- | :- | :- |
| string_value | str | Giriş değeri|
| is_converted | bool | Doğru: Uygunsa diğer veri türüne dönüştürülür.|


##  put_value(self, string_value, is_converted, set_style) {#str-bool-bool}
Hücreye bir değer koyar, uygunsa değer başka bir veri türüne dönüştürülür ve hücrenin sayı biçimi sıfırlanır.



```python

def put_value(self, string_value, is_converted, set_style):
    ...
```


| Parametre| Tip| Tanım|
| :- | :- | :- |
| string_value | str | Giriş değeri|
| is_converted | bool | Doğru: Uygunsa diğer veri türüne dönüştürülür.|
| set_style | bool | Doğru: Diğer veri türüne dönüştürürken sayı biçimini hücrenin stiline ayarlayın|



###  Ayrıca bakınız
* modül [`aspose.cells`](../../)
* sınıf [`Cell`](/cells/python-net/tr/aspose.cells/cell)
