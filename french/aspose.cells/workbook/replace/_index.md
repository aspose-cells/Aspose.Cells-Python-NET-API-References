---
title: méthode replace
second_title: Aspose.Cells for Python via .NET API Références
description:
type: docs
weight: 350
url: /fr/aspose.cells/workbook/replace/
is_root: false
---
##  replace(self, place_holder, new_value) {#str-str}
Remplace la valeur d'une cellule par une nouvelle chaîne.



```python

def replace(self, place_holder, new_value):
    ...
```


| Paramètre| Taper| Description|
| :- | :- | :- |
| place_holder | str | Cell espace réservé|
| new_value | str | Valeur de chaîne à remplacer|

###  Exemple

```python
from aspose.cells import Workbook

workbook = Workbook()
# ......
workbook.replace("AnOldValue", "NewValue")

```


##  replace(self, place_holder, new_value) {#str-int}
Remplace la valeur d'une cellule par un nouvel entier.



```python

def replace(self, place_holder, new_value):
    ...
```


| Paramètre| Taper| Description|
| :- | :- | :- |
| place_holder | str | Cell espace réservé|
| new_value | int | Valeur entière à remplacer|

###  Exemple

```python
from aspose.cells import Workbook

workbook = Workbook()
# ......
newValue = 100
workbook.replace("AnOldValue", newValue)

```


##  replace(self, place_holder, new_value) {#str-float}
Remplace la valeur d'une cellule par un nouveau double.



```python

def replace(self, place_holder, new_value):
    ...
```


| Paramètre| Taper| Description|
| :- | :- | :- |
| place_holder | str | Cell espace réservé|
| new_value | float | Double valeur à remplacer|

###  Exemple

```python
from aspose.cells import Workbook

workbook = Workbook()
# ......
newValue = 100.0
workbook.replace("AnOldValue", newValue)

```


##  replace(self, bool_value, new_value) {#bool-any}
Remplace les valeurs des cellules par de nouvelles données.



```python

def replace(self, bool_value, new_value):
    ...
```


| Paramètre| Taper| Description|
| :- | :- | :- |
| bool_value | bool | La valeur booléenne à remplacer.|
| new_value | any | Nouvelle valeur. Il peut s'agir d'une chaîne, d'un entier, d'un double ou d'une valeur DateTime.|


##  replace(self, int_value, new_value) {#int-any}
Remplace les valeurs des cellules par de nouvelles données.



```python

def replace(self, int_value, new_value):
    ...
```


| Paramètre| Taper| Description|
| :- | :- | :- |
| int_value | int | La valeur entière à remplacer.|
| new_value | any | Nouvelle valeur. Il peut s'agir d'une chaîne, d'un entier, d'un double ou d'une valeur DateTime.|


##  replace(self, place_holder, new_values, is_vertical) {#str-list-bool}
Remplace la valeur d'une cellule par un nouveau tableau de chaînes.



```python

def replace(self, place_holder, new_values, is_vertical):
    ...
```


| Paramètre| Taper| Description|
| :- | :- | :- |
| place_holder | str | Cell espace réservé|
| new_values | list | Tableau de chaînes à remplacer|
| is_vertical | bool | Vrai - Vertical, Faux - Horizontal|

###  Exemple

```python
from aspose.cells import Workbook

workbook = Workbook()
# ......
newValues = ["Tom", "Alice", "Jerry"]
workbook.replace("AnOldValue", newValues, True)

```


##  replace(self, place_holder, new_values, is_vertical) {#str-list-bool}
Remplace les valeurs des cellules par un tableau d'entiers.



```python

def replace(self, place_holder, new_values, is_vertical):
    ...
```


| Paramètre| Taper| Description|
| :- | :- | :- |
| place_holder | str | Cell espace réservé|
| new_values | list | Tableau d'entiers à remplacer|
| is_vertical | bool | Vrai - Vertical, Faux - Horizontal|

###  Exemple

```python
from aspose.cells import Workbook

workbook = Workbook()
# ......
newValues = [1, 2, 3]
workbook.replace("AnOldValue", newValues, True)

```


##  replace(self, place_holder, new_values, is_vertical) {#str-list-bool}
Remplace les valeurs des cellules par un tableau double.



```python

def replace(self, place_holder, new_values, is_vertical):
    ...
```


| Paramètre| Taper| Description|
| :- | :- | :- |
| place_holder | str | Cell espace réservé|
| new_values | list | Double tableau à remplacer|
| is_vertical | bool | Vrai - Vertical, Faux - Horizontal|

###  Exemple

```python
from aspose.cells import Workbook

workbook = Workbook()
# ......
newValues = [1.23, 2.56, 3.14159]
workbook.replace("AnOldValue", newValues, True)

```


##  replace(self, place_holder, new_value, options) {#str-str-aspose.cells.ReplaceOptions}
Remplace la valeur d'une cellule par une nouvelle chaîne.



```python

def replace(self, place_holder, new_value, options):
    ...
```


| Paramètre| Taper| Description|
| :- | :- | :- |
| place_holder | str | Cell espace réservé|
| new_value | str | Valeur de chaîne à remplacer|
| options | [`ReplaceOptions`](/cells/python-net/fr/aspose.cells/replaceoptions) | Les options de remplacement|



###  Voir également
* module [`aspose.cells`](../../)
* classe [`Workbook`](/cells/python-net/fr/aspose.cells/workbook)
