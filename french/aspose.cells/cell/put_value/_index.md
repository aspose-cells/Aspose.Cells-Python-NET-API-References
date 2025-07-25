---
title: méthode put_value
second_title: Aspose.Cells for Python via .NET API Références
description:
type: docs
weight: 290
url: /fr/aspose.cells/cell/put_value/
is_root: false
---
##  put_value(self, bool_value) {#bool}
Place une valeur booléenne dans la cellule.



```python

def put_value(self, bool_value):
    ...
```


| Paramètre| Taper| Description|
| :- | :- | :- |
| bool_value | bool |  |


##  put_value(self, int_value) {#int}
Met une valeur entière dans la cellule.



```python

def put_value(self, int_value):
    ...
```


| Paramètre| Taper| Description|
| :- | :- | :- |
| int_value | int | Valeur d'entrée|


##  put_value(self, double_value) {#float}
Met une valeur double dans la cellule.



```python

def put_value(self, double_value):
    ...
```


| Paramètre| Taper| Description|
| :- | :- | :- |
| double_value | float | Valeur d'entrée|


##  put_value(self, string_value) {#str}
Place une valeur de chaîne dans la cellule.



```python

def put_value(self, string_value):
    ...
```


| Paramètre| Taper| Description|
| :- | :- | :- |
| string_value | str | Valeur d'entrée|


##  put_value(self, date_time) {#DateTime}
Place une valeur DateTime dans la cellule.



```python

def put_value(self, date_time):
    ...
```


| Paramètre| Taper| Description|
| :- | :- | :- |
| date_time | DateTime | Valeur d'entrée|
###  Remarques

La définition d'une valeur DateTime pour une cellule ne signifie pas que la cellule sera automatiquement formatée en tant que date et heure.
La valeur DateTime a été conservée en tant que valeur numérique dans le modèle de données de MS Excel et de Aspose.Cells.
Si la valeur numérique sera considérée comme la valeur numérique elle-même ou comme la date et l'heure
dépend du format numérique appliqué à cette cellule. Si cette cellule n'a pas été formatée en date et heure,
il sera affiché sous forme de valeur numérique même si ce que vous saisissez est DateTime.
###  Exemple

Cet exemple montre comment définir la valeur DateTime sur une cellule et la faire afficher sous forme de date et d'heure.

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
Place une valeur d'objet dans la cellule.



```python

def put_value(self, object_value):
    ...
```


| Paramètre| Taper| Description|
| :- | :- | :- |
| object_value | any | valeur d'entrée|


##  put_value(self, string_value, is_converted) {#str-bool}
Place une valeur de chaîne dans la cellule et convertit la valeur en un autre type de données si approprié.



```python

def put_value(self, string_value, is_converted):
    ...
```


| Paramètre| Taper| Description|
| :- | :- | :- |
| string_value | str | Valeur d'entrée|
| is_converted | bool | Vrai : converti en un autre type de données si approprié.|


##  put_value(self, string_value, is_converted, set_style) {#str-bool-bool}
Place une valeur dans la cellule, si nécessaire, la valeur sera convertie en un autre type de données et le format numérique de la cellule sera réinitialisé.



```python

def put_value(self, string_value, is_converted, set_style):
    ...
```


| Paramètre| Taper| Description|
| :- | :- | :- |
| string_value | str | Valeur d'entrée|
| is_converted | bool | Vrai : converti en un autre type de données si approprié.|
| set_style | bool | Vrai : définir le format numérique sur le style de la cellule lors de la conversion vers un autre type de données|



###  Voir également
* module [`aspose.cells`](../../)
* classe [`Cell`](/cells/python-net/fr/aspose.cells/cell)
