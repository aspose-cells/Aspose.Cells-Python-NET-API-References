---
title: Slicer classe
second_title: Aspose.Cells for Python via .NET API Références
description:
type: docs
weight: 10
url: /fr/aspose.cells.slicers/slicer/
is_root: false
---
##  Slicer classe
description sommaire de Slicer Voir



Le type Slicer expose les membres suivants :

###  Propriétés
| Propriété| Description|
| :- | :- |
| [title](/cells/python-net/fr/aspose.cells.slicers/slicer/title) | Spécifie le titre de l'objet Slicer actuel.|
| [alternative_text](/cells/python-net/fr/aspose.cells.slicers/slicer/alternative_text) | Renvoie ou définit la chaîne de texte descriptive (alternative) de l'objet Slicer.|
| [is_printable](/cells/python-net/fr/aspose.cells.slicers/slicer/is_printable) | Indique si l'objet slicer est imprimable.|
| [is_locked](/cells/python-net/fr/aspose.cells.slicers/slicer/is_locked) | Indique si la forme du slicer est verrouillée.|
| [placement](/cells/python-net/fr/aspose.cells.slicers/slicer/placement) | Représente la manière dont l'objet de dessin est attaché aux cellules situées en dessous.<br/> La propriété contrôle le placement d'un objet sur une feuille de calcul.|
| [locked_aspect_ratio](/cells/python-net/fr/aspose.cells.slicers/slicer/locked_aspect_ratio) | Indique si le rapport hauteur/largeur est verrouillé.|
| [locked_position](/cells/python-net/fr/aspose.cells.slicers/slicer/locked_position) |Indique si le segment spécifié peut être déplacé ou redimensionné à l'aide de l'interface utilisateur.|
| [shape](/cells/python-net/fr/aspose.cells.slicers/slicer/shape) | Renvoie l'objet Shape associé au slicer spécifié. Lecture seule.|
| [slicer_cache](/cells/python-net/fr/aspose.cells.slicers/slicer/slicer_cache) | Renvoie l'objet SlicerCache associé au slicer. Lecture seule.|
| [parent](/cells/python-net/fr/aspose.cells.slicers/slicer/parent) | Renvoie l'objet [`Worksheet`](/cells/python-net/fr/aspose.cells/worksheet) contenant ce slicer. Lecture seule.|
| [style_type](/cells/python-net/fr/aspose.cells.slicers/slicer/style_type) | Spécifiez le type de style de trancheur intégré<br/> le type par défaut est SlicerStyleLight1|
| [name](/cells/python-net/fr/aspose.cells.slicers/slicer/name) | Renvoie ou définit le nom du slicer spécifié|
| [caption](/cells/python-net/fr/aspose.cells.slicers/slicer/caption) | Renvoie ou définit la légende du slicer spécifié.|
| [caption_visible](/cells/python-net/fr/aspose.cells.slicers/slicer/caption_visible) | Renvoie ou définit si l'en-tête qui affiche la légende du slicer est visible<br/> la valeur par défaut est vraie|
| [number_of_columns](/cells/python-net/fr/aspose.cells.slicers/slicer/number_of_columns) | Renvoie ou définit le nombre de colonnes dans le segment spécifié.|
| [left_pixel](/cells/python-net/fr/aspose.cells.slicers/slicer/left_pixel) | Renvoie ou définit le décalage horizontal de la forme du slicer à partir de sa colonne de gauche, en pixels.|
| [top_pixel](/cells/python-net/fr/aspose.cells.slicers/slicer/top_pixel) | Renvoie ou définit le décalage vertical de la forme du slicer à partir de sa ligne supérieure, en pixels.|
| [width](/cells/python-net/fr/aspose.cells.slicers/slicer/width) | Renvoie ou définit la largeur du slicer spécifié, en points.|
| [width_pixel](/cells/python-net/fr/aspose.cells.slicers/slicer/width_pixel) |Renvoie ou définit la largeur du slicer spécifié, en pixels.|
| [height](/cells/python-net/fr/aspose.cells.slicers/slicer/height) | Renvoie ou définit la hauteur du slicer spécifié, en points.|
| [height_pixel](/cells/python-net/fr/aspose.cells.slicers/slicer/height_pixel) | Renvoie ou définit la hauteur du slicer spécifié, en pixels.|
| [column_width_pixel](/cells/python-net/fr/aspose.cells.slicers/slicer/column_width_pixel) | Obtient ou définit la largeur de chaque colonne dans le segment, en unités de pixels.|
| [column_width](/cells/python-net/fr/aspose.cells.slicers/slicer/column_width) | Renvoie ou définit la largeur, en points, de chaque colonne du segment.|
| [row_height_pixel](/cells/python-net/fr/aspose.cells.slicers/slicer/row_height_pixel) | Renvoie ou définit la hauteur, en pixels, de chaque ligne dans le segment spécifié.|
| [row_height](/cells/python-net/fr/aspose.cells.slicers/slicer/row_height) | Renvoie ou définit la hauteur, en points, de chaque ligne dans le segment spécifié.|


###  Méthodes
| Méthode| Description|
| :- | :- |
| [`add_pivot_connection(self, pivot)`](/cells/python-net/fr/aspose.cells.slicers/slicer/add_pivot_connection/#aspose.cells.pivot.pivottable) | Ajoute une connexion PivotTable.|
| [`remove_pivot_connection(self, pivot)`](/cells/python-net/fr/aspose.cells.slicers/slicer/remove_pivot_connection/#aspose.cells.pivot.pivottable) | Supprime la connexion au tableau croisé dynamique.|
| [`refresh(self)`](/cells/python-net/fr/aspose.cells.slicers/slicer/refresh/#) | Actualisation du segment. Pendant ce temps, actualisation et calcul des tableaux croisés dynamiques relatifs.|



###  Exemple

```python
from aspose.cells import Workbook
from aspose.cells.pivot import PivotFieldType, PivotTableStyleType
from aspose.cells.slicers import SlicerStyleType

book = Workbook()
sheet = book.worksheets[0]
cells = sheet.cells
cells.get(0, 0).value = "fruit"
cells.get(1, 0).value = "grape"
cells.get(2, 0).value = "blueberry"
cells.get(3, 0).value = "kiwi"
cells.get(4, 0).value = "cherry"
cells.get(5, 0).value = "grape"
cells.get(6, 0).value = "blueberry"
cells.get(7, 0).value = "kiwi"
cells.get(8, 0).value = "cherry"
cells.get(0, 1).value = "year"
cells.get(1, 1).value = 2020
cells.get(2, 1).value = 2020
cells.get(3, 1).value = 2020
cells.get(4, 1).value = 2020
cells.get(5, 1).value = 2021
cells.get(6, 1).value = 2021
cells.get(7, 1).value = 2021
cells.get(8, 1).value = 2021
cells.get(0, 2).value = "amount"
cells.get(1, 2).value = 50
cells.get(2, 2).value = 60
cells.get(3, 2).value = 70
cells.get(4, 2).value = 80
cells.get(5, 2).value = 90
cells.get(6, 2).value = 100
cells.get(7, 2).value = 110
cells.get(8, 2).value = 120
pivots = sheet.pivot_tables
pivotIndex = pivots.add("=Sheet1!A1:C9", "A12", "TestPivotTable")
pivot = pivots[pivotIndex]
pivot.add_field_to_area(PivotFieldType.ROW, "fruit")
pivot.add_field_to_area(PivotFieldType.COLUMN, "year")
pivot.add_field_to_area(PivotFieldType.DATA, "amount")
pivot.pivot_table_style_type = PivotTableStyleType.PIVOT_TABLE_STYLE_MEDIUM10
pivot.refresh_data()
pivot.calculate_data()
slicers = sheet.slicers
slicerIndex = slicers.add(pivot, "E12", "fruit")
slicer = slicers[slicerIndex]
slicer.style_type = SlicerStyleType.SLICER_STYLE_LIGHT2
items = slicer.slicer_cache.slicer_cache_items
item = items[0]
item.selected = False
# do your business
book.save("out.xlsx")

```

###  Voir également
* module [`aspose.cells.slicers`](..)
* classe [`Worksheet`](/cells/python-net/fr/aspose.cells/worksheet)
