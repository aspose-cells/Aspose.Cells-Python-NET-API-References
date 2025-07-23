---
title: replace yöntemi
second_title: Aspose.Cells for Python via .NET API Referanslar
description:
type: docs
weight: 350
url: /tr/aspose.cells/workbook/replace/
is_root: false
---
##  replace(self, place_holder, new_value) {#str-str}
Bir hücrenin değerini yeni bir dizeyle değiştirir.



```python

def replace(self, place_holder, new_value):
    ...
```


| Parametre| Tip| Tanım|
| :- | :- | :- |
| place_holder | str | Cell yer tutucu|
| new_value | str | Değiştirilecek dize değeri|

###  Örnek

```python
from aspose.cells import Workbook

workbook = Workbook()
# ......
workbook.replace("AnOldValue", "NewValue")

```


##  replace(self, place_holder, new_value) {#str-int}
Bir hücrenin değerini yeni bir tam sayı ile değiştirir.



```python

def replace(self, place_holder, new_value):
    ...
```


| Parametre| Tip| Tanım|
| :- | :- | :- |
| place_holder | str | Cell yer tutucu|
| new_value | int | Değiştirilecek tam sayı değeri|

###  Örnek

```python
from aspose.cells import Workbook

workbook = Workbook()
# ......
newValue = 100
workbook.replace("AnOldValue", newValue)

```


##  replace(self, place_holder, new_value) {#str-float}
Bir hücrenin değerini yeni bir double ile değiştirir.



```python

def replace(self, place_holder, new_value):
    ...
```


| Parametre| Tip| Tanım|
| :- | :- | :- |
| place_holder | str | Cell yer tutucu|
| new_value | float | Değiştirilecek çift değer|

###  Örnek

```python
from aspose.cells import Workbook

workbook = Workbook()
# ......
newValue = 100.0
workbook.replace("AnOldValue", newValue)

```


##  replace(self, bool_value, new_value) {#bool-any}
Hücrelerin değerlerini yeni verilerle değiştirir.



```python

def replace(self, bool_value, new_value):
    ...
```


| Parametre| Tip| Tanım|
| :- | :- | :- |
| bool_value | bool | Değiştirilecek boolean değeri.|
| new_value | any | Yeni değer. Dize, tam sayı, çift sayı veya DateTime değeri olabilir.|


##  replace(self, int_value, new_value) {#int-any}
Hücrelerin değerlerini yeni verilerle değiştirir.



```python

def replace(self, int_value, new_value):
    ...
```


| Parametre| Tip| Tanım|
| :- | :- | :- |
| int_value | int | Değiştirilecek tam sayı değeri.|
| new_value | any | Yeni değer. Dize, tam sayı, çift sayı veya DateTime değeri olabilir.|


##  replace(self, place_holder, new_values, is_vertical) {#str-list-bool}
Bir hücrenin değerini yeni bir dize dizisiyle değiştirir.



```python

def replace(self, place_holder, new_values, is_vertical):
    ...
```


| Parametre| Tip| Tanım|
| :- | :- | :- |
| place_holder | str | Cell yer tutucu|
| new_values | list | Değiştirilecek dize dizisi|
| is_vertical | bool | Doğru - Dikey, Yanlış - Yatay|

###  Örnek

```python
from aspose.cells import Workbook

workbook = Workbook()
# ......
newValues = ["Tom", "Alice", "Jerry"]
workbook.replace("AnOldValue", newValues, True)

```


##  replace(self, place_holder, new_values, is_vertical) {#str-list-bool}
Hücrelerin değerlerini bir tamsayı dizisiyle değiştirir.



```python

def replace(self, place_holder, new_values, is_vertical):
    ...
```


| Parametre| Tip| Tanım|
| :- | :- | :- |
| place_holder | str | Cell yer tutucu|
| new_values | list | Değiştirilecek tamsayı dizisi|
| is_vertical | bool | Doğru - Dikey, Yanlış - Yatay|

###  Örnek

```python
from aspose.cells import Workbook

workbook = Workbook()
# ......
newValues = [1, 2, 3]
workbook.replace("AnOldValue", newValues, True)

```


##  replace(self, place_holder, new_values, is_vertical) {#str-list-bool}
Hücrelerin değerlerini double diziyle değiştirir.



```python

def replace(self, place_holder, new_values, is_vertical):
    ...
```


| Parametre| Tip| Tanım|
| :- | :- | :- |
| place_holder | str | Cell yer tutucu|
| new_values | list | Değiştirilecek çift dizi|
| is_vertical | bool | Doğru - Dikey, Yanlış - Yatay|

###  Örnek

```python
from aspose.cells import Workbook

workbook = Workbook()
# ......
newValues = [1.23, 2.56, 3.14159]
workbook.replace("AnOldValue", newValues, True)

```


##  replace(self, place_holder, new_value, options) {#str-str-aspose.cells.ReplaceOptions}
Bir hücrenin değerini yeni bir dizeyle değiştirir.



```python

def replace(self, place_holder, new_value, options):
    ...
```


| Parametre| Tip| Tanım|
| :- | :- | :- |
| place_holder | str | Cell yer tutucu|
| new_value | str | Değiştirilecek dize değeri|
| options | [`ReplaceOptions`](/cells/python-net/tr/aspose.cells/replaceoptions) | Değiştirme seçenekleri|



###  Ayrıca bakınız
* modül [`aspose.cells`](../../)
* sınıf [`Workbook`](/cells/python-net/tr/aspose.cells/workbook)
