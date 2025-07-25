---
title: check_excel_restriction proprietà
second_title: Aspose.Cells for Python via .NET API Riferimenti
description:
type: docs
weight: 70
url: /it/aspose.cells/jsonloadoptions/check_excel_restriction/
is_root: false
---
##  check_excel_restriction proprietà

Se verificare la restrizione del file Excel quando l'utente modifica celle con oggetti correlati.
Ad esempio, Excel non consente di immettere valori stringa più lunghi di 32K.
Quando si immette un valore più lungo di 32K, ad esempio Cell.PutValue(string), se questa proprietà è vera, si otterrà un'eccezione.
Se questa proprietà è falsa, accetteremo il valore della stringa di input come valore della cella in modo che in seguito
è possibile restituire il valore stringa completo per altri formati di file, ad esempio CSV.
Tuttavia, se hai impostato un valore di questo tipo che non è valido per il formato di file Excel,
Non salvare la cartella di lavoro in formato Excel in un secondo momento. In caso contrario, potrebbe verificarsi un errore imprevisto nel file Excel generato.
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
* classe [`JsonLoadOptions`](/cells/python-net/it/aspose.cells/jsonloadoptions)
