---
title: enable_calculation_chain proprietà
second_title: Aspose.Cells for Python via .NET API Riferimenti
description:
type: docs
weight: 70
url: /it/aspose.cells/formulasettings/enable_calculation_chain/
is_root: false
---
##  enable_calculation_chain proprietà

Abilita la catena di calcolo per le formule. Il valore predefinito è "false".

###  Osservazioni

Quando ci sono molte formule nella cartella di lavoro e l'utente ha bisogno di calcolarle ripetutamente
modificandone solo una piccola parte, potrebbe essere utile, ai fini delle prestazioni, abilitare la catena di calcolo.
D'altra parte, se la catena è abilitata, il mantenimento del modello della catena richiede memoria extra,
e richiede anche un po' più di tempo di CPU per alcune altre operazioni, come la modifica del valore di una cella o delle formule.
Dopo aver modificato questa proprietà da false a true, la catena di calcolo verrà analizzata e costruita
al momento del primo calcolo per la cartella di lavoro, quindi il tempo richiesto per il primo calcolo
potrebbe essere più di un calcolo normale senza catena.
###  Definizione:
```python
@property
def enable_calculation_chain(self):
    ...
@enable_calculation_chain.setter
def enable_calculation_chain(self, value):
    ...
```

###  Guarda anche
* modulo [`aspose.cells`](../../)
* classe [`FormulaSettings`](/cells/python-net/it/aspose.cells/formulasettings)
