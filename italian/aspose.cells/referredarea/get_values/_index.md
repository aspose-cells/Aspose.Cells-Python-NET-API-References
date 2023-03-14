---
title: metodo get_values
second_title: Aspose.Cells for Python via .NET API Referenze
description:
type: docs
weight: 30
url: /it/aspose.cells/referredarea/get_values/
is_root: false
---
##  get_values() {#}
Ottiene i valori delle celle in quest'area.


###  ritorna

Se quest'area non è valida, "#REF!" verrà restituito;
Se quest'area è una singola cella, allora restituisce l'oggetto valore cella;
Altrimenti restituisce un array 2D per tutti i valori in quest'area.


```python
def get_values(self):
    ...
```




##  get_values(calculate_formulas) {#bool}
Ottiene i valori delle celle in quest'area.


###  ritorna

Se quest'area non è valida, "#REF!" verrà restituito;
Se quest'area è una singola cella, allora restituisce l'oggetto valore cella;
Altrimenti restituisce un array 2D per tutti i valori in quest'area.


```python
def get_values(self, calculate_formulas):
    ...
```


| Parametro| Tipo| Descrizione|
| :- | :- | :- |
| calculate_formulas | bool | In questo intervallo, se ci sono alcune formule che non sono state calcolate,<br/> questo flag indica se tali formule devono essere calcolate in modo ricorsivo|



###  Guarda anche
* modulo [aspose.cells](../../)
* classe [ReferredArea](/cells/python-net/it/aspose.cells/referredarea)
