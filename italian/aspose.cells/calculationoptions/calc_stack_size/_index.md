---
title: calc_stack_size proprietà
second_title: Aspose.Cells for Python via .NET API Riferimenti
description:
type: docs
weight: 30
url: /it/aspose.cells/calculationoptions/calc_stack_size/
is_root: false
---
##  calc_stack_size proprietà

La dimensione dello stack per il calcolo ricorsivo delle celle. Il valore predefinito è 200.

###  Osservazioni

Quando ci sono grandi quantità di celle che devono essere calcolate ricorsivamente nell'albero delle dipendenze,
Potrebbe essersi verificato un errore StackOverflowException durante il processo di calcolo.
In tal caso, l'utente dovrebbe specificare un valore inferiore per questa proprietà.
In tali situazioni, l'utente deve determinare il valore corretto per questa proprietà in base alle formule e ai dati effettivi.
Tuttavia, un valore troppo piccolo può causare un degrado delle prestazioni per il calcolo della formula e un valore inferiore a 2
renderà impossibile calcolare una formula che dipende da un'altra. Quindi, se il valore specificato è inferiore a 2,
verrà reimpostato a 2.
###  Definizione:
```python
@property
def calc_stack_size(self):
    ...
@calc_stack_size.setter
def calc_stack_size(self, value):
    ...
```

###  Guarda anche
* modulo [`aspose.cells`](../../)
* classe [`CalculationOptions`](/cells/python-net/it/aspose.cells/calculationoptions)
