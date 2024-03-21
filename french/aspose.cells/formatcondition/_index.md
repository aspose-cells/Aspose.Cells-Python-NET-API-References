---
title: FormatCondition classe
second_title: Aspose.Cells for Python via .NET API Références
description:
type: docs
weight: 720
url: /fr/aspose.cells/formatcondition/
is_root: false
---
##  FormatCondition classe
Représente la condition de mise en forme conditionnelle.



Le type FormatCondition expose les membres suivants :

###  Propriétés
| Propriété| Description|
| :- | :- |
| [formula1](/cells/python-net/fr/aspose.cells/formatcondition/formula1) | Obtient et définit la valeur ou l'expression associée à la mise en forme conditionnelle.|
| [formula2](/cells/python-net/fr/aspose.cells/formatcondition/formula2) | Obtient et définit la valeur ou l'expression associée à la mise en forme conditionnelle.|
| [operator](/cells/python-net/fr/aspose.cells/formatcondition/operator) | Obtient et définit le type d'opérateur de format conditionnel.|
| [stop_if_true](/cells/python-net/fr/aspose.cells/formatcondition/stop_if_true) | Certes, aucune règle de priorité inférieure ne peut être appliquée à cette règle lorsque celle-ci est évaluée comme vraie.<br/> S'applique uniquement à Excel 2007 ;|
| [priority](/cells/python-net/fr/aspose.cells/formatcondition/priority) | Priorité de cette règle de mise en forme conditionnelle. Cette valeur est utilisée pour déterminer quel<br/>Le format doit être évalué et rendu. Les valeurs numériques inférieures ont une priorité plus élevée que<br/> valeurs numériques plus élevées, où « 1 » est la priorité la plus élevée.|
| [style](/cells/python-net/fr/aspose.cells/formatcondition/style) | Obtient ou définit le style des plages de cellules mises en forme conditionnellement.|
| [type](/cells/python-net/fr/aspose.cells/formatcondition/type) |Obtient et définit si le format conditionnel Type.|
| [icon_set](/cells/python-net/fr/aspose.cells/formatcondition/icon_set) | Obtenez l'instance "IconSet" de la mise en forme conditionnelle.<br/>Le IconSetType de l’instance par défaut est TrafficLights31.<br/> Valable uniquement pour type = IconSet.|
| [data_bar](/cells/python-net/fr/aspose.cells/formatcondition/data_bar) | Obtenez l'instance "DataBar" de la mise en forme conditionnelle.<br/>La couleur de l'instance par défaut est le bleu.<br/> Valable uniquement pour le type DataBar.|
| [color_scale](/cells/python-net/fr/aspose.cells/formatcondition/color_scale) | Obtenez l'instance "ColorScale" de la mise en forme conditionnelle.<br/>L'instance par défaut est un 3ColorScale "vert-jaune-rouge".<br/> Valable uniquement pour le type = ColorScale.|
| [top10](/cells/python-net/fr/aspose.cells/formatcondition/top10) | Obtenez l'instance "Top10" de la mise en forme conditionnelle.<br/>La règle de l'instance par défaut met en évidence les cellules dont<br/>les valeurs se situent dans la tranche des 10 premiers.<br/> Valable uniquement pour le type Top10.|
| [above_average](/cells/python-net/fr/aspose.cells/formatcondition/above_average) | Obtenez l'instance "AboveAverage" de la mise en forme conditionnelle.<br/> La règle de l'instance par défaut met en évidence les cellules qui sont<br/>au-dessus de la moyenne pour toutes les valeurs de la plage.<br/>Valable uniquement pour le type = AboveAverage.|
| [text](/cells/python-net/fr/aspose.cells/formatcondition/text) | La valeur du texte dans une règle de mise en forme conditionnelle « le texte contient ».<br/>Valable uniquement pour type = containText, notContainsText, BeginsWith et EndsWith.<br/> La valeur par défaut est nulle.|
| [time_period](/cells/python-net/fr/aspose.cells/formatcondition/time_period) | Période de temps applicable dans une règle de formatage conditionnel « date survenant… ».<br/>Valable uniquement pour type = timePeriod.<br/> La valeur par défaut est TimePeriodType.Today.|


###  Méthodes
| Méthode| Description|
| :- | :- |
| [get_formula1](/cells/python-net/fr/aspose.cells/formatcondition/get_formula1/#bool-bool) | Obtient la valeur ou l'expression associée à cette condition de format.|
| [get_formula1](/cells/python-net/fr/aspose.cells/formatcondition/get_formula1/#bool-bool-int-int) | Obtient la valeur ou l'expression de la mise en forme conditionnelle de la cellule.|
| [get_formula1](/cells/python-net/fr/aspose.cells/formatcondition/get_formula1/#int-int) | Obtient la formule de mise en forme conditionnelle de la cellule.|
| [get_formula2](/cells/python-net/fr/aspose.cells/formatcondition/get_formula2/#bool-bool) | Obtient la valeur ou l'expression associée à cette condition de format.|
| [get_formula2](/cells/python-net/fr/aspose.cells/formatcondition/get_formula2/#bool-bool-int-int) | Obtient la valeur ou l'expression de la mise en forme conditionnelle de la cellule.|
| [get_formula2](/cells/python-net/fr/aspose.cells/formatcondition/get_formula2/#int-int) | Obtient la formule de mise en forme conditionnelle de la cellule.|
| [set_formulas](/cells/python-net/fr/aspose.cells/formatcondition/set_formulas/#str-str-bool-bool) | Définit la valeur ou l'expression associée à cette condition de format.|
| [set_formula1](/cells/python-net/fr/aspose.cells/formatcondition/set_formula1/#str-bool-bool) | Définit la valeur ou l'expression associée à cette condition de format.|
| [set_formula2](/cells/python-net/fr/aspose.cells/formatcondition/set_formula2/#str-bool-bool) | Définit la valeur ou l'expression associée à cette condition de format.|



###  Exemple

```python
from aspose.cells import CellArea, FormatConditionType, OperatorType, Workbook
from aspose.pydrawing import Color

# Instantiating a Workbook object
workbook = Workbook()
sheet = workbook.worksheets[0]
# Adds an empty conditional formatting
index = sheet.conditional_formattings.add()
fcs = sheet.conditional_formattings[index]
# Sets the conditional format range.
ca = CellArea()
ca.start_row = 0
ca.end_row = 0
ca.start_column = 0
ca.end_column = 0
fcs.add_area(ca)
ca = CellArea()
ca.start_row = 1
ca.end_row = 1
ca.start_column = 1
ca.end_column = 1
fcs.add_area(ca)
# Adds condition.
conditionIndex = fcs.add_condition(FormatConditionType.CELL_VALUE, OperatorType.BETWEEN, "=A2", "100")
# Adds condition.
conditionIndex2 = fcs.add_condition(FormatConditionType.CELL_VALUE, OperatorType.BETWEEN, "50", "100")
# Sets the background color.
fc = fcs[conditionIndex]
fc.style.background_color = Color.red
# Saving the Excel file
workbook.save("output.xls")

```

###  Voir également
* module [`aspose.cells`](..)
