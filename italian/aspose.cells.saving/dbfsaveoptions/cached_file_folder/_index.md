---
title: cached_file_folder proprietà
second_title: Aspose.Cells for Python via .NET API Riferimenti
description:
type: docs
weight: 30
url: /it/aspose.cells.saving/dbfsaveoptions/cached_file_folder/
is_root: false
---
##  cached_file_folder proprietà

Cartella per i file temporanei che possono essere utilizzati come cache di dati.

###  Osservazioni

Se la cartella non è stata specificata,
il valore predefinito è [`CellsHelper.get_cache_folder`](/cells/python-net/it/aspose.cells/cellshelper/get_cache_folder).
Se il suo valore predefinito è null o vuoto, oppure è stato specificato come null o vuoto,
in questo modo non verrà utilizzato alcun file di cache durante il salvataggio della cartella di lavoro.
###  Definizione:
```python
@property
def cached_file_folder(self):
    ...
@cached_file_folder.setter
def cached_file_folder(self, value):
    ...
```

###  Guarda anche
* modulo [`aspose.cells.saving`](../../)
* classe [`DbfSaveOptions`](/cells/python-net/it/aspose.cells.saving/dbfsaveoptions)
