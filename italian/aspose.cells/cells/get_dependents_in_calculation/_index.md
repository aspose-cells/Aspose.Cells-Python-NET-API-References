---
title: Metodo get_dependents_in_calculation
second_title: Aspose.Cells for Python via .NET API Riferimenti
description:
type: docs
weight: 400
url: /it/aspose.cells/cells/get_dependents_in_calculation/
is_root: false
---
##  get_dependents_in_calculation(self, row, column, recursive) {#int-int-bool}
Ottiene tutte le celle il cui risultato calcolato dipende da una cella specifica.


###  ritorna

Enumeratore per enumerare tutti i dipendenti (Cell oggetti)


```python

def get_dependents_in_calculation(self, row, column, recursive):
    ...
```


| Parametro| Tipo| Descrizione|
| :- | :- | :- |
| row | int | Indice di riga della cella specifica|
| column | int |Indice di colonna della cella specifica.|
| recursive | bool | Se restituisce quei dipendenti che non fanno riferimento direttamente alla cella specifica<br/> ma riferimento ad altre foglie di quella cellula.|
###  Osservazioni

Per utilizzare questo metodo, assicurati che la cartella di lavoro sia stata impostata con il valore true per
[`FormulaSettings.enable_calculation_chain`](/cells/python-net/it/aspose.cells/formulasettings#enable_calculation_chain) ed è stato calcolato completamente con questa impostazione.
Se non esiste alcun riferimento a una formula per questa cella, verrà restituito null.
Per maggiori dettagli ed esempi, vedere [`Cell.get_dependents_in_calculation`](/cells/python-net/it/aspose.cells/cell/get_dependents_in_calculation)


###  Guarda anche
* modulo [`aspose.cells`](../../)
* classe [`Cells`](/cells/python-net/it/aspose.cells/cells)
