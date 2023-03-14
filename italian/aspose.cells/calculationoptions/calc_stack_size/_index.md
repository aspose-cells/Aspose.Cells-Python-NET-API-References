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

Specifica la dimensione dello stack per il calcolo delle celle in modo ricorsivo.

###  Osservazioni

Quando ci sono grandi quantità di celle devono essere calcolate in modo ricorsivo nell'albero delle dipendenze,
StackOverflowException può essere causato nel processo di calcolo.
In tal caso, l'utente deve specificare un valore inferiore per questa proprietà.
Per tale situazione, l'utente deve determinare il valore corretto per questa proprietà in base alle formule e ai dati effettivi.
Un valore troppo basso può causare un degrado delle prestazioni per il calcolo della formula.
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
* modulo [aspose.cells](../../)
* classe [CalculationOptions](/cells/python-net/it/aspose.cells/calculationoptions)
