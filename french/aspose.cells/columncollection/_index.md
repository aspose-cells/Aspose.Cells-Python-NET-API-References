---
title: ColumnCollection classe
second_title: Aspose.Cells for Python via .NET API Références
description:
type: docs
weight: 250
url: /fr/aspose.cells/columncollection/
is_root: false
---
##  ColumnCollection classe
Collection des [`Column`](/cells/python-net/fr/aspose.cells/column) objets qui représentent les colonnes individuelles (paramètres) dans une feuille de calcul.
L'objet Column représente uniquement les paramètres tels que la largeur de la colonne, les styles, etc. pour l'ensemble de la colonne,
n'a rien à voir avec le fait qu'il y ait des cellules non vides (données) ou non dans la colonne correspondante.
Et le « Count » de cette collection ne représente que le nombre d'objets Column qui ont été instanciés dans cette collection,
n'a rien à voir avec le fait qu'il y ait des cellules non vides (données) ou non dans la feuille de calcul.



Le type ColumnCollection expose les membres suivants :

###  Propriétés
| Propriété| Description|
| :- | :- |
| [capacity](/cells/python-net/fr/aspose.cells/columncollection/capacity) | Obtient ou définit le nombre d'éléments que la liste de tableaux peut contenir.|


###  Méthodes
| Méthode| Description|
| :- | :- |
| [`copy_to(self, array)`](/cells/python-net/fr/aspose.cells/columncollection/copy_to/#list) |Copie la liste de tableaux entière dans une liste de tableaux unidimensionnelle compatible, en commençant au début de la liste de tableaux cible.|
| [`copy_to(self, index, array, array_index, count)`](/cells/python-net/fr/aspose.cells/columncollection/copy_to/#int-list-int-int) | Copie une plage d'éléments de la liste de tableaux vers une liste de tableaux unidimensionnelle compatible, en commençant à l'index spécifié de la liste de tableaux cible.|
| [`index_of(self, item, index)`](/cells/python-net/fr/aspose.cells/columncollection/index_of/#aspose.cells.column-int) | Recherche l'objet spécifié et renvoie l'index de base zéro de la première occurrence dans la plage d'éléments de la liste de tableaux qui s'étend de l'index spécifié au dernier élément.|
| [`index_of(self, item, index, count)`](/cells/python-net/fr/aspose.cells/columncollection/index_of/#aspose.cells.column-int-int) | Recherche l'objet spécifié et renvoie l'index de base zéro de la première occurrence dans la plage d'éléments de la liste de tableaux qui commence à l'index spécifié et contient le nombre d'éléments spécifié.|
| [`last_index_of(self, item)`](/cells/python-net/fr/aspose.cells/columncollection/last_index_of/#aspose.cells.column) | Recherche l'objet spécifié et renvoie l'index de base zéro de la dernière occurrence dans la liste de tableaux entière.|
| [`last_index_of(self, item, index)`](/cells/python-net/fr/aspose.cells/columncollection/last_index_of/#aspose.cells.column-int) |Recherche l'objet spécifié et renvoie l'index de base zéro de la dernière occurrence dans la plage d'éléments de la liste de tableaux qui s'étend du premier élément à l'index spécifié.|
| [`last_index_of(self, item, index, count)`](/cells/python-net/fr/aspose.cells/columncollection/last_index_of/#aspose.cells.column-int-int) | Recherche l'objet spécifié et renvoie l'index de base zéro de la dernière occurrence dans la plage d'éléments de la liste de tableaux qui contient le nombre spécifié d'éléments et se termine à l'index spécifié.|
| [`get_by_index(self, index)`](/cells/python-net/fr/aspose.cells/columncollection/get_by_index/#int) | Obtient l'objet colonne par l'index.|
| [`get_column_by_index(self, index)`](/cells/python-net/fr/aspose.cells/columncollection/get_column_by_index/#int) | Obtient l'objet [`Column`](/cells/python-net/fr/aspose.cells/column) par la position dans la liste.|
| [`get(self, column_index)`](/cells/python-net/fr/aspose.cells/columncollection/get/#int) | Ajoutez API for Python via .Net.|
| [`binary_search(self, item)`](/cells/python-net/fr/aspose.cells/columncollection/binary_search/#aspose.cells.column) | Recherche dans la liste entière de tableaux triés un élément à l'aide du comparateur par défaut et renvoie l'index de base zéro de l'élément.|



###  Exemple

```python
from aspose.cells import BackgroundType, StyleFlag, Workbook
from aspose.pydrawing import Color

# Instantiating a Workbook object
workbook = Workbook()
# Obtaining the reference of the first worksheet
worksheet = workbook.worksheets[0]
# Add new Style to Workbook
style = workbook.create_style()
# Setting the background color to Blue
style.foreground_color = Color.blue
# setting Background Pattern
style.pattern = BackgroundType.SOLID
# New Style Flag
styleFlag = StyleFlag()
# Set All Styles
styleFlag.all = True
# Change the default width of first ten columns
for i in range(10):
    worksheet.cells.columns[i].width = 20.0
# Get the Column with non default formatting
columns = worksheet.cells.columns
for column in columns:
    # Apply Style to first ten Columns
    column.apply_style(style, styleFlag)
# Saving the Excel file
workbook.save("book1.xls")

```

###  Voir également
* module [`aspose.cells`](..)
* classe [`Column`](/cells/python-net/fr/aspose.cells/column)
