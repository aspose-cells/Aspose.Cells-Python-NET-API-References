---
title: Metodo get_default_sheet_name
second_title: Aspose.Cells for Python via .NET API Riferimenti
description:
type: docs
weight: 80
url: /it/aspose.cells/settableglobalizationsettings/get_default_sheet_name/
is_root: false
---
##  get_default_sheet_name(self) {#}
Ottiene il nome del foglio predefinito per l'aggiunta automatica del foglio di lavoro.
L'impostazione predefinita è "Foglio".


###  ritorna

il nome del foglio predefinito per l'aggiunta automatica del foglio di lavoro


```python

def get_default_sheet_name(self):
    ...
```


###  Osservazioni

Aggiunto automaticamente (ad esempio da [`WorksheetCollection.add`](/cells/python-net/it/aspose.cells/worksheetcollection/add))
il nome del foglio sarà il nome specificato più il numero di sequenza.
 Ad esempio, per la Germania l'utente potrebbe volere che il nome del foglio sia "Tabellenblatt2" anziché "Sheet2".
Quindi l'utente può implementare questo metodo per restituire "Tabellenblatt".


###  Guarda anche
* modulo [`aspose.cells`](../../)
* classe [`SettableGlobalizationSettings`](/cells/python-net/it/aspose.cells/settableglobalizationsettings)
