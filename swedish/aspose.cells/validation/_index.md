---
title: Validation klass
second_title: Aspose.Cells for Python via .NET API Referenser
description:
type: docs
weight: 1520
url: /sv/aspose.cells/validation/
is_root: false
---
##  Validation klass
Representerar datavalidering.inställningar.



Typen Validation avslöjar följande medlemmar:

###  Egenskaper
| Fast egendom| Beskrivning|
| :- | :- |
| [operator](/cells/python-net/sv/aspose.cells/validation/operator) | Representerar operatorn för datavalideringen.|
| [alert_style](/cells/python-net/sv/aspose.cells/validation/alert_style) | Representerar valideringsaviseringsstilen.|
| [type](/cells/python-net/sv/aspose.cells/validation/type) | Representerar datavalideringstypen.|
| [input_message](/cells/python-net/sv/aspose.cells/validation/input_message) | Representerar inmatningsmeddelandet för datavalidering.|
| [input_title](/cells/python-net/sv/aspose.cells/validation/input_title) | Representerar titeln på dialogrutan för datavalideringsinmatning.|
| [error_message](/cells/python-net/sv/aspose.cells/validation/error_message) | Representerar felmeddelandet för datavalidering.|
| [error_title](/cells/python-net/sv/aspose.cells/validation/error_title) | Representerar titeln på dialogrutan för datavalideringsfel.|
| [show_input](/cells/python-net/sv/aspose.cells/validation/show_input) | Anger om meddelandet för datavalidering ska visas när användaren väljer en cell i datavalideringsområdet.|
| [show_error](/cells/python-net/sv/aspose.cells/validation/show_error) | Anger om felmeddelandet för datavalidering ska visas när användaren anger ogiltiga data.|
| [ignore_blank](/cells/python-net/sv/aspose.cells/validation/ignore_blank) |Anger om tomma värden är tillåtna enligt valideringen av intervalldata.|
| [formula1](/cells/python-net/sv/aspose.cells/validation/formula1) | Representerar värdet eller uttrycket som är associerat med datavalideringen.|
| [formula2](/cells/python-net/sv/aspose.cells/validation/formula2) | Representerar värdet eller uttrycket som är associerat med datavalideringen.|
| [value1](/cells/python-net/sv/aspose.cells/validation/value1) | Representerar det första värdet som är associerat med datavalideringen.|
| [value2](/cells/python-net/sv/aspose.cells/validation/value2) | Representerar det andra värdet som är associerat med datavalideringen.|
| [in_cell_drop_down](/cells/python-net/sv/aspose.cells/validation/in_cell_drop_down) | Anger om datavalidering visar en rullgardinsmeny som innehåller acceptabla värden.|
| [areas](/cells/python-net/sv/aspose.cells/validation/areas) | Hämtar alla [`CellArea`](/cells/python-net/sv/aspose.cells/cellarea) som innehåller inställningarna för datavalidering.|


###  Metoder
| Metod| Beskrivning|
| :- | :- |
| [`get_formula1(self, is_r1c1, is_local)`](/cells/python-net/sv/aspose.cells/validation/get_formula1/#bool-bool) | Hämtar värdet eller uttrycket som är associerat med denna validering.|
| [`get_formula1(self, is_r1c1, is_local, row, column)`](/cells/python-net/sv/aspose.cells/validation/get_formula1/#bool-bool-int-int) | Hämtar värdet eller uttrycket som är associerat med denna validering för en specifik cell.|
| [`get_formula2(self, is_r1c1, is_local)`](/cells/python-net/sv/aspose.cells/validation/get_formula2/#bool-bool) | Hämtar värdet eller uttrycket som är associerat med denna validering.|
| [`get_formula2(self, is_r1c1, is_local, row, column)`](/cells/python-net/sv/aspose.cells/validation/get_formula2/#bool-bool-int-int) | Hämtar värdet eller uttrycket som är associerat med denna validering för en specifik cell.|
| [`add_area(self, cell_area)`](/cells/python-net/sv/aspose.cells/validation/add_area/#aspose.cells.cellarea) | Tillämpar valideringen på området.|
| [`add_area(self, cell_area, check_intersection, check_edge)`](/cells/python-net/sv/aspose.cells/validation/add_area/#aspose.cells.cellarea-bool-bool) | Tillämpar valideringen på området.|
| [`set_formula1(self, formula, is_r1c1, is_local)`](/cells/python-net/sv/aspose.cells/validation/set_formula1/#str-bool-bool) | Anger värdet eller uttrycket som är associerat med denna validering.|
| [`set_formula2(self, formula, is_r1c1, is_local)`](/cells/python-net/sv/aspose.cells/validation/set_formula2/#str-bool-bool) | Anger värdet eller uttrycket som är associerat med denna validering.|
| [`get_list_value(self, row, column)`](/cells/python-net/sv/aspose.cells/validation/get_list_value/#int-int) | Hämta värdet för listan för valideringen för den angivna cellen.|
| [`get_value(self, row, column, is_value1)`](/cells/python-net/sv/aspose.cells/validation/get_value/#int-int-bool) | Hämta valideringsvärdet för den specifika cellen.|
| [`add_areas(self, areas, check_intersection, check_edge)`](/cells/python-net/sv/aspose.cells/validation/add_areas/#list-bool-bool) | Tillämpar valideringen på givna områden.|
| [`remove_area(self, cell_area)`](/cells/python-net/sv/aspose.cells/validation/remove_area/#aspose.cells.cellarea) | Ta bort valideringsinställningarna i intervallet.|
| [`remove_areas(self, areas)`](/cells/python-net/sv/aspose.cells/validation/remove_areas/#list) |Tar bort denna validering från angivna områden.|
| [`remove_a_cell(self, row, column)`](/cells/python-net/sv/aspose.cells/validation/remove_a_cell/#int-int) | Ta bort valideringsinställningarna i cellen.|
| [`copy(self, source, copy_option)`](/cells/python-net/sv/aspose.cells/validation/copy/#aspose.cells.validation-aspose.cells.copyoptions) | Kopieringsvalidering.|



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
