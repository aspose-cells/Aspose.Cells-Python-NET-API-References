---
title: calculate_on_open proprietà
second_title: Aspose.Cells for Python via .NET API Riferimenti
description:
type: docs
weight: 30
url: /it/aspose.cells/formulasettings/calculate_on_open/
is_root: false
---
##  calculate_on_open proprietà

Indica se l'applicazione deve eseguire un calcolo completo quando la cartella di lavoro è aperta.

###  Osservazioni

Questa proprietà serve solo per salvare le impostazioni nel file del foglio di calcolo risultante
in modo che altre applicazioni (ad esempio MS Excel) possano agire di conseguenza quando caricano il file risultante.
Per motivi di prestazioni per la maggior parte delle applicazioni degli utenti, non calcoliamo automaticamente alcuna formula nella cartella di lavoro,
indipendentemente dal valore impostato per questa proprietà.
###  Definizione:
```python
@property
def calculate_on_open(self):
    ...
@calculate_on_open.setter
def calculate_on_open(self, value):
    ...
```

###  Guarda anche
* modulo [`aspose.cells`](../../)
* classe [`FormulaSettings`](/cells/python-net/it/aspose.cells/formulasettings)
