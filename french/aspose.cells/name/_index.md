---
title: Name classe
second_title: Aspose.Cells for Python via .NET API Références
description:
type: docs
weight: 1000
url: /fr/aspose.cells/name/
is_root: false
---
##  Name classe
Représente un nom défini pour une plage de cellules.



Le type Name expose les membres suivants :

###  Propriétés
| Propriété| Description|
| :- | :- |
| [comment](/cells/python-net/fr/aspose.cells/name/comment) | Obtient et définit le commentaire du nom.<br/> S'applique uniquement à Excel 2007 ou aux versions supérieures.|
| [text](/cells/python-net/fr/aspose.cells/name/text) | Obtient le texte du nom de l'objet.|
| [full_text](/cells/python-net/fr/aspose.cells/name/full_text) | Obtient le nom du texte intégral de l'objet avec le paramètre de portée.|
| [refers_to](/cells/python-net/fr/aspose.cells/name/refers_to) | Renvoie ou définit la formule à laquelle le nom est défini pour faire référence, en commençant par un signe égal.|
| [r1c1_refers_to](/cells/python-net/fr/aspose.cells/name/r1c1_refers_to) |Obtient ou définit une référence R1C1 du [`Name`](/cells/python-net/fr/aspose.cells/name).|
| [is_referred](/cells/python-net/fr/aspose.cells/name/is_referred) | Indique si ce nom est référencé par d'autres formules.|
| [is_visible](/cells/python-net/fr/aspose.cells/name/is_visible) | Indique si le nom est visible.|
| [sheet_index](/cells/python-net/fr/aspose.cells/name/sheet_index) | Indique que ce nom appartient au classeur ou à la feuille de calcul.<br/> 0 = Nom global, sinon index vers la feuille (base un)|


###  Méthodes
| Méthode| Description|
| :- | :- |
| [`get_refers_to(self, is_r1c1, is_local)`](/cells/python-net/fr/aspose.cells/name/get_refers_to/#bool-bool) | Obtenez la référence de ce nom.|
| [`get_refers_to(self, is_r1c1, is_local, row, column)`](/cells/python-net/fr/aspose.cells/name/get_refers_to/#bool-bool-int-int) | Obtenez la référence de ce nom en fonction de la cellule spécifiée.|
| [`get_ranges(self)`](/cells/python-net/fr/aspose.cells/name/get_ranges/#) | Obtient toutes les plages référencées par ce nom.|
| [`get_ranges(self, recalculate)`](/cells/python-net/fr/aspose.cells/name/get_ranges/#bool) | Obtient toutes les plages référencées par ce nom.|
| [`get_range(self)`](/cells/python-net/fr/aspose.cells/name/get_range/#) | Obtient la plage si ce nom fait référence à une plage.|
| [`get_range(self, recalculate)`](/cells/python-net/fr/aspose.cells/name/get_range/#bool) | Obtient la plage si ce nom fait référence à une plage|
| [`get_range(self, sheet_index, row, column)`](/cells/python-net/fr/aspose.cells/name/get_range/#int-int-int) | Obtient la plage si ce nom fait référence à une plage.<br/> Si la référence de ce nom n'est pas absolue, la plage peut être différente pour différentes cellules.|
| [`set_refers_to(self, refers_to, is_r1c1, is_local)`](/cells/python-net/fr/aspose.cells/name/set_refers_to/#str-bool-bool) | Définissez la référence de ce nom.|
| [`get_referred_areas(self, recalculate)`](/cells/python-net/fr/aspose.cells/name/get_referred_areas/#bool) | Obtient toutes les références référencées par ce nom.|



###  Exemple

```python
from aspose.cells import Workbook

# Instantiating a Workbook object
workbook = Workbook()
# Accessing the first worksheet in the Excel file
worksheet = workbook.worksheets[0]
# Creating a named range
range = worksheet.cells.create_range("B4", "G14")
# Setting the name of the named range
range.name = "TestRange"
# Saving the modified Excel file in default (that is Excel 2000) format
workbook.save("output.xls")

```

###  Voir également
* module [`aspose.cells`](..)
* classe [`Name`](/cells/python-net/fr/aspose.cells/name)
