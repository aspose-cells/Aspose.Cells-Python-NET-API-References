---
title: calculation_mode proprietà
second_title: Aspose.Cells for Python via .NET API Riferimenti
description:
type: docs
weight: 60
url: /it/aspose.cells/formulasettings/calculation_mode/
is_root: false
---
##  calculation_mode proprietà

Ottiene o imposta la modalità per il calcolo della cartella di lavoro in MS Excel.

###  Osservazioni

Questa proprietà serve solo per salvare le impostazioni nel file del foglio di calcolo risultante
in modo che altre applicazioni (ad esempio MS Excel) possano agire di conseguenza durante il caricamento e la manipolazione del file risultante.
Per motivi di prestazioni per la maggior parte delle applicazioni degli utenti, non calcoliamo automaticamente alcuna formula nella cartella di lavoro,
indipendentemente dalla modalità impostata per questa proprietà.
Se l'utente ha bisogno di calcolare delle formule, si prega di chiamare sempre i metodi su oggetti diversi in base alle esigenze:
[`Workbook.calculate_formula`](/cells/python-net/aspose.cells/workbook/calculate_formula), [`Worksheet.calculate_formula`](/cells/python-net/aspose.cells/worksheet/calculate_formula),
[`Cell.calculate`](/cells/python-net/it/aspose.cells/cell/calculate), ...ecc.
###  Definizione:
```python
@property
def calculation_mode(self):
    ...
@calculation_mode.setter
def calculation_mode(self, value):
    ...
```

###  Guarda anche
* modulo [`aspose.cells`](../../)
* classe [`CalcModeType`](/cells/python-net/it/aspose.cells/calcmodetype)
* classe [`FormulaSettings`](/cells/python-net/it/aspose.cells/formulasettings)
