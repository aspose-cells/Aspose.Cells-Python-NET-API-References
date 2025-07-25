---
title: max_column_count proprietà
second_title: Aspose.Cells for Python via .NET API Riferimenti
description:
type: docs
weight: 270
url: /it/aspose.cells/txtloadoptions/max_column_count/
is_root: false
---
##  max_column_count proprietà

Numero massimo di colonne da importare per un foglio.

###  Osservazioni

Le colonne che superano questo limite verranno ignorate
o esteso al foglio successivo secondo [`TxtLoadOptions.extend_to_next_sheet`](/cells/python-net/it/aspose.cells/txtloadoptions#extend_to_next_sheet).
Questo conteggio include le colonne di intestazione ([`TxtLoadOptions.header_columns_count`](/cells/python-net/it/aspose.cells/txtloadoptions#header_columns_count)).
Il suo valore massimo è il limite di colonne del formato file corrispondente, ad esempio per il file xlsx è 16384.
Se questa proprietà non è stata specificata o il valore specificato non è positivo, verrà utilizzato anche il limite massimo.
###  Definizione:
```python
@property
def max_column_count(self):
    ...
@max_column_count.setter
def max_column_count(self, value):
    ...
```

###  Guarda anche
* modulo [`aspose.cells`](../../)
* classe [`TxtLoadOptions`](/cells/python-net/it/aspose.cells/txtloadoptions)
