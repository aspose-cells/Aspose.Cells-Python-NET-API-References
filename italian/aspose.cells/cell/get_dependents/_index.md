---
title: Metodo get_dependents
second_title: Aspose.Cells for Python via .NET API Riferimenti
description:
type: docs
weight: 90
url: /it/aspose.cells/cell/get_dependents/
is_root: false
---
##  get_dependents(self, is_all) {#bool}
Ottieni tutte le celle la cui formula fa riferimento direttamente a questa cella.



```python

def get_dependents(self, is_all):
    ...
```


| Parametro| Tipo| Descrizione|
| :- | :- | :- |
| is_all | bool |Indica se controllare le formule in altri fogli di lavoro|
###  Osservazioni

* Se un riferimento contenente questa cella appare nella formula di una cella, quella cella verrà presa come

il dipendente di questa cella, indipendentemente dal fatto che il riferimento o questa cella venga utilizzata o meno durante il calcolo.
Ad esempio, sebbene la cella A2 nella formula "=SE(VERO;A1;A2)" non venga utilizzata durante il calcolo,
questa formula deve ancora essere considerata dipendente da A2.
Per ottenere le formule i cui risultati calcolati dipendono da questa cella, utilizzare [`Cell.get_dependents_in_calculation`](/cells/python-net/it/aspose.cells/cell/get_dependents_in_calculation). Quando si tracciano i dipendenti per una cella, tutte le formule nella cartella di lavoro o nel foglio di lavoro verranno analizzate e controllate.
Quindi è un processo che richiede molto tempo. Se l'utente ha bisogno di tracciare i dipendenti per molte celle, utilizzando questo metodo
Causa prestazioni scadenti. Per motivi di prestazioni, si consiglia di utilizzare [`Cell.get_dependents_in_calculation`](/cells/python-net/it/aspose.cells/cell/get_dependents_in_calculation).
Oppure, l'utente può raccogliere la mappa dei precedenti di tutte le celle da [`Cell.get_precedents`](/cells/python-net/it/aspose.cells/cell/get_precedents) in primo luogo,
e quindi costruire la mappa dei dipendenti in base alla mappa dei precedenti.

* Se un riferimento contenente questa cella appare nella formula di una cella, quella cella verrà presa come
il dipendente di questa cella, indipendentemente dal fatto che il riferimento o questa cella venga utilizzata o meno durante il calcolo.
Ad esempio, sebbene la cella A2 nella formula "=SE(VERO;A1;A2)" non venga utilizzata durante il calcolo,
questa formula deve ancora essere considerata dipendente da A2.
Per ottenere le formule i cui risultati calcolati dipendono da questa cella, utilizzare [`Cell.get_dependents_in_calculation`](/cells/python-net/it/aspose.cells/cell/get_dependents_in_calculation). Quando si tracciano i dipendenti per una cella, tutte le formule nella cartella di lavoro o nel foglio di lavoro verranno analizzate e controllate.
Quindi è un processo che richiede molto tempo. Se l'utente ha bisogno di tracciare i dipendenti per molte celle, utilizzando questo metodo
Causa prestazioni scadenti. Per motivi di prestazioni, si consiglia di utilizzare [`Cell.get_dependents_in_calculation`](/cells/python-net/it/aspose.cells/cell/get_dependents_in_calculation).
Oppure, l'utente può raccogliere la mappa dei precedenti di tutte le celle da [`Cell.get_precedents`](/cells/python-net/it/aspose.cells/cell/get_precedents) in primo luogo,
e quindi costruire la mappa dei dipendenti in base alla mappa dei precedenti.

* Se un riferimento contenente questa cella appare nella formula di una cella, quella cella verrà presa come
il dipendente di questa cella, indipendentemente dal fatto che il riferimento o questa cella venga utilizzata o meno durante il calcolo.
Ad esempio, sebbene la cella A2 nella formula "=SE(VERO;A1;A2)" non venga utilizzata durante il calcolo,
questa formula deve ancora essere considerata dipendente da A2.
Per ottenere le formule i cui risultati calcolati dipendono da questa cella, utilizzare [`Cell.get_dependents_in_calculation`](/cells/python-net/it/aspose.cells/cell/get_dependents_in_calculation). Quando si tracciano i dipendenti per una cella, tutte le formule nella cartella di lavoro o nel foglio di lavoro verranno analizzate e controllate.
Quindi è un processo che richiede molto tempo. Se l'utente ha bisogno di tracciare i dipendenti per molte celle, utilizzando questo metodo
Causa prestazioni scadenti. Per motivi di prestazioni, si consiglia di utilizzare [`Cell.get_dependents_in_calculation`](/cells/python-net/it/aspose.cells/cell/get_dependents_in_calculation).
Oppure, l'utente può raccogliere la mappa dei precedenti di tutte le celle da [`Cell.get_precedents`](/cells/python-net/it/aspose.cells/cell/get_precedents) in primo luogo,
e quindi costruire la mappa dei dipendenti in base alla mappa dei precedenti.
###  Esempio

```python
from aspose.cells import Workbook

workbook = Workbook()
cells = workbook.worksheets[0].cells
cells.get("A1").formula = "=B1+SUM(B1:B10)+[Book1.xls]Sheet1!B2"
cells.get("A2").formula = "=IF(TRUE,B2,B1)"
dependents = cells.get("B1").get_dependents(True)
for i in range(len(dependents)):
    print(dependents[i].name)

```



###  Guarda anche
* modulo [`aspose.cells`](../../)
* classe [`Cell`](/cells/python-net/it/aspose.cells/cell)
