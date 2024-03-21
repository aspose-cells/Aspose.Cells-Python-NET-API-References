---
title: RowCollection classe
second_title: Aspose.Cells for Python via .NET API Références
description:
type: docs
weight: 1350
url: /fr/aspose.cells/rowcollection/
is_root: false
---
##  RowCollection classe
Collecte les objets [`Row`](/cells/python-net/fr/aspose.cells/row) qui représentent les lignes individuelles d'une feuille de calcul.



Le type RowCollection expose les membres suivants :

###  Propriétés
| Propriété| Description|
| :- | :- |
| [count](/cells/python-net/fr/aspose.cells/rowcollection/count) | Obtient le nombre de lignes dans cette collection.|



Obtient un objet [`Row`](/cells/python-net/fr/aspose.cells/row) par index de ligne donné. L'objet Row d'un index de ligne donné sera instancié s'il n'existe pas auparavant.
###  Indexeur
| Nom| Description|
| :- | :- |
| [index] |  |


###  Méthodes
| Méthode| Description|
| :- | :- |
| [get_enumerator](/cells/python-net/fr/aspose.cells/rowcollection/get_enumerator/#bool-bool) | Obtient un énumérateur qui parcourt les lignes de cette collection|
| [get_row_by_index](/cells/python-net/fr/aspose.cells/rowcollection/get_row_by_index/#int) | Obtient l'objet ligne par sa position dans la liste.|
| [clear](/cells/python-net/fr/aspose.cells/rowcollection/clear/#) | Effacez toutes les lignes et cellules.|
| [remove_at](/cells/python-net/fr/aspose.cells/rowcollection/remove_at/#int) | Supprimez l'élément de ligne à l'index (position) spécifié dans cette collection.|



###  Exemple

```python
from aspose.cells import Workbook

# Instantiating a Workbook object
workbook = Workbook()
# Obtaining the reference of the first worksheet
worksheet = workbook.worksheets[0]
# Get first row
row = worksheet.cells.rows[0]

```

###  Voir également
* module [`aspose.cells`](..)
* classe [`Row`](/cells/python-net/fr/aspose.cells/row)
