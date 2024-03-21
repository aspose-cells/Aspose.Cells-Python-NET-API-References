---
title: Row classe
second_title: Aspose.Cells for Python via .NET API Références
description:
type: docs
weight: 1340
url: /fr/aspose.cells/row/
is_root: false
---
##  Row classe
Représente une seule ligne dans une feuille de calcul.



Le type Row expose les membres suivants :

###  Propriétés
| Propriété| Description|
| :- | :- |
| [is_blank](/cells/python-net/fr/aspose.cells/row/is_blank) | Indique si la ligne contient des données|
| [is_collapsed](/cells/python-net/fr/aspose.cells/row/is_collapsed) | si la ligne est réduite|
| [height](/cells/python-net/fr/aspose.cells/row/height) | Obtient et définit la hauteur de ligne en unité de points.|
| [is_hidden](/cells/python-net/fr/aspose.cells/row/is_hidden) | Indique si la ligne est masquée.|
| [index](/cells/python-net/fr/aspose.cells/row/index) | Obtient l'index de cette ligne.|
| [group_level](/cells/python-net/fr/aspose.cells/row/group_level) | Obtient le niveau de groupe de la ligne.|
| [is_height_matched](/cells/python-net/fr/aspose.cells/row/is_height_matched) | Indique si la hauteur de ligne correspond au paramètre de police par défaut actuel du classeur.<br/>La valeur True de cette propriété indique également que la hauteur de ligne est « automatique » sans valeur de hauteur personnalisée définie par l'utilisateur.|
| [has_custom_style](/cells/python-net/fr/aspose.cells/row/has_custom_style) | Indique si cette ligne a des paramètres de style personnalisés (différents de celui par défaut hérité du classeur).|
| [first_cell](/cells/python-net/fr/aspose.cells/row/first_cell) | Obtient le premier objet cellule de la ligne.|
| [first_data_cell](/cells/python-net/fr/aspose.cells/row/first_data_cell) | Obtient la première cellule non vide de la ligne.|
| [last_cell](/cells/python-net/fr/aspose.cells/row/last_cell) | Obtient le dernier objet cellule de la ligne.|
| [last_data_cell](/cells/python-net/fr/aspose.cells/row/last_data_cell) | Obtient la dernière cellule non vide de la ligne.|



Obtient la cellule.
###  Indexeur
| Nom| Description|
| :- | :- |
| [index] | L'index des colonnes|


###  Méthodes
| Méthode| Description|
| :- | :- |
| [get_cell_by_index](/cells/python-net/fr/aspose.cells/row/get_cell_by_index/#int) | Obtenez la cellule par index spécifique dans la collection de cellules de cette ligne.|
| [get_enumerator](/cells/python-net/fr/aspose.cells/row/get_enumerator/#bool-bool) | Obtient un énumérateur qui parcourt les cellules dans cette ligne.|
| [get_cell_or_null](/cells/python-net/fr/aspose.cells/row/get_cell_or_null/#int) | Obtient la cellule ou null dans l'index spécifique.|
| [get_style](/cells/python-net/fr/aspose.cells/row/get_style/#) | Obtient le style de cette ligne.|
| [set_style](/cells/python-net/fr/aspose.cells/row/set_style/#aspose.cells.Style) | Définit le style de cette ligne.|
| [copy_settings](/cells/python-net/fr/aspose.cells/row/copy_settings/#aspose.cells.Row-bool) | Copiez les paramètres de la ligne, tels que le style, la hauteur, la visibilité, etc.|
| [apply_style](/cells/python-net/fr/aspose.cells/row/apply_style/#aspose.cells.Style-aspose.cells.StyleFlag) | Applique des formats pour une ligne entière.|
| [equals](/cells/python-net/fr/aspose.cells/row/equals/#aspose.cells.Row) | Vérifie si cet objet fait référence à la même ligne avec un autre objet ligne.|



###  Exemple

```python
from aspose.cells import BackgroundType, StyleFlag, Workbook
from aspose.pydrawing import Color

# Instantiating a Workbook object
workbook = Workbook()
# Obtaining the reference of the first worksheet
worksheet = workbook.worksheets[0]
style = workbook.create_style()
# Setting the background color to Blue
style.background_color = Color.blue
# Setting the foreground color to Red
style.foreground_color = Color.red
# setting Background Pattern
style.pattern = BackgroundType.DIAGONAL_STRIPE
# New Style Flag
styleFlag = StyleFlag()
# Set All Styles
styleFlag.all = True
# Get first row
row = worksheet.cells.rows[0]
# Apply Style to first row
row.apply_style(style, styleFlag)
# Saving the Excel file
workbook.save("book1.xls")

```

###  Voir également
* module [`aspose.cells`](..)
