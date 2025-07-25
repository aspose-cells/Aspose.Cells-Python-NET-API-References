---
title: FormatCondition classe
second_title: Aspose.Cells for Python via .NET API Références
description:
type: docs
weight: 700
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
| [stop_if_true](/cells/python-net/fr/aspose.cells/formatcondition/stop_if_true) |C'est vrai, aucune règle avec une priorité inférieure ne peut être appliquée sur cette règle, lorsque cette règle est évaluée à vrai.<br/> S'applique uniquement à Excel 2007 ;|
| [priority](/cells/python-net/fr/aspose.cells/formatcondition/priority) | La priorité de cette règle de mise en forme conditionnelle. Cette valeur permet de déterminer<br/>Le format doit être évalué et rendu. Les valeurs numériques inférieures ont une priorité plus élevée que<br/> valeurs numériques plus élevées, où « 1 » est la priorité la plus élevée.|
| [style](/cells/python-net/fr/aspose.cells/formatcondition/style) | Obtient ou définit le style des plages de cellules formatées conditionnellement.|
| [type](/cells/python-net/fr/aspose.cells/formatcondition/type) | Obtient et définit si le format conditionnel est Type.|
| [icon_set](/cells/python-net/fr/aspose.cells/formatcondition/icon_set) | Obtenez l'instance « IconSet » de la mise en forme conditionnelle.<br/>L'IconSetType de l'instance par défaut est TrafficLights31.<br/> Valable uniquement pour le type = IconSet.|
| [data_bar](/cells/python-net/fr/aspose.cells/formatcondition/data_bar) | Obtenez l'instance « DataBar » de la mise en forme conditionnelle.<br/>La couleur par défaut de l'instance est le bleu.<br/> Valable uniquement pour le type DataBar.|
| [color_scale](/cells/python-net/fr/aspose.cells/formatcondition/color_scale) | Obtenez l'instance « ColorScale » de la mise en forme conditionnelle.<br/>L'instance par défaut est un 3ColorScale « vert-jaune-rouge ».<br/> Valable uniquement pour le type = ColorScale.|
| [top10](/cells/python-net/fr/aspose.cells/formatcondition/top10) | Obtenez l'instance « Top10 » de la mise en forme conditionnelle.<br/>La règle de l'instance par défaut met en évidence les cellules dont<br/>les valeurs se situent dans la tranche des 10 premières.<br/> Valable uniquement pour le type Top10.|
| [above_average](/cells/python-net/fr/aspose.cells/formatcondition/above_average) |Obtenez l'instance « AboveAverage » de la mise en forme conditionnelle.<br/> La règle de l'instance par défaut met en évidence les cellules qui sont<br/>au-dessus de la moyenne pour toutes les valeurs de la gamme.<br/> Valable uniquement pour le type = AboveAverage.|
| [text](/cells/python-net/fr/aspose.cells/formatcondition/text) | La valeur de texte dans une règle de mise en forme conditionnelle « le texte contient ».<br/>Valable uniquement pour type = containsText, notContainsText, beginsWith et endsWith.<br/> La valeur par défaut est null.|
| [time_period](/cells/python-net/fr/aspose.cells/formatcondition/time_period) | La période applicable dans une règle de mise en forme conditionnelle « date survenant… ».<br/>Valable uniquement pour le type = timePeriod.<br/> La valeur par défaut est TimePeriodType.Today.|


###  Méthodes
| Méthode| Description|
| :- | :- |
| [`get_formula1(self, is_r1c1, is_local)`](/cells/python-net/fr/aspose.cells/formatcondition/get_formula1/#bool-bool) | Obtient la valeur ou l'expression associée à cette condition de format.|
| [`get_formula1(self, is_r1c1, is_local, row, column)`](/cells/python-net/fr/aspose.cells/formatcondition/get_formula1/#bool-bool-int-int) | Obtient la valeur ou l'expression de la mise en forme conditionnelle de la cellule.|
| [`get_formula1(self, row, column)`](/cells/python-net/fr/aspose.cells/formatcondition/get_formula1/#int-int) | Obtient la formule de mise en forme conditionnelle de la cellule.|
| [`get_formula2(self, is_r1c1, is_local)`](/cells/python-net/fr/aspose.cells/formatcondition/get_formula2/#bool-bool) | Obtient la valeur ou l'expression associée à cette condition de format.|
| [`get_formula2(self, is_r1c1, is_local, row, column)`](/cells/python-net/fr/aspose.cells/formatcondition/get_formula2/#bool-bool-int-int) | Obtient la valeur ou l'expression de la mise en forme conditionnelle de la cellule.|
| [`get_formula2(self, row, column)`](/cells/python-net/fr/aspose.cells/formatcondition/get_formula2/#int-int) | Obtient la formule de mise en forme conditionnelle de la cellule.|
| [`set_formulas(self, formula1, formula2, is_r1c1, is_local)`](/cells/python-net/fr/aspose.cells/formatcondition/set_formulas/#str-str-bool-bool) | Définit la valeur ou l'expression associée à cette condition de format.|
| [`set_formula1(self, formula, is_r1c1, is_local)`](/cells/python-net/fr/aspose.cells/formatcondition/set_formula1/#str-bool-bool) | Définit la valeur ou l'expression associée à cette condition de format.|
| [`set_formula2(self, formula, is_r1c1, is_local)`](/cells/python-net/fr/aspose.cells/formatcondition/set_formula2/#str-bool-bool) | Définit la valeur ou l'expression associée à cette condition de format.|



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
