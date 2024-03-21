---
title: check_excel_restriction proprietà
second_title: Aspose.Cells for Python via .NET API Referenze
description:
type: docs
weight: 90
url: /it/aspose.cells/ebookloadoptions/check_excel_restriction/
is_root: false
---
##  check_excel_restriction proprietà

Se controllare la restrizione del file Excel quando l'utente modifica gli oggetti correlati alle celle.
Ad esempio, Excel non consente l'immissione di valori di stringa più lunghi di 32K.
Quando inserisci un valore più lungo di 32 KB, ad esempio Cell.PutValue(string), se questa proprietà è vera, otterrai un'eccezione.
Se questa proprietà è falsa, accetteremo il valore della stringa di input come valore della cella in modo che venga visualizzato in seguito
è possibile restituire il valore stringa completo per altri formati di file come CSV.
Tuttavia, se hai impostato un tipo di valore non valido per il formato file Excel,
non dovresti salvare la cartella di lavoro come formato di file Excel in un secondo momento. Altrimenti potrebbe esserci un errore imprevisto per il file Excel generato.
###  Definizione:
```python
@property
def check_excel_restriction(self):
    ...
@check_excel_restriction.setter
def check_excel_restriction(self, value):
    ...
```

###  Guarda anche
* modulo [`aspose.cells`](../../)
* classe [`EbookLoadOptions`](/cells/python-net/it/aspose.cells/ebookloadoptions)
