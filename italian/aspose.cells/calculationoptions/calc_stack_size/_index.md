---
title: calc_stack_size proprietà
second_title: Aspose.Cells for Python via .NET API Referenze
description:
type: docs
weight: 30
url: /it/aspose.cells/calculationoptions/calc_stack_size/
is_root: false
---
##  calc_stack_size proprietà

La dimensione dello stack per il calcolo ricorsivo delle celle. Il valore predefinito è 200.

###  Osservazioni

Quando è necessario calcolare una grande quantità di celle in modo ricorsivo nell'albero delle dipendenze,
StackOverflowException può essere causato nel processo di calcolo.
In tal caso, l'utente deve specificare un valore più piccolo per questa proprietà.
Per tale situazione, l'utente deve determinare il valore corretto per questa proprietà in base alle formule e ai dati effettivi.
Tuttavia, un valore troppo piccolo potrebbe causare un degrado delle prestazioni per il calcolo della formula e un valore inferiore a 2
renderà impossibile calcolare una formula che dipende da un'altra. Quindi, se il valore specificato è inferiore a 2,
verrà ripristinato a 2.
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
