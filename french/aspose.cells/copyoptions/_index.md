---
title: CopyOptions classe
second_title: Aspose.Cells for Python via .NET API Références
description:
type: docs
weight: 340
url: /fr/aspose.cells/copyoptions/
is_root: false
---
##  CopyOptions classe
Représente les options de copie.



Le type CopyOptions expose les membres suivants :

###  Constructeurs
| Constructeur| Description|
| :- | :- |
| [`__init__(self)`](/cells/python-net/fr/aspose.cells/copyoptions/__init__/#) | Constructeur CopyOptions.|


###  Propriétés
| Propriété| Description|
| :- | :- |
| [keep_macros](/cells/python-net/fr/aspose.cells/copyoptions/keep_macros) |Indique si les macros doivent être conservées ;|
| [extend_to_adjacent_range](/cells/python-net/fr/aspose.cells/copyoptions/extend_to_adjacent_range) | Indique si les plages doivent être étendues lors de la copie de la plage vers la plage adjacente.|
| [copy_names](/cells/python-net/fr/aspose.cells/copyoptions/copy_names) | Indique si les noms doivent être copiés.|
| [copy_invalid_formulas_as_values](/cells/python-net/fr/aspose.cells/copyoptions/copy_invalid_formulas_as_values) | Si la formule n'est pas valide pour la destination dest, copiez uniquement les valeurs.|
| [column_character_width](/cells/python-net/fr/aspose.cells/copyoptions/column_character_width) | Indique si la largeur de la colonne est copiée en unités de caractères.|
| [refer_to_sheet_with_same_name](/cells/python-net/fr/aspose.cells/copyoptions/refer_to_sheet_with_same_name) | Dans MS Excel, lors de la copie de formules qui font référence à d'autres feuilles de calcul lors de la copie d'une feuille de calcul vers une autre,<br/>les formules copiées doivent faire référence au classeur source.<br/>Cependant, dans certaines situations, l'utilisateur peut avoir besoin que les formules copiées se réfèrent à des feuilles de calcul portant le même nom.<br/>dans le même classeur, par exemple lorsque ces feuilles de calcul ont été copiées avant cette opération de copie,<br/> alors cette propriété doit être conservée comme vraie.|
| [refer_to_destination_sheet](/cells/python-net/fr/aspose.cells/copyoptions/refer_to_destination_sheet) | Lors de la copie de la plage dans le même fichier et que le graphique fait référence à la feuille source,<br/>Faux signifie que la source de données du graphique copié ne sera pas modifiée.<br/> Vrai signifie que la source de données du graphique copié fait référence à la feuille de destination.|



###  Voir également
* module [`aspose.cells`](..)
