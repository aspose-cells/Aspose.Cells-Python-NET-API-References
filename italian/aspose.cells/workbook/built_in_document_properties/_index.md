---
title: built_in_document_properties proprietà
second_title: Aspose.Cells for Python via .NET API Riferimenti
description:
type: docs
weight: 470
url: /it/aspose.cells/workbook/built_in_document_properties/
is_root: false
---
##  built_in_document_properties proprietà

Restituisce una raccolta [`DocumentProperty`](/cells/python-net/it/aspose.cells.properties/documentproperty) che rappresenta tutte le proprietà del documento integrate nel foglio di calcolo.

###  Osservazioni

Non è possibile aggiungere una nuova proprietà all'elenco delle proprietà predefinite del documento. È possibile solo ottenere una proprietà predefinita e modificarne il valore.
Di seguito è riportato l'elenco dei nomi delle proprietà predefinite:

Titolo


Soggetto


Autore


Parole chiave


Commenti


Modello


Ultimo autore


Numero di revisione


Nome dell'applicazione


Data dell'ultima stampa


Data di creazione


Ultimo salvataggio


Tempo totale di modifica


Numero di pagine


Numero di parole


Numero di caratteri


Sicurezza


Categoria


Formato


Manager


Azienda


Numero di byte


Numero di linee


Numero di paragrafi


Numero di diapositive


Numero di note


Numero di diapositive nascoste


Numero di clip multimediali

###  Esempio

```python
from aspose.cells import Workbook

workbook = Workbook()
doc = workbook.built_in_document_properties.get("Author")
doc.value = "John Smith"

```
###  Definizione:
```python
@property
def built_in_document_properties(self):
    ...
```

###  Guarda anche
* modulo [`aspose.cells`](../../)
* classe [`BuiltInDocumentPropertyCollection`](/cells/python-net/it/aspose.cells.properties/builtindocumentpropertycollection)
* classe [`DocumentProperty`](/cells/python-net/it/aspose.cells.properties/documentproperty)
* classe [`Workbook`](/cells/python-net/it/aspose.cells/workbook)
