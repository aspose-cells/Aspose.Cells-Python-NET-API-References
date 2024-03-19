---
title: Validation klass
second_title: Aspose.Cells for Python via .NET API Referenser
description:
type: docs
weight: 1610
url: /sv/aspose.cells/validation/
is_root: false
---
##  Validation klass
Representerar datavalidering.inställningar.



Typen Validation avslöjar följande medlemmar:

###  Egenskaper
| Fast egendom| Beskrivning|
| :- | :- |
| [operator](/cells/python-net/sv/aspose.cells/validation/operator) | Representerar operatören för datavalideringen.|
| [alert_style](/cells/python-net/sv/aspose.cells/validation/alert_style) | Representerar valideringsvarningsstilen.|
| [type](/cells/python-net/sv/aspose.cells/validation/type) | Representerar datavalideringstypen.|
| [input_message](/cells/python-net/sv/aspose.cells/validation/input_message) | Representerar ingångsmeddelandet för datavalidering.|
| [input_title](/cells/python-net/sv/aspose.cells/validation/input_title) | Representerar titeln på dialogrutan för datavalidering.|
| [error_message](/cells/python-net/sv/aspose.cells/validation/error_message) | Representerar datavalideringsfelmeddelandet.|
| [error_title](/cells/python-net/sv/aspose.cells/validation/error_title) | Representerar titeln på dialogrutan för datavalideringsfel.|
| [show_input](/cells/python-net/sv/aspose.cells/validation/show_input) | Indikerar om inmatningsmeddelandet för datavalidering kommer att visas när användaren väljer en cell i datavalideringsintervallet.|
| [show_error](/cells/python-net/sv/aspose.cells/validation/show_error) | Indikerar om datavalideringsfelmeddelandet kommer att visas när användaren anger ogiltiga data.|
| [ignore_blank](/cells/python-net/sv/aspose.cells/validation/ignore_blank) | Indikerar om tomma värden är tillåtna av intervalldatavalideringen.|
| [formula1](/cells/python-net/sv/aspose.cells/validation/formula1) |Representerar värdet eller uttrycket som är associerat med datavalideringen.|
| [formula2](/cells/python-net/sv/aspose.cells/validation/formula2) |Representerar värdet eller uttrycket som är associerat med datavalideringen.|
| [value1](/cells/python-net/sv/aspose.cells/validation/value1) | Representerar det första värdet som är kopplat till datavalideringen.|
| [value2](/cells/python-net/sv/aspose.cells/validation/value2) | Representerar det andra värdet som är associerat med datavalideringen.|
| [in_cell_drop_down](/cells/python-net/sv/aspose.cells/validation/in_cell_drop_down) | Anger om datavalidering visar en rullgardinslista som innehåller acceptabla värden.|
| [areas](/cells/python-net/sv/aspose.cells/validation/areas) | Hämtar alla [`CellArea`](/cells/python-net/sv/aspose.cells/cellarea) som innehåller datavalideringsinställningarna.|


###  Metoder
| Metod| Beskrivning|
| :- | :- |
| [get_formula1](/cells/python-net/sv/aspose.cells/validation/get_formula1/#bool-bool) | Hämtar värdet eller uttrycket som är kopplat till denna validering.|
| [get_formula1](/cells/python-net/sv/aspose.cells/validation/get_formula1/#bool-bool-int-int) | Hämtar värdet eller uttrycket som är associerat med denna validering för specifik cell.|
| [get_formula2](/cells/python-net/sv/aspose.cells/validation/get_formula2/#bool-bool) | Hämtar värdet eller uttrycket som är kopplat till denna validering.|
| [get_formula2](/cells/python-net/sv/aspose.cells/validation/get_formula2/#bool-bool-int-int) | Hämtar värdet eller uttrycket som är associerat med denna validering för specifik cell.|
| [add_area](/cells/python-net/sv/aspose.cells/validation/add_area/#aspose.cells.CellArea) | Tillämpar valideringen på området.|
| [add_area](/cells/python-net/sv/aspose.cells/validation/add_area/#aspose.cells.CellArea-bool-bool) | Tillämpar valideringen på området.|
| [set_formula1](/cells/python-net/sv/aspose.cells/validation/set_formula1/#str-bool-bool) | Ställer in värdet eller uttrycket som är associerat med denna validering.|
| [set_formula2](/cells/python-net/sv/aspose.cells/validation/set_formula2/#str-bool-bool) | Ställer in värdet eller uttrycket som är associerat med denna validering.|
| [get_list_value](/cells/python-net/sv/aspose.cells/validation/get_list_value/#int-int) | Hämta värdet för lista för valideringen för den angivna cellen.|
| [get_value](/cells/python-net/sv/aspose.cells/validation/get_value/#int-int-bool) | Få värdet av validering på den specifika cellen.|
| [add_areas](/cells/python-net/sv/aspose.cells/validation/add_areas/#list-bool-bool) | Tillämpar valideringen på givna områden.|
| [remove_area](/cells/python-net/sv/aspose.cells/validation/remove_area/#aspose.cells.CellArea) | Ta bort valideringsinställningarna i intervallet.|
| [remove_areas](/cells/python-net/sv/aspose.cells/validation/remove_areas/#list) | Tar bort denna validering från givna områden.|
| [remove_a_cell](/cells/python-net/sv/aspose.cells/validation/remove_a_cell/#int-int) | Ta bort valideringsinställningarna i cellen.|
| [copy](/cells/python-net/sv/aspose.cells/validation/copy/#aspose.cells.Validation-aspose.cells.CopyOptions) | Kopia validering.|



###  Exempel

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

###  Se även
* modul [`aspose.cells`](..)
* klass [`CellArea`](/cells/python-net/sv/aspose.cells/cellarea)
