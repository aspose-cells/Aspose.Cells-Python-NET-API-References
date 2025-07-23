---
title: force_full_calculation proprietà
second_title: Aspose.Cells for Python via .NET API Riferimenti
description:
type: docs
weight: 90
url: /it/aspose.cells/formulasettings/force_full_calculation/
is_root: false
---
##  force_full_calculation proprietà

Indica se calcolare tutte le formule ogni volta che viene attivato un calcolo.

###  Osservazioni

Questa proprietà serve solo per salvare le impostazioni nel file del foglio di calcolo risultante
in modo che altre applicazioni (ad esempio MS Excel) possano agire di conseguenza durante il caricamento e la manipolazione del file risultante.
Per motivi di prestazioni per la maggior parte delle applicazioni degli utenti, non calcoliamo automaticamente alcuna formula nella cartella di lavoro,
indipendentemente dal valore impostato per questa proprietà.
###  Definizione:
```python
@property
def force_full_calculation(self):
    ...
@force_full_calculation.setter
def force_full_calculation(self, value):
    ...
```

###  Guarda anche
* modulo [`aspose.cells`](../../)
* classe [`FormulaSettings`](/cells/python-net/it/aspose.cells/formulasettings)
