---
title: Metodo calculate_data
second_title: Aspose.Cells for Python via .NET API Riferimenti
description:
type: docs
weight: 40
url: /it/aspose.cells.pivot/pivottable/calculate_data/
is_root: false
---
##  calculate_data(self) {#}
Calcola i dati della tabella pivot nelle celle.



```python

def calculate_data(self):
    ...
```


###  Osservazioni

Cell.Il valore nell'intervallo pivot non potrebbe restituire il risultato corretto se il metodo non è stato chiamato.
Questo metodo calcola i dati con una cache pivot interna e non con la fonte dati originale.
Pertanto, se l'origine dati viene modificata, chiamare prima il metodo RefreshData().

##  calculate_data(self, option) {#aspose.cells.pivot.PivotTableCalculateOption}
Calcolo delle tabelle pivot con opzioni



```python

def calculate_data(self, option):
    ...
```


| Parametro| Tipo| Descrizione|
| :- | :- | :- |
| option | [`PivotTableCalculateOption`](/cells/python-net/it/aspose.cells.pivot/pivottablecalculateoption) |  |



###  Guarda anche
* modulo [`aspose.cells.pivot`](../../)
* classe [`PivotTable`](/cells/python-net/it/aspose.cells.pivot/pivottable)
