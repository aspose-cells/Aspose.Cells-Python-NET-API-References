---
title: Validation classe
second_title: Aspose.Cells for Python via .NET API Referenze
description:
type: docs
weight: 1610
url: /it/aspose.cells/validation/
is_root: false
---
##  Validation classe
Rappresenta le impostazioni di convalida dei dati.



Il tipo Validation espone i seguenti membri:

###  Proprietà
| Proprietà| Descrizione|
| :- | :- |
| [operator](/cells/python-net/it/aspose.cells/validation/operator) | Rappresenta l'operatore per la validazione dei dati.|
| [alert_style](/cells/python-net/it/aspose.cells/validation/alert_style) | Rappresenta lo stile dell'avviso di convalida.|
| [type](/cells/python-net/it/aspose.cells/validation/type) | Rappresenta il tipo di convalida dei dati.|
| [input_message](/cells/python-net/it/aspose.cells/validation/input_message) | Rappresenta il messaggio di input di convalida dei dati.|
| [input_title](/cells/python-net/it/aspose.cells/validation/input_title) | Rappresenta il titolo della finestra di dialogo di input di convalida dei dati.|
| [error_message](/cells/python-net/it/aspose.cells/validation/error_message) | Rappresenta il messaggio di errore di convalida dei dati.|
| [error_title](/cells/python-net/it/aspose.cells/validation/error_title) | Rappresenta il titolo della finestra di dialogo dell'errore di convalida dei dati.|
| [show_input](/cells/python-net/it/aspose.cells/validation/show_input) | Indica se il messaggio di input di convalida dei dati verrà visualizzato ogni volta che l'utente seleziona una cella nell'intervallo di convalida dei dati.|
| [show_error](/cells/python-net/it/aspose.cells/validation/show_error) | Indica se il messaggio di errore di convalida dei dati verrà visualizzato ogni volta che l'utente inserisce dati non validi.|
| [ignore_blank](/cells/python-net/it/aspose.cells/validation/ignore_blank) | Indica se i valori vuoti sono consentiti dalla convalida dei dati dell'intervallo.|
| [formula1](/cells/python-net/it/aspose.cells/validation/formula1) |Rappresenta il valore o l'espressione associata alla convalida dei dati.|
| [formula2](/cells/python-net/it/aspose.cells/validation/formula2) |Rappresenta il valore o l'espressione associata alla convalida dei dati.|
| [value1](/cells/python-net/it/aspose.cells/validation/value1) | Rappresenta il primo valore associato alla convalida dei dati.|
| [value2](/cells/python-net/it/aspose.cells/validation/value2) | Rappresenta il secondo valore associato alla convalida dei dati.|
| [in_cell_drop_down](/cells/python-net/it/aspose.cells/validation/in_cell_drop_down) | Indica se la convalida dei dati visualizza un elenco a discesa che contiene valori accettabili.|
| [areas](/cells/python-net/it/aspose.cells/validation/areas) | Ottiene tutti gli [`CellArea`](/cells/python-net/it/aspose.cells/cellarea) che contengono le impostazioni di convalida dei dati.|


###  Metodi
| Metodo| Descrizione|
| :- | :- |
| [get_formula1](/cells/python-net/it/aspose.cells/validation/get_formula1/#bool-bool) | Ottiene il valore o l'espressione associata a questa convalida.|
| [get_formula1](/cells/python-net/it/aspose.cells/validation/get_formula1/#bool-bool-int-int) | Ottiene il valore o l'espressione associata a questa convalida per una cella specifica.|
| [get_formula2](/cells/python-net/it/aspose.cells/validation/get_formula2/#bool-bool) | Ottiene il valore o l'espressione associata a questa convalida.|
| [get_formula2](/cells/python-net/it/aspose.cells/validation/get_formula2/#bool-bool-int-int) | Ottiene il valore o l'espressione associata a questa convalida per una cella specifica.|
| [add_area](/cells/python-net/it/aspose.cells/validation/add_area/#aspose.cells.CellArea) | Applica la convalida all'area.|
| [add_area](/cells/python-net/it/aspose.cells/validation/add_area/#aspose.cells.CellArea-bool-bool) | Applica la convalida all'area.|
| [set_formula1](/cells/python-net/it/aspose.cells/validation/set_formula1/#str-bool-bool) | Imposta il valore o l'espressione associata a questa convalida.|
| [set_formula2](/cells/python-net/it/aspose.cells/validation/set_formula2/#str-bool-bool) | Imposta il valore o l'espressione associata a questa convalida.|
| [get_list_value](/cells/python-net/it/aspose.cells/validation/get_list_value/#int-int) | Ottieni il valore per l'elenco della convalida per la cella specificata.|
| [get_value](/cells/python-net/it/aspose.cells/validation/get_value/#int-int-bool) | Ottieni il valore di convalida sulla cella specifica.|
| [add_areas](/cells/python-net/it/aspose.cells/validation/add_areas/#list-bool-bool) | Applica la convalida a determinate aree.|
| [remove_area](/cells/python-net/it/aspose.cells/validation/remove_area/#aspose.cells.CellArea) | Rimuovere le impostazioni di convalida nell'intervallo.|
| [remove_areas](/cells/python-net/it/aspose.cells/validation/remove_areas/#list) | Rimuove questa convalida da determinate aree.|
| [remove_a_cell](/cells/python-net/it/aspose.cells/validation/remove_a_cell/#int-int) | Rimuovere le impostazioni di convalida nella cella.|
| [copy](/cells/python-net/it/aspose.cells/validation/copy/#aspose.cells.Validation-aspose.cells.CopyOptions) | Convalida della copia.|



###  Esempio

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

###  Guarda anche
* modulo [`aspose.cells`](..)
* classe [`CellArea`](/cells/python-net/it/aspose.cells/cellarea)
