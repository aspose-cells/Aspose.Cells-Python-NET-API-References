---
title: VbaProject classe
second_title: Aspose.Cells for Python via .NET API Riferimenti
description:
type: docs
weight: 30
url: /it/aspose.cells.vba/vbaproject/
is_root: false
---
##  VbaProject classe
Rappresenta il progetto VBA.



Il tipo VbaProject espone i seguenti membri:

###  Proprietà
| Proprietà| Descrizione|
| :- | :- |
| [is_valid_signed](/cells/python-net/it/aspose.cells.vba/vbaproject/is_valid_signed) | Indica se la firma del progetto VBA è valida o meno.|
| [cert_raw_data](/cells/python-net/it/aspose.cells.vba/vbaproject/cert_raw_data) | Ottiene i dati grezzi del certificato se questo progetto VBA è firmato.|
| [encoding](/cells/python-net/it/aspose.cells.vba/vbaproject/encoding) |Ottiene e imposta la codifica del progetto VBA.|
| [name](/cells/python-net/it/aspose.cells.vba/vbaproject/name) | Ottiene e imposta il nome del progetto VBA.|
| [is_signed](/cells/python-net/it/aspose.cells.vba/vbaproject/is_signed) | Indica se il codice VBA è firmato o meno.|
| [is_protected](/cells/python-net/it/aspose.cells.vba/vbaproject/is_protected) | Indica se questo progetto VBA è protetto.|
| [islocked_for_viewing](/cells/python-net/it/aspose.cells.vba/vbaproject/islocked_for_viewing) | Indica se questo progetto VBA è bloccato per la visualizzazione.|
| [modules](/cells/python-net/it/aspose.cells.vba/vbaproject/modules) | Ottiene tutti gli oggetti [`VbaModule`](/cells/python-net/it/aspose.cells.vba/vbamodule).|
| [references](/cells/python-net/it/aspose.cells.vba/vbaproject/references) | Ottiene tutti i riferimenti del progetto VBA.|


###  Metodi
| Metodo| Descrizione|
| :- | :- |
| [`sign(self, digital_signature)`](/cells/python-net/it/aspose.cells.vba/vbaproject/sign/#aspose.cells.digitalsignatures.digitalsignature) | Firma questo progetto VBA con una firma digitale|
| [`protect(self, islocked_for_viewing, password)`](/cells/python-net/it/aspose.cells.vba/vbaproject/protect/#bool-str) | Protegge o rimuove la protezione da questo progetto VBA.|
| [`copy(self, source)`](/cells/python-net/it/aspose.cells.vba/vbaproject/copy/#aspose.cells.vba.vbaproject) | Copia il progetto VBA da un altro file.|
| [`validate_password(self, password)`](/cells/python-net/it/aspose.cells.vba/vbaproject/validate_password/#str) | Convalida la password di protezione.|



###  Esempio

```python
from aspose.cells import Workbook

# Instantiating a Workbook object
workbook = Workbook()
#  Init VBA project.
vbaProject = workbook.vba_project
# Saving the Excel file
workbook.save("book1.xlsm")

```

###  Guarda anche
* modulo [`aspose.cells.vba`](..)
* classe [`VbaModule`](/cells/python-net/it/aspose.cells.vba/vbamodule)
