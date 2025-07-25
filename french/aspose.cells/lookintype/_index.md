---
title: LookInType énumération
second_title: Aspose.Cells for Python via .NET API Références
description:
type: docs
weight: 2270
url: /fr/aspose.cells/lookintype/
is_root: false
---
##  LookInType énumération
Représente l'apparence du type.



Le type LookInType expose les membres suivants :

###  Des champs
| Champ| Description|
| :- | :- |
| FORMULAS | Recherche l'objet recherché à partir de la formule ([`Cell.formula`](/cells/python-net/fr/aspose.cells/cell#formula)) si la cellule est une formule,<br/>sinon, recherche à partir de la valeur d'origine de la cellule (idem avec [`LookInType.ORIGINAL_VALUES`](/cells/python-net/fr/aspose.cells/lookintype#ORIGINAL_VALUES)).|
| VALUES | Recherche l'objet à partir de la valeur d'origine de la cellule ([`Cell.value`](/cells/python-net/fr/aspose.cells/cell#value))<br/> et valeur formatée ([`Cell.string_value`](/cells/python-net/fr/aspose.cells/cell#string_value)).|
| VALUES_EXCLUDE_FORMULA_CELL | Ignore les cellules contenant des formules. Pour celles qui ne contiennent pas de formules,<br/> c'est pareil avec [`LookInType.VALUES`](/cells/python-net/fr/aspose.cells/lookintype#VALUES).|
| COMMENTS | Recherche l'objet uniquement à partir du commentaire de la cellule. Ignore les cellules sans commentaire.|
| ONLY_FORMULAS | Ignore les cellules qui ne sont pas des formules. Pour celles qui sont des formules,<br/> trouve l'objet recherché à partir de la formule ([`Cell.formula`](/cells/python-net/fr/aspose.cells/cell#formula)).|
| ORIGINAL_VALUES | Rechercher l'objet à partir de la valeur d'origine de la cellule uniquement.|
| FORMATTED_VALUES | Rechercher l'objet à partir de la valeur formatée de la cellule ([`Cell.string_value`](/cells/python-net/fr/aspose.cells/cell#string_value)) uniquement.|



###  Voir également
* module [`aspose.cells`](..)
