---
title: طريقة replace
second_title: Aspose.Cells for Python via .NET API المراجع
description:
type: docs
weight: 350
url: /ar/aspose.cells/workbook/replace/
is_root: false
---
##  replace(self, place_holder, new_value) {#str-str}
استبدال قيمة الخلية بسلسلة جديدة.



```python

def replace(self, place_holder, new_value):
    ...
```


| معامل| يكتب| وصف|
| :- | :- | :- |
| place_holder | str | Cell عنصر نائب|
| new_value | str | قيمة السلسلة المراد استبدالها|

###  مثال

```python
from aspose.cells import Workbook

workbook = Workbook()
# ......
workbook.replace("AnOldValue", "NewValue")

```


##  replace(self, place_holder, new_value) {#str-int}
استبدال قيمة الخلية برقم صحيح جديد.



```python

def replace(self, place_holder, new_value):
    ...
```


| معامل| يكتب| وصف|
| :- | :- | :- |
| place_holder | str | Cell عنصر نائب|
| new_value | int | القيمة الصحيحة المراد استبدالها|

###  مثال

```python
from aspose.cells import Workbook

workbook = Workbook()
# ......
newValue = 100
workbook.replace("AnOldValue", newValue)

```


##  replace(self, place_holder, new_value) {#str-float}
استبدال قيمة الخلية بقيمة مزدوجة جديدة.



```python

def replace(self, place_holder, new_value):
    ...
```


| معامل| يكتب| وصف|
| :- | :- | :- |
| place_holder | str | Cell عنصر نائب|
| new_value | float | قيمة مزدوجة للاستبدال|

###  مثال

```python
from aspose.cells import Workbook

workbook = Workbook()
# ......
newValue = 100.0
workbook.replace("AnOldValue", newValue)

```


##  replace(self, bool_value, new_value) {#bool-any}
استبدال قيم الخلايا ببيانات جديدة.



```python

def replace(self, bool_value, new_value):
    ...
```


| معامل| يكتب| وصف|
| :- | :- | :- |
| bool_value | bool | القيمة المنطقية التي يجب استبدالها.|
| new_value | any | قيمة جديدة. يمكن أن تكون سلسلة نصية، أو عددًا صحيحًا، أو قيمة مزدوجة، أو قيمة تاريخ ووقت.|


##  replace(self, int_value, new_value) {#int-any}
استبدال قيم الخلايا ببيانات جديدة.



```python

def replace(self, int_value, new_value):
    ...
```


| معامل| يكتب| وصف|
| :- | :- | :- |
| int_value | int | القيمة الصحيحة التي يجب استبدالها.|
| new_value | any | قيمة جديدة. يمكن أن تكون سلسلة نصية، أو عددًا صحيحًا، أو قيمة مزدوجة، أو قيمة تاريخ ووقت.|


##  replace(self, place_holder, new_values, is_vertical) {#str-list-bool}
استبدال قيمة الخلية بمصفوفة سلسلة جديدة.



```python

def replace(self, place_holder, new_values, is_vertical):
    ...
```


| معامل| يكتب| وصف|
| :- | :- | :- |
| place_holder | str | Cell عنصر نائب|
| new_values | list | مجموعة من السلاسل المراد استبدالها|
| is_vertical | bool | صحيح - عمودي، خطأ - أفقي|

###  مثال

```python
from aspose.cells import Workbook

workbook = Workbook()
# ......
newValues = ["Tom", "Alice", "Jerry"]
workbook.replace("AnOldValue", newValues, True)

```


##  replace(self, place_holder, new_values, is_vertical) {#str-list-bool}
استبدال قيم الخلايا بمصفوفة عددية صحيحة.



```python

def replace(self, place_holder, new_values, is_vertical):
    ...
```


| معامل| يكتب| وصف|
| :- | :- | :- |
| place_holder | str | Cell عنصر نائب|
| new_values | list | مجموعة عدد صحيح لاستبدالها|
| is_vertical | bool | صحيح - عمودي، خطأ - أفقي|

###  مثال

```python
from aspose.cells import Workbook

workbook = Workbook()
# ......
newValues = [1, 2, 3]
workbook.replace("AnOldValue", newValues, True)

```


##  replace(self, place_holder, new_values, is_vertical) {#str-list-bool}
استبدال قيم الخلايا بمصفوفة مزدوجة.



```python

def replace(self, place_holder, new_values, is_vertical):
    ...
```


| معامل| يكتب| وصف|
| :- | :- | :- |
| place_holder | str | Cell عنصر نائب|
| new_values | list | مجموعة مزدوجة للاستبدال|
| is_vertical | bool | صحيح - عمودي، خطأ - أفقي|

###  مثال

```python
from aspose.cells import Workbook

workbook = Workbook()
# ......
newValues = [1.23, 2.56, 3.14159]
workbook.replace("AnOldValue", newValues, True)

```


##  replace(self, place_holder, new_value, options) {#str-str-aspose.cells.ReplaceOptions}
استبدال قيمة الخلية بسلسلة جديدة.



```python

def replace(self, place_holder, new_value, options):
    ...
```


| معامل| يكتب| وصف|
| :- | :- | :- |
| place_holder | str | Cell عنصر نائب|
| new_value | str | قيمة السلسلة المراد استبدالها|
| options | [`ReplaceOptions`](/cells/python-net/ar/aspose.cells/replaceoptions) | خيارات الاستبدال|



###  أنظر أيضا
* الوحدة [`aspose.cells`](../../)
* فئة [`Workbook`](/cells/python-net/ar/aspose.cells/workbook)
