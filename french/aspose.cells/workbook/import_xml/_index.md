---
title: méthode import_xml
second_title: Aspose.Cells for Python via .NET API Références
description:
type: docs
weight: 230
url: /fr/aspose.cells/workbook/import_xml/
is_root: false
---
##  import_xml(self, url, sheet_name, row, col) {#str-str-int-int}
Importe/met à jour un fichier de données XML dans le classeur.



```python

def import_xml(self, url, sheet_name, row, col):
    ...
```


| Paramètre| Taper| Description|
| :- | :- | :- |
| url | str | l'url/chemin du fichier xml.|
| sheet_name | str | le nom de la feuille de destination.|
| row | int | la ligne de destination|
| col | int | la colonne de destination|

###  Exemple

Le code suivant importe des données XML dans la feuille de calcul « Feuille 1 » à Cell A1.

```python
from aspose.cells import Workbook

wb = Workbook("Book1.xlsx")
wb.import_xml("xml.xml", "Sheet1", 0, 0)
wb.save("output.xlsx")

```


##  import_xml(self, stream, sheet_name, row, col) {#io.RawIOBase-str-int-int}
Importe/met à jour un fichier de données XML dans le classeur.



```python

def import_xml(self, stream, sheet_name, row, col):
    ...
```


| Paramètre| Taper| Description|
| :- | :- | :- |
| stream | io.RawIOBase | le flux de fichiers xml.|
| sheet_name | str | le nom de la feuille de destination.|
| row | int | la ligne de destination.|
| col | int | la colonne de destination.|



###  Voir également
* module [`aspose.cells`](../../)
* classe [`Workbook`](/cells/python-net/fr/aspose.cells/workbook)
