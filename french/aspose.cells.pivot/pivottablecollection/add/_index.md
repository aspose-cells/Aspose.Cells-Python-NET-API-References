---
title: add méthode
second_title: Aspose.Cells for Python via .NET API Références
description:
type: docs
weight: 20
url: /fr/aspose.cells.pivot/pivottablecollection/add/
is_root: false
---
##  add(source_data, dest_cell_name, table_name) {#str-str-str}
Ajoute un nouveau cache de tableau croisé dynamique à une collection PivotCaches.


###  Retour

Le nouvel index de cache ajouté.


```python
def add(self, source_data, dest_cell_name, table_name):
    ...
```


| Paramètre| Taper| Description|
| :- | :- | :- |
| source_data | str | Les données du nouveau cache de tableau croisé dynamique.|
| dest_cell_name | str |La cellule dans le coin supérieur gauche de la plage de destination du rapport de tableau croisé dynamique.|
| table_name | str | Nom du nouveau rapport de tableau croisé dynamique.|


##  add(pivot_table, dest_cell_name, table_name) {#PivotTable-str-str}
Ajoute un nouvel objet de tableau croisé dynamique à la collection à partir d'un autre tableau croisé dynamique.


###  Retour

Le nouvel index de tableau croisé dynamique ajouté.


```python
def add(self, pivot_table, dest_cell_name, table_name):
    ...
```


| Paramètre| Taper| Description|
| :- | :- | :- |
| pivot_table | [PivotTable](/cells/python-net/fr/aspose.cells.pivot/pivottable) | Le tableau croisé dynamique source.|
| dest_cell_name | str |La cellule dans le coin supérieur gauche de la plage de destination du rapport de tableau croisé dynamique.|
| table_name | str | Nom du nouveau rapport de tableau croisé dynamique.|


##  add(source_data, dest_cell_name, table_name, use_same_source) {#str-str-str-bool}
Ajoute un nouveau cache de tableau croisé dynamique à une collection PivotCaches.


###  Retour

Le nouvel index de cache ajouté.


```python
def add(self, source_data, dest_cell_name, table_name, use_same_source):
    ...
```


| Paramètre| Taper| Description|
| :- | :- | :- |
| source_data | str | Les données du nouveau cache de tableau croisé dynamique.|
| dest_cell_name | str |La cellule dans le coin supérieur gauche de la plage de destination du rapport de tableau croisé dynamique.|
| table_name | str | Nom du nouveau rapport de tableau croisé dynamique.|
| use_same_source | bool | Indique si la même source de données est utilisée lorsqu'un autre tableau croisé dynamique existant a utilisé cette source de données.<br/> Si la propriété est vraie, cela économisera de la mémoire.|


##  add(source_data, row, column, table_name) {#str-int-int-str}
Ajoute un nouveau cache de tableau croisé dynamique à une collection PivotCaches.


###  Retour

Le nouvel index de cache ajouté.


```python
def add(self, source_data, row, column, table_name):
    ...
```


| Paramètre| Taper| Description|
| :- | :- | :- |
| source_data | str | La plage de cellules de données pour le nouveau tableau croisé dynamique.Exemple : Sheet1!A1:C8|
| row | int | Index de ligne de la cellule dans le coin supérieur gauche de la plage de destination du rapport de tableau croisé dynamique.|
| column | int | Index de colonne de la cellule dans le coin supérieur gauche de la plage de destination du rapport de tableau croisé dynamique.|
| table_name | str | Nom du nouveau rapport de tableau croisé dynamique.|


##  add(pivot_table, row, column, table_name) {#PivotTable-int-int-str}
Ajoute un nouvel objet de tableau croisé dynamique à la collection à partir d'un autre tableau croisé dynamique.


###  Retour

Le nouvel index de tableau croisé dynamique ajouté.


```python
def add(self, pivot_table, row, column, table_name):
    ...
```


| Paramètre| Taper| Description|
| :- | :- | :- |
| pivot_table | [PivotTable](/cells/python-net/fr/aspose.cells.pivot/pivottable) | Le tableau croisé dynamique source.|
| row | int | Index de ligne de la cellule dans le coin supérieur gauche de la plage de destination du rapport de tableau croisé dynamique.|
| column | int | Index de colonne de la cellule dans le coin supérieur gauche de la plage de destination du rapport de tableau croisé dynamique.|
| table_name | str | Nom du nouveau rapport de tableau croisé dynamique.|


##  add(source_data, row, column, table_name, use_same_source) {#str-int-int-str-bool}
Ajoute un nouveau cache de tableau croisé dynamique à une collection PivotCaches.


###  Retour

Le nouvel index de cache ajouté.


```python
def add(self, source_data, row, column, table_name, use_same_source):
    ...
```


| Paramètre| Taper| Description|
| :- | :- | :- |
| source_data | str | La plage de cellules de données pour le nouveau tableau croisé dynamique.Exemple : Sheet1!A1:C8|
| row | int | Index de ligne de la cellule dans le coin supérieur gauche de la plage de destination du rapport de tableau croisé dynamique.|
| column | int | Index de colonne de la cellule dans le coin supérieur gauche de la plage de destination du rapport de tableau croisé dynamique.|
| table_name | str | Nom du nouveau rapport de tableau croisé dynamique.|
| use_same_source | bool | Indique si la même source de données est utilisée lorsqu'un autre tableau croisé dynamique existant a utilisé cette source de données.<br/> Si la propriété est vraie, cela économisera de la mémoire.|


##  add(source_data, is_auto_page, page_fields, dest_cell_name, table_name) {#list-bool-PivotPageFields-str-str}
Ajoute un nouvel objet de tableau croisé dynamique à la collection avec plusieurs plages de consolidation comme source de données.


###  Retour

Le nouvel index de tableau croisé dynamique ajouté.


```python
def add(self, source_data, is_auto_page, page_fields, dest_cell_name, table_name):
    ...
```


| Paramètre| Taper| Description|
| :- | :- | :- |
| source_data | list | Les plages de consolidation multiples, telles que {"Sheet1!A1:C8","Sheet2!A1:B8"} |
| is_auto_page | bool | Si auto créer un champ de page unique.<br/>Si vrai, le paramètre pageFields suivant sera ignoré.|
| page_fields | [PivotPageFields](/cells/python-net/fr/aspose.cells.pivot/pivotpagefields) | Les éléments de champ de la page pivot.|
| dest_cell_name | str | destCellName Le nom du nouveau rapport de tableau croisé dynamique.|
| table_name | str | le nom du nouveau rapport de tableau croisé dynamique.|


##  add(source_data, is_auto_page, page_fields, row, column, table_name) {#list-bool-PivotPageFields-int-int-str}
Ajoute un nouvel objet de tableau croisé dynamique à la collection avec plusieurs plages de consolidation comme source de données.


###  Retour

Le nouvel index de tableau croisé dynamique ajouté.


```python
def add(self, source_data, is_auto_page, page_fields, row, column, table_name):
    ...
```


| Paramètre| Taper| Description|
| :- | :- | :- |
| source_data | list | Les plages de consolidation multiples, telles que {"Sheet1!A1:C8","Sheet2!A1:B8"} |
| is_auto_page | bool | Si auto créer un champ de page unique.<br/> Si vrai, le paramètre pageFields suivant sera ignoré|
| page_fields | [PivotPageFields](/cells/python-net/fr/aspose.cells.pivot/pivotpagefields) | Les éléments de champ de la page pivot.|
| row | int | Index de ligne de la cellule dans le coin supérieur gauche de la plage de destination du rapport de tableau croisé dynamique.|
| column | int | Index de colonne de la cellule dans le coin supérieur gauche de la plage de destination du rapport de tableau croisé dynamique.|
| table_name | str | Nom du nouveau rapport de tableau croisé dynamique.|



###  Voir également
* module [aspose.cells.pivot](../../)
* classe [PivotTableCollection](/cells/python-net/fr/aspose.cells.pivot/pivottablecollection)
