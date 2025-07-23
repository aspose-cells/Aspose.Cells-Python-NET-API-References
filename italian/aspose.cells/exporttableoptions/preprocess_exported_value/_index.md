---
title: Metodo preprocess_exported_value
second_title: Aspose.Cells for Python via .NET API Riferimenti
description:
type: docs
weight: 20
url: /it/aspose.cells/exporttableoptions/preprocess_exported_value/
is_root: false
---
##  preprocess_exported_value(self, cell_row, cell_column, value) {#int-int-aspose.cells.CellValue}
Preelaborare il valore della cella corrente da esportare.


###  ritorna

Se la cella corrente è stata sostituita con un tipo e/o un valore diverso.


```python

def preprocess_exported_value(self, cell_row, cell_column, value):
    ...
```


| Parametro| Tipo| Descrizione|
| :- | :- | :- |
| cell_row | int | l'indice di riga della cella corrente|
| cell_column | int | l'indice di colonna della cella|
| value | [`CellValue`](/cells/python-net/it/aspose.cells/cellvalue) | valore e tipo di cella corrente|
###  Osservazioni

L'indice di riga e di colonna è l'indice assoluto della cella nel foglio di lavoro, non l'indice nella tabella esportata.
L'utente può controllare il valore della cella corrente nell'implementazione di override di questo metodo,
se la cella corrente deve essere sostituita con un altro tipo e valore,
qui l'implementazione dovrebbe impostare il tipo e il valore previsti sull'oggetto CellValue e restituire true.
Per impostazione predefinita, questo metodo non fa nulla e restituisce false.


###  Guarda anche
* modulo [`aspose.cells`](../../)
* classe [`ExportTableOptions`](/cells/python-net/it/aspose.cells/exporttableoptions)
