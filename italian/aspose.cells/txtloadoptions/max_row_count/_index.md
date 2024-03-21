---
title: max_row_count proprietà
second_title: Aspose.Cells for Python via .NET API Referenze
description:
type: docs
weight: 300
url: /it/aspose.cells/txtloadoptions/max_row_count/
is_root: false
---
##  max_row_count proprietà

Il numero massimo di righe da importare per un foglio.

###  Osservazioni

Le righe che superano questo limite verranno ignorate
oppure esteso al foglio successivo secondo [`TxtLoadOptions.extend_to_next_sheet`](/cells/python-net/it/aspose.cells/txtloadoptions#extend_to_next_sheet).
Questo conteggio include le righe di intestazione ([`TxtLoadOptions.header_rows_count`](/cells/python-net/it/aspose.cells/txtloadoptions#header_rows_count)).
Il valore massimo consentito è il limite di riga del formato di file corrispondente, ad esempio per il file xlsx è 1048576.
Se questa proprietà non è stata specificata o il valore specificato non è positivo, verrà utilizzato anche il limite massimo.
###  Definizione:
```python
@property
def max_row_count(self):
    ...
@max_row_count.setter
def max_row_count(self, value):
    ...
```

###  Guarda anche
* modulo [`aspose.cells`](../../)
* classe [`TxtLoadOptions`](/cells/python-net/it/aspose.cells/txtloadoptions)
