---
title: Validation classe
second_title: Aspose.Cells for Python via .NET API Références
description:
type: docs
weight: 1610
url: /fr/aspose.cells/validation/
is_root: false
---
##  Validation classe
Représente les paramètres de validation des données.



Le type Validation expose les membres suivants :

###  Propriétés
| Propriété| Description|
| :- | :- |
| [operator](/cells/python-net/fr/aspose.cells/validation/operator) | Représente l'opérateur pour la validation des données.|
| [alert_style](/cells/python-net/fr/aspose.cells/validation/alert_style) | Représente le style d’alerte de validation.|
| [type](/cells/python-net/fr/aspose.cells/validation/type) | Représente le type de validation des données.|
| [input_message](/cells/python-net/fr/aspose.cells/validation/input_message) | Représente le message d’entrée de validation des données.|
| [input_title](/cells/python-net/fr/aspose.cells/validation/input_title) | Représente le titre de la boîte de dialogue de saisie de validation des données.|
| [error_message](/cells/python-net/fr/aspose.cells/validation/error_message) | Représente le message d'erreur de validation des données.|
| [error_title](/cells/python-net/fr/aspose.cells/validation/error_title) | Représente le titre de la boîte de dialogue d'erreur de validation des données.|
| [show_input](/cells/python-net/fr/aspose.cells/validation/show_input) | Indique si le message d'entrée de validation des données sera affiché chaque fois que l'utilisateur sélectionne une cellule dans la plage de validation des données.|
| [show_error](/cells/python-net/fr/aspose.cells/validation/show_error) | Indique si le message d'erreur de validation des données sera affiché chaque fois que l'utilisateur saisit des données non valides.|
| [ignore_blank](/cells/python-net/fr/aspose.cells/validation/ignore_blank) | Indique si les valeurs vides sont autorisées par la validation des données de plage.|
| [formula1](/cells/python-net/fr/aspose.cells/validation/formula1) |Représente la valeur ou l'expression associée à la validation des données.|
| [formula2](/cells/python-net/fr/aspose.cells/validation/formula2) |Représente la valeur ou l'expression associée à la validation des données.|
| [value1](/cells/python-net/fr/aspose.cells/validation/value1) | Représente la première valeur associée à la validation des données.|
| [value2](/cells/python-net/fr/aspose.cells/validation/value2) | Représente la deuxième valeur associée à la validation des données.|
| [in_cell_drop_down](/cells/python-net/fr/aspose.cells/validation/in_cell_drop_down) | Indique si la validation des données affiche une liste déroulante contenant les valeurs acceptables.|
| [areas](/cells/python-net/fr/aspose.cells/validation/areas) | Obtient tous les [`CellArea`](/cells/python-net/fr/aspose.cells/cellarea) qui contiennent les paramètres de validation des données.|


###  Méthodes
| Méthode| Description|
| :- | :- |
| [get_formula1](/cells/python-net/fr/aspose.cells/validation/get_formula1/#bool-bool) | Obtient la valeur ou l'expression associée à cette validation.|
| [get_formula1](/cells/python-net/fr/aspose.cells/validation/get_formula1/#bool-bool-int-int) | Obtient la valeur ou l'expression associée à cette validation pour une cellule spécifique.|
| [get_formula2](/cells/python-net/fr/aspose.cells/validation/get_formula2/#bool-bool) | Obtient la valeur ou l'expression associée à cette validation.|
| [get_formula2](/cells/python-net/fr/aspose.cells/validation/get_formula2/#bool-bool-int-int) | Obtient la valeur ou l'expression associée à cette validation pour une cellule spécifique.|
| [add_area](/cells/python-net/fr/aspose.cells/validation/add_area/#aspose.cells.CellArea) | Applique la validation à la zone.|
| [add_area](/cells/python-net/fr/aspose.cells/validation/add_area/#aspose.cells.CellArea-bool-bool) | Applique la validation à la zone.|
| [set_formula1](/cells/python-net/fr/aspose.cells/validation/set_formula1/#str-bool-bool) | Définit la valeur ou l'expression associée à cette validation.|
| [set_formula2](/cells/python-net/fr/aspose.cells/validation/set_formula2/#str-bool-bool) | Définit la valeur ou l'expression associée à cette validation.|
| [get_list_value](/cells/python-net/fr/aspose.cells/validation/get_list_value/#int-int) | Obtenez la valeur de la liste de validation pour la cellule spécifiée.|
| [get_value](/cells/python-net/fr/aspose.cells/validation/get_value/#int-int-bool) | Obtenez la valeur de validation sur la cellule spécifique.|
| [add_areas](/cells/python-net/fr/aspose.cells/validation/add_areas/#list-bool-bool) | Applique la validation à des zones données.|
| [remove_area](/cells/python-net/fr/aspose.cells/validation/remove_area/#aspose.cells.CellArea) | Supprimez les paramètres de validation dans la plage.|
| [remove_areas](/cells/python-net/fr/aspose.cells/validation/remove_areas/#list) | Supprime cette validation des zones données.|
| [remove_a_cell](/cells/python-net/fr/aspose.cells/validation/remove_a_cell/#int-int) | Supprimez les paramètres de validation dans la cellule.|
| [copy](/cells/python-net/fr/aspose.cells/validation/copy/#aspose.cells.Validation-aspose.cells.CopyOptions) | Validation de copie.|



###  Exemple

```python
from aspose.cells import CellArea, OperatorType, ValidationType, Workbook

workbook = Workbook()
validations = workbook.worksheets[0].validations
area = CellArea.create_cell_area(0, 0, 1, 1)
validation = validations[validations.add(area)]
validation.type = ValidationType.WHOLE_NUMBER
validation.operator = OperatorType.BETWEEN
validation.formula1 = "3"
validation.formula2 = "1234"

```

###  Voir également
* module [`aspose.cells`](..)
* classe [`CellArea`](/cells/python-net/fr/aspose.cells/cellarea)
