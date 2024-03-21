---
title: put_value yöntemi
second_title: Aspose.Cells for Python via .NET API Referanslar
description:
type: docs
weight: 280
url: /tr/aspose.cells/cell/put_value/
is_root: false
---
##  put_value {#bool}
Hücreye bir boole değeri koyar.



```python
def put_value(self, bool_value):
    ...
```


| Parametre| Tip| Tanım|
| :- | :- | :- |
| bool_value | bool |  |


##  put_value {#int}
Hücreye bir tam sayı değeri koyar.



```python
def put_value(self, int_value):
    ...
```


| Parametre| Tip| Tanım|
| :- | :- | :- |
| int_value | int | Girdi değeri|


##  put_value {#float}
Hücreye çift değer koyar.



```python
def put_value(self, double_value):
    ...
```


| Parametre| Tip| Tanım|
| :- | :- | :- |
| double_value | float | Girdi değeri|


##  put_value {#str}
Hücreye bir dize değeri koyar.



```python
def put_value(self, string_value):
    ...
```


| Parametre| Tip| Tanım|
| :- | :- | :- |
| string_value | str | Girdi değeri|


##  put_value {#DateTime}
Hücreye bir DateTime değeri koyar.



```python
def put_value(self, date_time):
    ...
```


| Parametre| Tip| Tanım|
| :- | :- | :- |
| date_time | DateTime | Girdi değeri|
###  Notlar

Bir hücre dozu için DateTime değerinin ayarlanması, hücrenin otomatik olarak tarih saat olarak biçimlendirileceği anlamına gelmez.
DateTime değeri hem ms excel'in hem de Aspose.Cells'in veri modelinde sayısal değer olarak tutuldu.
Sayısal değerin sayısal değer olarak mı yoksa tarih saat olarak mı alınacağı
bu hücreye uygulanan sayı biçimine bağlıdır. Bu hücre tarih saat olarak biçimlendirilmemişse,
girdiğiniz şey DateTime olsa bile sayısal bir değer olarak görüntülenecektir.
###  Örnek

Bu örnek, DateTime değerinin bir hücreye nasıl ayarlanacağını ve bunun tarih saat olarak görüntülenmesini nasıl sağlayacağınızı gösterir.

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


##  put_value {#any}
Hücreye bir nesne değeri koyar.



```python
def put_value(self, object_value):
    ...
```


| Parametre| Tip| Tanım|
| :- | :- | :- |
| object_value | any | Girdi değeri|


##  put_value {#str-bool}
Hücreye bir dize değeri koyar ve uygunsa değeri diğer veri türüne dönüştürür.



```python
def put_value(self, string_value, is_converted):
    ...
```


| Parametre| Tip| Tanım|
| :- | :- | :- |
| string_value | str | Girdi değeri|
| is_converted | bool | Doğru: uygunsa diğer veri türüne dönüştürülür.|


##  put_value {#str-bool-bool}
Hücreye bir değer koyar, uygunsa değer başka bir veri tipine dönüştürülür ve hücrenin sayı formatı sıfırlanır.



```python
def put_value(self, string_value, is_converted, set_style):
    ...
```


| Parametre| Tip| Tanım|
| :- | :- | :- |
| string_value | str | Girdi değeri|
| is_converted | bool | Doğru: uygunsa diğer veri türüne dönüştürülür.|
| set_style | bool | Doğru: diğer veri türlerine dönüştürürken sayı biçimini hücrenin stiline göre ayarlayın|



###  Ayrıca bakınız
* modül [`aspose.cells`](../../)
* sınıf [`Cell`](/cells/python-net/tr/aspose.cells/cell)
