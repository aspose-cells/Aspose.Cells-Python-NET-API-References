---
title: Validation Klasse
second_title: Aspose.Cells for Python via .NET API Referenzen
description:
type: docs
weight: 1610
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
| [input_title](/cells/python-net/de/aspose.cells/validation/input_title) | Stellt den Titel des Eingabedialogfelds zur Datenvalidierung dar.|
| [error_message](/cells/python-net/de/aspose.cells/validation/error_message) | Stellt die Fehlermeldung zur Datenüberprüfung dar.|
| [error_title](/cells/python-net/de/aspose.cells/validation/error_title) | Stellt den Titel des Dialogfelds „Datenvalidierungsfehler“ dar.|
| [show_input](/cells/python-net/de/aspose.cells/validation/show_input) | Gibt an, ob die Eingabemeldung zur Datenvalidierung immer dann angezeigt wird, wenn der Benutzer eine Zelle im Datenvalidierungsbereich auswählt.|
| [show_error](/cells/python-net/de/aspose.cells/validation/show_error) | Gibt an, ob die Datenvalidierungsfehlermeldung angezeigt wird, wenn der Benutzer ungültige Daten eingibt.|
| [ignore_blank](/cells/python-net/de/aspose.cells/validation/ignore_blank) | Gibt an, ob leere Werte bei der Bereichsdatenvalidierung zulässig sind.|
| [formula1](/cells/python-net/de/aspose.cells/validation/formula1) |Stellt den Wert oder Ausdruck dar, der der Datenvalidierung zugeordnet ist.|
| [formula2](/cells/python-net/de/aspose.cells/validation/formula2) |Stellt den Wert oder Ausdruck dar, der der Datenvalidierung zugeordnet ist.|
| [value1](/cells/python-net/de/aspose.cells/validation/value1) | Stellt den ersten Wert dar, der der Datenvalidierung zugeordnet ist.|
| [value2](/cells/python-net/de/aspose.cells/validation/value2) | Stellt den zweiten Wert dar, der der Datenvalidierung zugeordnet ist.|
| [in_cell_drop_down](/cells/python-net/de/aspose.cells/validation/in_cell_drop_down) | Gibt an, ob bei der Datenvalidierung eine Dropdown-Liste angezeigt wird, die akzeptable Werte enthält.|
| [areas](/cells/python-net/de/aspose.cells/validation/areas) | Ruft alle [`CellArea`](/cells/python-net/de/aspose.cells/cellarea) ab, die die Datenvalidierungseinstellungen enthalten.|


###  Methoden
| Methode| Beschreibung|
| :- | :- |
| [get_formula1](/cells/python-net/de/aspose.cells/validation/get_formula1/#bool-bool) | Ruft den Wert oder Ausdruck ab, der dieser Validierung zugeordnet ist.|
| [get_formula1](/cells/python-net/de/aspose.cells/validation/get_formula1/#bool-bool-int-int) | Ruft den Wert oder Ausdruck ab, der dieser Validierung für eine bestimmte Zelle zugeordnet ist.|
| [get_formula2](/cells/python-net/de/aspose.cells/validation/get_formula2/#bool-bool) | Ruft den Wert oder Ausdruck ab, der dieser Validierung zugeordnet ist.|
| [get_formula2](/cells/python-net/de/aspose.cells/validation/get_formula2/#bool-bool-int-int) | Ruft den Wert oder Ausdruck ab, der dieser Validierung für eine bestimmte Zelle zugeordnet ist.|
| [add_area](/cells/python-net/de/aspose.cells/validation/add_area/#aspose.cells.CellArea) | Wendet die Validierung auf den Bereich an.|
| [add_area](/cells/python-net/de/aspose.cells/validation/add_area/#aspose.cells.CellArea-bool-bool) | Wendet die Validierung auf den Bereich an.|
| [set_formula1](/cells/python-net/de/aspose.cells/validation/set_formula1/#str-bool-bool) | Legt den Wert oder Ausdruck fest, der dieser Validierung zugeordnet ist.|
| [set_formula2](/cells/python-net/de/aspose.cells/validation/set_formula2/#str-bool-bool) | Legt den Wert oder Ausdruck fest, der dieser Validierung zugeordnet ist.|
| [get_list_value](/cells/python-net/de/aspose.cells/validation/get_list_value/#int-int) | Rufen Sie den Wert für die Liste der Validierung für die angegebene Zelle ab.|
| [get_value](/cells/python-net/de/aspose.cells/validation/get_value/#int-int-bool) | Rufen Sie den Wert der Validierung für die spezifische Zelle ab.|
| [add_areas](/cells/python-net/de/aspose.cells/validation/add_areas/#list-bool-bool) | Wendet die Validierung auf bestimmte Bereiche an.|
| [remove_area](/cells/python-net/de/aspose.cells/validation/remove_area/#aspose.cells.CellArea) | Entfernen Sie die Validierungseinstellungen im Bereich.|
| [remove_areas](/cells/python-net/de/aspose.cells/validation/remove_areas/#list) | Entfernt diese Validierung aus bestimmten Bereichen.|
| [remove_a_cell](/cells/python-net/de/aspose.cells/validation/remove_a_cell/#int-int) | Entfernen Sie die Validierungseinstellungen in der Zelle.|
| [copy](/cells/python-net/de/aspose.cells/validation/copy/#aspose.cells.Validation-aspose.cells.CopyOptions) | Validierung kopieren.|



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
