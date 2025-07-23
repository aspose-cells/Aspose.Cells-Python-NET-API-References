---
title: méthode add
second_title: Aspose.Cells for Python via .NET API Références
description:
type: docs
weight: 20
url: /fr/aspose.cells/hyperlinkcollection/add/
is_root: false
---
##  add(self, cell_name, total_rows, total_columns, address) {#str-int-int-str}
Ajoute un lien hypertexte vers une cellule spécifiée ou une plage de cellules.


###  Retour

[`Hyperlink`](/cells/python-net/fr/aspose.cells/hyperlink) index d'objet.


```python

def add(self, cell_name, total_rows, total_columns, address):
    ...
```


| Paramètre| Taper| Description|
| :- | :- | :- |
| cell_name | str | Cell nom.|
| total_rows | int | Nombre de lignes dans cette plage d'hyperliens.|
| total_columns | int |Nombre de colonnes de cette plage d'hyperliens.|
| address | str | Adresse de l'hyperlien.|


##  add(self, first_row, first_column, total_rows, total_columns, address) {#int-int-int-int-str}
Ajoute un lien hypertexte vers une cellule spécifiée ou une plage de cellules.


###  Retour

[`Hyperlink`](/cells/python-net/fr/aspose.cells/hyperlink) index d'objet.


```python

def add(self, first_row, first_column, total_rows, total_columns, address):
    ...
```


| Paramètre| Taper| Description|
| :- | :- | :- |
| first_row | int | Première ligne de la plage d'hyperliens.|
| first_column | int | Première colonne de la plage d'hyperliens.|
| total_rows | int | Nombre de lignes dans cette plage d'hyperliens.|
| total_columns | int |Nombre de colonnes de cette plage d'hyperliens.|
| address | str | Adresse de l'hyperlien.|

###  Exemple

```python
from aspose.cells import Workbook

# Instantiating a Workbook object
excel = Workbook()
worksheet = excel.worksheets[0]
worksheet.hyperlinks.add("A4", 1, 1, "http://www.aspose.com")
worksheet.hyperlinks.add("A5", 1, 1, "c:\\book1.xls")

```


##  add(self, start_cell_name, end_cell_name, address, text_to_display, screen_tip) {#str-str-str-str-str}
Ajoute un lien hypertexte vers une cellule spécifiée ou une plage de cellules.


###  Retour

[`Hyperlink`](/cells/python-net/fr/aspose.cells/hyperlink) index d'objet.


```python

def add(self, start_cell_name, end_cell_name, address, text_to_display, screen_tip):
    ...
```


| Paramètre| Taper| Description|
| :- | :- | :- |
| start_cell_name | str |La cellule en haut à gauche de la plage.|
| end_cell_name | str | La cellule en bas à droite de la plage.|
| address | str | Adresse de l'hyperlien.|
| text_to_display | str | Le texte à afficher pour l'hyperlien spécifié.|
| screen_tip | str | Le texte de l'info-bulle pour l'hyperlien spécifié.|



###  Voir également
* module [`aspose.cells`](../../)
* classe [`Hyperlink`](/cells/python-net/fr/aspose.cells/hyperlink)
* classe [`HyperlinkCollection`](/cells/python-net/fr/aspose.cells/hyperlinkcollection)
