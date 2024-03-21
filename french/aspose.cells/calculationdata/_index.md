---
title: CalculationData classe
second_title: Aspose.Cells for Python via .NET API Références
description:
type: docs
weight: 120
url: /fr/aspose.cells/calculationdata/
is_root: false
---
##  CalculationData classe
Représente les données requises lors du calcul d'une fonction, telles que le nom de la fonction, les paramètres, ... etc.



Le type CalculationData expose les membres suivants :

###  Propriétés
| Propriété| Description|
| :- | :- |
| [calculated_value](/cells/python-net/fr/aspose.cells/calculationdata/calculated_value) | Obtient ou définit la valeur calculée pour cette fonction.|
| [workbook](/cells/python-net/fr/aspose.cells/calculationdata/workbook) | Obtient l'objet Workbook dans lequel se trouve la fonction.|
| [worksheet](/cells/python-net/fr/aspose.cells/calculationdata/worksheet) | Obtient l'objet Worksheet dans lequel se trouve la fonction.|
| [cell_row](/cells/python-net/fr/aspose.cells/calculationdata/cell_row) | Obtient l'index de ligne de la cellule dans laquelle se trouve la fonction.|
| [cell_column](/cells/python-net/fr/aspose.cells/calculationdata/cell_column) | Obtient l'index de colonne de la cellule dans laquelle se trouve la fonction.|
| [cell](/cells/python-net/fr/aspose.cells/calculationdata/cell) | Obtient l'objet Cell dans lequel se trouve la fonction.|
| [function_name](/cells/python-net/fr/aspose.cells/calculationdata/function_name) |Obtient le nom de la fonction à calculer.|
| [param_count](/cells/python-net/fr/aspose.cells/calculationdata/param_count) | Obtient le nombre de paramètres|


###  Méthodes
| Méthode| Description|
| :- | :- |
| [get_param_value](/cells/python-net/fr/aspose.cells/calculationdata/get_param_value/#int) | Obtient l'objet valeur représenté du paramètre à un index donné.|
| [get_param_value_in_array_mode](/cells/python-net/fr/aspose.cells/calculationdata/get_param_value_in_array_mode/#int-int-int) | Obtient la ou les valeurs du paramètre à un index donné.<br/>Si le paramètre est une sorte d'expression qui doit être calculée,<br/> alors il sera calculé en mode tableau.|
| [get_param_text](/cells/python-net/fr/aspose.cells/calculationdata/get_param_text/#int) | Obtient le texte littéral du paramètre à l'index donné.|



###  Remarques

Tous les objets fournis par cette classe sont uniquement destinés à la « lecture ».
L'utilisateur ne doit modifier aucune donnée dans le classeur pendant le processus de calcul de la formule.
Sinon, un résultat inattendu ou une exception peut être provoqué.

###  Voir également
* module [`aspose.cells`](..)
