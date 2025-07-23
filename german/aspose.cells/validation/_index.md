---
title: Validation Klasse
second_title: Aspose.Cells for Python via .NET API Referenzen
description:
type: docs
weight: 1520
url: /de/aspose.cells/validation/
is_root: false
---
##  Validation Klasse
Stellt Datenvalidierungseinstellungen dar.



Der Typ Validation macht die folgenden Member verfügbar:

###  Eigenschaften
| Eigentum| Beschreibung|
| :- | :- |
| [operator](/cells/python-net/de/aspose.cells/validation/operator) | Stellt den Operator für die Datenvalidierung dar.|
| [alert_style](/cells/python-net/de/aspose.cells/validation/alert_style) | Stellt den Validierungswarnungsstil dar.|
| [type](/cells/python-net/de/aspose.cells/validation/type) | Stellt den Datenvalidierungstyp dar.|
| [input_message](/cells/python-net/de/aspose.cells/validation/input_message) | Stellt die Eingabenachricht zur Datenvalidierung dar.|
| [input_title](/cells/python-net/de/aspose.cells/validation/input_title) | Stellt den Titel des Eingabedialogfelds zur Datenüberprüfung dar.|
| [error_message](/cells/python-net/de/aspose.cells/validation/error_message) | Stellt die Fehlermeldung zur Datenüberprüfung dar.|
| [error_title](/cells/python-net/de/aspose.cells/validation/error_title) | Stellt den Titel des Dialogfelds mit dem Datenvalidierungsfehler dar.|
| [show_input](/cells/python-net/de/aspose.cells/validation/show_input) | Gibt an, ob die Eingabemeldung zur Datenüberprüfung angezeigt wird, wenn der Benutzer eine Zelle im Datenüberprüfungsbereich auswählt.|
| [show_error](/cells/python-net/de/aspose.cells/validation/show_error) | Gibt an, ob die Fehlermeldung zur Datenüberprüfung angezeigt wird, wenn der Benutzer ungültige Daten eingibt.|
| [ignore_blank](/cells/python-net/de/aspose.cells/validation/ignore_blank) |Gibt an, ob bei der Bereichsdatenüberprüfung leere Werte zulässig sind.|
| [formula1](/cells/python-net/de/aspose.cells/validation/formula1) | Stellt den mit der Datenüberprüfung verknüpften Wert oder Ausdruck dar.|
| [formula2](/cells/python-net/de/aspose.cells/validation/formula2) | Stellt den mit der Datenüberprüfung verknüpften Wert oder Ausdruck dar.|
| [value1](/cells/python-net/de/aspose.cells/validation/value1) | Stellt den ersten mit der Datenvalidierung verknüpften Wert dar.|
| [value2](/cells/python-net/de/aspose.cells/validation/value2) | Stellt den zweiten Wert dar, der mit der Datenvalidierung verknüpft ist.|
| [in_cell_drop_down](/cells/python-net/de/aspose.cells/validation/in_cell_drop_down) | Gibt an, ob bei der Datenüberprüfung eine Dropdownliste mit zulässigen Werten angezeigt wird.|
| [areas](/cells/python-net/de/aspose.cells/validation/areas) | Ruft alle [`CellArea`](/cells/python-net/de/aspose.cells/cellarea) ab, die die Datenvalidierungseinstellungen enthalten.|


###  Methoden
| Methode| Beschreibung|
| :- | :- |
| [`get_formula1(self, is_r1c1, is_local)`](/cells/python-net/de/aspose.cells/validation/get_formula1/#bool-bool) | Ruft den mit dieser Validierung verknüpften Wert oder Ausdruck ab.|
| [`get_formula1(self, is_r1c1, is_local, row, column)`](/cells/python-net/de/aspose.cells/validation/get_formula1/#bool-bool-int-int) | Ruft den Wert oder Ausdruck ab, der dieser Validierung für eine bestimmte Zelle zugeordnet ist.|
| [`get_formula2(self, is_r1c1, is_local)`](/cells/python-net/de/aspose.cells/validation/get_formula2/#bool-bool) | Ruft den mit dieser Validierung verknüpften Wert oder Ausdruck ab.|
| [`get_formula2(self, is_r1c1, is_local, row, column)`](/cells/python-net/de/aspose.cells/validation/get_formula2/#bool-bool-int-int) | Ruft den Wert oder Ausdruck ab, der dieser Validierung für eine bestimmte Zelle zugeordnet ist.|
| [`add_area(self, cell_area)`](/cells/python-net/de/aspose.cells/validation/add_area/#aspose.cells.cellarea) | Wendet die Validierung auf den Bereich an.|
| [`add_area(self, cell_area, check_intersection, check_edge)`](/cells/python-net/de/aspose.cells/validation/add_area/#aspose.cells.cellarea-bool-bool) | Wendet die Validierung auf den Bereich an.|
| [`set_formula1(self, formula, is_r1c1, is_local)`](/cells/python-net/de/aspose.cells/validation/set_formula1/#str-bool-bool) | Legt den Wert oder Ausdruck fest, der mit dieser Validierung verknüpft ist.|
| [`set_formula2(self, formula, is_r1c1, is_local)`](/cells/python-net/de/aspose.cells/validation/set_formula2/#str-bool-bool) | Legt den Wert oder Ausdruck fest, der mit dieser Validierung verknüpft ist.|
| [`get_list_value(self, row, column)`](/cells/python-net/de/aspose.cells/validation/get_list_value/#int-int) | Ruft den Wert für die Liste der Validierungen für die angegebene Zelle ab.|
| [`get_value(self, row, column, is_value1)`](/cells/python-net/de/aspose.cells/validation/get_value/#int-int-bool) | Rufen Sie den Validierungswert für die jeweilige Zelle ab.|
| [`add_areas(self, areas, check_intersection, check_edge)`](/cells/python-net/de/aspose.cells/validation/add_areas/#list-bool-bool) | Wendet die Validierung auf angegebene Bereiche an.|
| [`remove_area(self, cell_area)`](/cells/python-net/de/aspose.cells/validation/remove_area/#aspose.cells.cellarea) | Entfernen Sie die Validierungseinstellungen im Bereich.|
| [`remove_areas(self, areas)`](/cells/python-net/de/aspose.cells/validation/remove_areas/#list) |Entfernt diese Validierung aus bestimmten Bereichen.|
| [`remove_a_cell(self, row, column)`](/cells/python-net/de/aspose.cells/validation/remove_a_cell/#int-int) | Entfernen Sie die Validierungseinstellungen in der Zelle.|
| [`copy(self, source, copy_option)`](/cells/python-net/de/aspose.cells/validation/copy/#aspose.cells.validation-aspose.cells.copyoptions) | Kopiervalidierung.|



###  Beispiel

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

###  Siehe auch
* Modul [`aspose.cells`](..)
* Klasse [`CellArea`](/cells/python-net/de/aspose.cells/cellarea)
