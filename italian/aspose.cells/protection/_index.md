---
title: Protection classe
second_title: Aspose.Cells for Python via .NET API Riferimenti
description:
type: docs
weight: 1150
url: /it/aspose.cells/protection/
is_root: false
---
##  Protection classe
Rappresenta i vari tipi di opzioni di protezione disponibili per un foglio di lavoro.



Il tipo Protection espone i seguenti membri:

###  Proprietà
| Proprietà| Descrizione|
| :- | :- |
| [allow_deleting_column](/cells/python-net/it/aspose.cells/protection/allow_deleting_column) | Indica se è consentita l'eliminazione di colonne in un foglio di lavoro protetto.|
| [allow_deleting_row](/cells/python-net/it/aspose.cells/protection/allow_deleting_row) | Indica se è consentita l'eliminazione di righe in un foglio di lavoro protetto.|
| [allow_filtering](/cells/python-net/it/aspose.cells/protection/allow_filtering) | Indica se all'utente è consentito utilizzare un filtro automatico creato prima che il foglio fosse protetto.|
| [allow_formatting_cell](/cells/python-net/it/aspose.cells/protection/allow_formatting_cell) | Indica se la formattazione delle celle è consentita in un foglio di lavoro protetto.|
| [allow_formatting_column](/cells/python-net/it/aspose.cells/protection/allow_formatting_column) | Rappresenta se la formattazione delle colonne è consentita su un foglio di lavoro protetto|
| [allow_formatting_row](/cells/python-net/it/aspose.cells/protection/allow_formatting_row) |Rappresenta se la formattazione delle righe è consentita su un foglio di lavoro protetto|
| [allow_inserting_column](/cells/python-net/it/aspose.cells/protection/allow_inserting_column) | Rappresenta se l'inserimento di colonne è consentito su un foglio di lavoro protetto|
| [allow_inserting_hyperlink](/cells/python-net/it/aspose.cells/protection/allow_inserting_hyperlink) | Rappresenta se l'inserimento di collegamenti ipertestuali è consentito in un foglio di lavoro protetto|
| [allow_inserting_row](/cells/python-net/it/aspose.cells/protection/allow_inserting_row) | Rappresenta se l'inserimento di righe è consentito su un foglio di lavoro protetto|
| [allow_sorting](/cells/python-net/it/aspose.cells/protection/allow_sorting) | Indica se l'opzione di ordinamento è consentita su un foglio di lavoro protetto.|
| [allow_using_pivot_table](/cells/python-net/it/aspose.cells/protection/allow_using_pivot_table) | Indica se all'utente è consentito manipolare le tabelle pivot su un foglio di lavoro protetto.|
| [allow_editing_content](/cells/python-net/it/aspose.cells/protection/allow_editing_content) | Indica se all'utente è consentito modificare il contenuto delle celle bloccate in un foglio di lavoro protetto.|
| [allow_editing_object](/cells/python-net/it/aspose.cells/protection/allow_editing_object) | Indica se all'utente è consentito manipolare oggetti di disegno su un foglio di lavoro protetto.|
| [allow_editing_scenario](/cells/python-net/it/aspose.cells/protection/allow_editing_scenario) | Indica se all'utente è consentito modificare gli scenari su un foglio di lavoro protetto.|
| [allow_selecting_locked_cell](/cells/python-net/it/aspose.cells/protection/allow_selecting_locked_cell) | Indica se all'utente è consentito selezionare celle bloccate su un foglio di lavoro protetto.|
| [allow_selecting_unlocked_cell](/cells/python-net/it/aspose.cells/protection/allow_selecting_unlocked_cell) | Indica se all'utente è consentito selezionare celle sbloccate su un foglio di lavoro protetto.|
| [password](/cells/python-net/it/aspose.cells/protection/password) | Rappresenta la password per proteggere il foglio di lavoro.|
| [is_protected_with_password](/cells/python-net/it/aspose.cells/protection/is_protected_with_password) | Indica se i fogli di lavoro sono protetti da password.|


###  Metodi
| Metodo| Descrizione|
| :- | :- |
| [`copy(self, source)`](/cells/python-net/it/aspose.cells/protection/copy/#aspose.cells.protection) |Informazioni sulla protezione dalla copia.|
| [`verify_password(self, password)`](/cells/python-net/it/aspose.cells/protection/verify_password/#str) | Verifica la password.|
| [`get_password_hash(self)`](/cells/python-net/it/aspose.cells/protection/get_password_hash/#) | Ottiene l'hash della password corrente.|



###  Esempio

```python
from aspose.cells import Workbook

# Instantiating a Workbook object
workbook = Workbook()
worksheet = workbook.worksheets[0]
# Allowing users to select locked cells of the worksheet
worksheet.protection.allow_selecting_locked_cell = True
# Allowing users to select unlocked cells of the worksheet
worksheet.protection.allow_selecting_unlocked_cell = True

```

###  Guarda anche
* modulo [`aspose.cells`](..)
