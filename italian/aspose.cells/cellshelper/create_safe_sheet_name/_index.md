---
title: Metodo create_safe_sheet_name
second_title: Aspose.Cells for Python via .NET API Riferimenti
description:
type: docs
weight: 90
url: /it/aspose.cells/cellshelper/create_safe_sheet_name/
is_root: false
---
##  create_safe_sheet_name(, nome_proposta){#str}
Controlla il nome del foglio specificato e ne crea uno valido quando necessario.
Se il nome del foglio specificato è conforme alle regole del nome del foglio Excel, allora restituiscilo.
Altrimenti la stringa verrà troncata se la lunghezza supera il limite
e i caratteri non validi verranno sostituiti con ' ', quindi verrà restituito il valore stringa ricostruito.


###  ritorna




```python

@staticmethod
def create_safe_sheet_name(name_proposal):
    ...
```


| Parametro| Tipo| Descrizione|
| :- | :- | :- |
| name_proposal | str | nome del foglio da utilizzare|


##  create_safe_sheet_name(, proposta_nome, sostituisci_carattere){#str-char}
Controlla il nome del foglio specificato e ne crea uno valido quando necessario.
Se il nome del foglio specificato è conforme alle regole del nome del foglio Excel, allora restituiscilo.
Altrimenti la stringa verrà troncata se la lunghezza supera il limite
e i caratteri non validi verranno sostituiti con il carattere specificato, quindi verrà restituito il valore stringa ricostruito.


###  ritorna




```python

@staticmethod
def create_safe_sheet_name(name_proposal, replace_char):
    ...
```


| Parametro| Tipo| Descrizione|
| :- | :- | :- |
| name_proposal | str | nome del foglio da utilizzare|
| replace_char | char | carattere che verrà utilizzato per sostituire i caratteri non validi nel nome del foglio specificato|



###  Guarda anche
* modulo [`aspose.cells`](../../)
* classe [`CellsHelper`](/cells/python-net/it/aspose.cells/cellshelper)
